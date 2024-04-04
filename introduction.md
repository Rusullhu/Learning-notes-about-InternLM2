## 视频总结  
陈恺老师介绍了书生·浦语大模型的全链路开源体系，首先老师介绍了通用人工智能的发展趋势，NLP领域从特定任务模型向通用大模型的转变。老师还介绍了Interlm2的提升，包括支持多模态、8K语境和不同尺寸的模型，更好地提升语言建模能力、对话交互和智能体框架方面的能力。  
![[5188ab995fc3ddb51c86a0451123197.jpg]]
  
## 课程主体  
- 通用人工智能的发展方向：从单一任务模型转向通用大模型，解决多种任务和模态。
![[5188ab995fc3ddb51c86a0451123197 1.jpg]]
- Interlm2介绍：采用了新的数据清理过滤技术，高质量语料和有针对的数据补全提升了模型性能，模型使用更少数据也能达到上一代效果，整体性能增强。  支持复杂场景，作为基座模型，性能良好。  现在模型具有长上下文理解、优秀对话与创作、可媲美大学生的数学能力的能力。尤其是能够采用代码解释器，无需调用工具，也能提高数学能力。
- 完善了开源工具体系：覆盖数据到预训练、微调、部署和评测等全流程，可扩展到千卡训练，性能优化，可以接入HuggingFace。  支持增量续训，加入某个垂类领域知识，能保持很好的原生通用能力，这点非常赞。开放了Xtuner，多种微调算法，8GB的20系显卡即可微调。轻量化接口非常好，LMDeploy性能领先，每秒可生成2k+的tokens，支持模型轻量化、量化和推理服务，与评测工具无缝对接。
- 性能评测与差距：CompassKit里的OpenCompss支持数据污染检查清洗、长文本能力评测。能帮我们更科学的评测大模型整体能力。当前大模型整体理科能力上交叉，中文场景下国内模型表现出色。  
- 应用：未完待续