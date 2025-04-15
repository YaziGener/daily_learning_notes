*Language Model Training Paradigm*

*1.训练阶段*
*2.Pretrain,SFT,Reward Model,PPO*
*3.Llama训练方式的差异*

1.一系列步骤
SFT -> Supervised Fine-Tuning(微调)

Pretrain

1.Continue learning plenty of human paper
2.Learining how human use word by word
3.Learn the most human knowledge and large amount literal expression style(like native speaker learn mother tongue)
4.The amount of data pretrain need and computing resources

Llama use 15t tokens

How to start?
段落联合概率：让一个模型，能一字不落的生成整个段落的概率
预训练阶段：模型不需要真的输出“下一个字”，而是输出所有“候选字”的概率清单

Joint Probability of a Paragraph: The probability that a model can generate an entire paragraph word-for-word (or character-for-character) without any deviation.

Pretraining Phase: The model doesn't actually need to output the next character; instead, it outputs a probability distribution over all possible next characters. 31：35