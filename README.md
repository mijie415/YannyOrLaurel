# Yanny还是Laurel？
![https://weibo.com/7418924704/MwUnVlJ76](微博)@摸鱼专用233

罗云熙在两年前发布了一个“一模一样”的视频，有位姐妹强烈建议我来分析一波[笑cry]

拿出N年不碰的MATLAB分别分析了一下罗云熙自己念的“Yanny”“Laurel”和原混合音频片段的specgram。首先说一下结论，提供的音频是对两种不同发音的组合，而两者的频段是有共同吻合之处的。在低质量录音中，“Yanny”发音频率相对较高，对高频音敏感的人会优先听到“Yanny”发音，对高频音不那么敏感的人群会听到“Laurel”发音。

用LPF过滤之后，我们能够比较清晰地听到音频里的“Laurel”发音；用HPF过滤后，我们能够比较清晰地听到“Yanny”发音。代码里的频率是我根据我个人听觉来的（不一定对所有人都起作用哈），不过反正代码都在这儿，大家想要自己尝试的话可以根据自己的听觉范围调节。第二种方法是使用不同的采样频率实现升降调/快慢速，也能很直观地听到差异。

我查了一下大范围的统计数据，看到了这样一句话：“Older people, whose ability to hear higher frequencies is more likely to have degraded, usually hear "Laurel"” （[doge]）
