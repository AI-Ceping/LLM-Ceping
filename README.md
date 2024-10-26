<!-- markdownlint-disable MD033 MD041 -->
<p align="center">
  <img src="https://ai-ceping.com/wp-content/uploads/2024/08/%E9%A6%96%E9%A1%B5Robot.png" alt="Your Logo" width="200" height="200">
</p>


<div align="center">
  
# LLM-Ceping 全面的大语言模型评测知识库


  <!-- prettier-ignore-start -->
  <!-- markdownlint-disable-next-line MD036 -->
  _✨ 用数据淘金，人工智能需要你助力！ ✨_
  <!-- prettier-ignore-end -->
</div>
<p align="center">
   <a href="https://AI-Ceping.com">
    <img src="https://img.shields.io/badge/AI--Ceping-数据共建平台-lightgrey?style=social&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAACNiR0NAAACRElEQVQ4y62UvU9TYRTGf+e8t1RLaYFKhJuYsqhgDGqiUYhiHGRyaKKzo5IoiTjppAmDEWUw0f/AzYXRmUES3XCQGIy5URFDRBQLtLfvfR1skc9Cg0/ybOd5zmeO+LmgGxgBjgFjwADwAfCB58A5QPiHBeA68GJ6NBuxDgo8ALqBBNAH3BChxTOMeIYewJTjKkwDd4FDfi6QDYbppJ5el+BUzNDeljHnW5tNHZujC7gPNG4w3JdWT9fmiYlgYp6IMYJsbihADuj3c0FsjeEWgp0gDgwCfatbV3aHFmAIOFgx3a0hwHHgXnlZ/8VQgMvANT8XxLztImuY521gqmqFUtvG9gOPqxo6V1uZQFYBu05kHUQCrmQd9Xtky3GsZqUGL3K8TSX05M98RDwmrhC6iVKJz6J8yS+71nRSsVHEUsGtqNJJpTG5trm5X7a4sOhemVTn4PtMStubU+ol4jq2WIiGSpbAM3xtatBDnopJJnSxqUHzFSbikldhhda63z8WopeRo1/8XCAitBjFt5bAwfz0aNb5uUBVaPMMB5BtzsthQ8tH55iV9itBZ2gZcI4jwDjwBPhWF+NwWOKWc3SVP041hMAb4JnXmvGezs7bC0sFJ8DZ8rU89DPe8MycvbRcdDvdczfQoXUxeorhisgAZ4wh63mcKISulqNRoFejiMlUvWIU9sbFiTBpI6ZxTKXrFdW/L6kajUIiLqgwIUevfrrYlNRhUTqKIeMz30s3iyXeNae0tzGpj1R2NMNSaHk9M2fv/AFcYriW8cKPugAAAABJRU5ErkJggg==" alt="license">
  </a>
<br>
  <a href="https://tapy80meo6.feishu.cn/wiki/OY2FwN1hTiJXJ5kxbuucPIMLn2c?fromScene=spaceOverview">
    <img src="https://img.shields.io/badge/%E9%A3%9E%E4%B9%A6-AI--Ceping知识库-lightgrey?style=social&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz48c3ZnIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDQ4IDQ4IiBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxwYXRoIGQ9Ik0xNyAyOUMyMSAyOSAyNSAyNi45MzM5IDI4IDIzLjQwNjVDMzYgMTQgNDEuNDI0MiAxNi44MTY2IDQ0IDE3Ljk5OThDMzguNSAyMC45OTk4IDQwLjUgMjkuNjIzMyAzMyAzNS45OTk4QzI4LjM4MiAzOS45MjU5IDIzLjQ5NDUgNDEuMDE0IDE5IDQxQzEyLjUyMzEgNDAuOTc5OSA2Ljg2MjI2IDM3Ljc2MzcgNCAzNS40MDYzVjE2Ljk5OTgiIHN0cm9rZT0iIzMzMyIgc3Ryb2tlLXdpZHRoPSI0IiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiLz48cGF0aCBkPSJNNS42NDgwOCAxNS44NjY5QzUuMDIyMzEgMTQuOTU2NyAzLjc3NzE1IDE0LjcyNjEgMi44NjY5NCAxNS4zNTE5QzEuOTU2NzMgMTUuOTc3NyAxLjcyNjE1IDE3LjIyMjggMi4zNTE5MiAxOC4xMzMxTDUuNjQ4MDggMTUuODY2OVpNMzYuMDAyMSAzNS43MzA5QzM2Ljk1OCAzNS4xNzc0IDM3LjI4NDMgMzMuOTUzOSAzNi43MzA5IDMyLjk5NzlDMzYuMTc3NCAzMi4wNDIgMzQuOTUzOSAzMS43MTU3IDMzLjk5NzkgMzIuMjY5MUwzNi4wMDIxIDM1LjczMDlaTTIuMzUxOTIgMTguMTMzMUM1LjI0MzUgMjIuMzM5IDEwLjc5OTIgMjguMTQ0IDE2Ljg4NjUgMzIuMjIzOUMxOS45MzQ1IDM0LjI2NjcgMjMuMjE3IDM1Ljk0NiAyNi40NDkgMzYuNzMyNEMyOS42OTQ2IDM3LjUyMiAzMy4wNDUxIDM3LjQ0MjggMzYuMDAyMSAzNS43MzA5TDMzLjk5NzkgMzIuMjY5MUMzMi4yMDQ5IDMzLjMwNzIgMjkuOTkyOSAzMy40NzggMjcuMzk0NyAzMi44NDU4QzI0Ljc4MyAzMi4yMTAzIDIxLjk0MDUgMzAuNzk1OCAxOS4xMTM1IDI4LjkwMTFDMTMuNDUwOCAyNS4xMDYgOC4yNTY1IDE5LjY2MSA1LjY0ODA4IDE1Ljg2NjlMMi4zNTE5MiAxOC4xMzMxWiIgZmlsbD0iIzMzMyIvPjxwYXRoIGQ9Ik0zMy41OTQ1IDE3QzMyLjgzOTggMTQuNzAyNyAzMC44NTQ5IDkuOTQwNTQgMjcuNTk0NSA3SDExLjU5NDVDMTUuMjE3MSAxMC42NzU3IDIzIDE2IDI3IDI0IiBzdHJva2U9IiMzMzMiIHN0cm9rZS13aWR0aD0iNCIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIi8+PC9zdmc+" alt="feishu">
  </a>
  <a href="https://mp.weixin.qq.com/s/uDZ8O7JIJrkrJ-APuJBGIA" target="_blank">
    <img alt="Wechat" src="https://img.shields.io/badge/wechat--公众号-brightgreen?logo=wechat&logoColor=white" />
  </a>
  <a href="https://space.bilibili.com/3546734703676231" target="_blank">
    <img alt="BiliBili" src="https://img.shields.io/badge/BiliBili-pink?logo=bilibili&logoColor=white" />
  </a>
  <a href="https://www.xiaohongshu.com/user/profile/6645ba3e0000000007007aa2?xsec_token=&xsec_source=pc_note" target="_blank">
    <img alt="Xiaohongshu" src="https://img.shields.io/badge/Xiaohongshu--brightred?style=social&logo=data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAcHBwcIBwgJCQgMDAsMDBEQDg4QERoSFBIUEhonGB0YGB0YJyMqIiAiKiM+MSsrMT5IPDk8SFdOTldtaG2Pj8ABBwcHBwgHCAkJCAwMCwwMERAODhARGhIUEhQSGicYHRgYHRgnIyoiICIqIz4xKysxPkg8OTxIV05OV21obY+PwP/CABEIADwAPAMBIgACEQEDEQH/xAAbAAEAAQUBAAAAAAAAAAAAAAAABQEDBAYHAv/aAAgBAQAAAACFAAFM3CkrGXGeLvWdUncvcuR6be6BATlY5poBUAAf/8QAGQEBAAIDAAAAAAAAAAAAAAAAAAIDAQQF/9oACAECEAAAAOKLp2auZqoj/8QAGgEBAAIDAQAAAAAAAAAAAAAAAAQFAQMGB//aAAgBAxAAAAD3oUsOs6vXFxYzB//EACkQAAICAgIBAgYCAwAAAAAAAAECAwQFEQASBhMhEBQxQVFhIkBCcZH/2gAIAQEAAT8A/o0sfcvu6VYTIyIXYAgaX8+/wsYjJVnrJLVYPOneNBpmYf6GzyTH34unqU507MFXtGw2T9hy1gsxUijlnoyqjr2BC9tD96+nGilREdo2VHB6MQQG1+D9/hBGJZ4Iz/nIq/8ATrmMx9PHeUZOrVQrGuOB0SW92PI8di4MBhcrJA7k2+tgKd91BPsAeeZ21pZLG3asbx3SgJdtkIutBNH255PJk7efxmPrWY4tRrYjLgaEib9+dcms2MMlyD0REwtLobkfWgV/W+eXU8tTetFaljep2k+U6fRQT9Oa5DK0M0Uya7Rurjf5U75i/Iscb+Yy1udo5po/Tjg672oA1o8xeUSSnTxVqf5eulv12n1sqANgD99uZC3icrfSK75DK9SCPaOYwC0jH6AKv2HPMLPjmTjNutkzJZjiWNIgpAYb5nb+MvxeOwi1/GGARzsq7MewvPJshjJcfh6FG0bAqIQ0nUr/AGv/xAAgEQEAAgIBBAMAAAAAAAAAAAABAhEAAzEEEiAhIlFx/9oACAECAQE/APDVq70vi6w0BFZP1xh00FS301ebIdsmOa9kocfuG+QUg471ZfE91eTkzbqvH//EACURAAEDAwMDBQAAAAAAAAAAAAECAxEABBIFITETFCAGIiNSkf/aAAgBAwEBPwDw1bVexRihGThRkmeIBA3/AGnNdcXdNMsM89VJK/sinfU942i1WWmfkSVFEmYFafdd5aoflPumMTNX+mW98BmSlWMZJ5xmYp3QmFvF1t1bat4xgwVcnemNCaZQwkXDiuiV4ExtmIqxs0WdullC1K3JJPJKjPj/AP/Z" />
  </a>
  <br>
<p align="center">
<a href="#简介">简介</a> &nbsp;&bull;&nbsp;
<a href="#用户贡献">用户贡献</a> &nbsp;&bull;&nbsp;
<a href="#AI-Ceping大模型测评知识库">AI-Ceping 大模型测评知识库</a> &nbsp;&bull;&nbsp;
<a href="https://github.com/AI-Ceping/LLM-Ceping/wiki">wiki</a> &nbsp;&bull;&nbsp;
<a href="#FAQ"> FAQ </a> &nbsp;&bull;&nbsp;
<a href="#相关文献"> 相关文献 </a>

</p>
  <br>
</p>


## 背景
在人工智能领域，大语言模型 LLM（Large Language Model）的发展正以前所未有的速度推进，这些模型通过深度学习和海量数据训练，在语言理解、生成和翻译等方面取得了显著的进展。随着ChatGPT等模型的诞生， LLM 的应用场景不断拓展，从简单的对话系统到复杂的内容创作，都显示出了巨大的潜力和价值。

然而，随着 LLM 的快速发展，如何有效评估这些模型的性能和安全性成为了一个紧迫的问题。传统的评测方法往往依赖于专家的主观判断，缺乏客观性和可重复性。此外，随着模型规模的增大和复杂性的提升，单一的评测指标已经难以全面反映模型的综合能力。



# 简介
⭐[LLM-Ceping](https://ai-ceping.com/)  AI-Ceping，一个由同济大学开发的大模型评测数据收集平台。是为了应对大语言模型（LLM）评测的迫切需求，尤其是在 ChatGPT 掀起的研究和应用浪潮之后。使命是构建一个权威、公正、透明的评测环境，以客观评估大型语言模型的能力，并反映这些模型需要解决的问题。
> [!TIP] 
> - 评测方法 通过用户提问和撰写参考答案来参与大模型的训练和评测。用户可以通过向模型提问，让三个大模型生成回答，并获得一定的奖励。此外，用户还可以选择喜欢的模型回答，涉及文字、语音和视频等多模态内容
> - 评测标准 评测方法包括使用强模型（如 GPT-4）来打分评测回答质量，衡量模型的指令遵循能力和有用性。打分维度包括事实正确性、满足用户需求、清晰度、完备性、丰富度等多项.
> - 目标 期望通过每位用户对大模型应用的理解以及自身具备的不同领域的知识，设计高质量的评测数据来对大模型进行综合的评估。通过这个平台，用户可以为大模型的训练与评测注入活力，
AI-Ceping 还提供了详细的任务概况说明，包括背景、奖励规则、活动须知、反作弊说明和活动安排等，以确保评测活动的顺利进行。通过这个平台，用户可以为大模型的训练与评测注入活力，同时也有机会获得现金奖励
---

# 用户贡献
> [!IMPORTANT] 
> - 我们的平台已经吸引超过 _**18,875**_ 名来自不同地区的用户。已经累积了 _**336,233**_ 条数据提交记录，其中覆盖了众多主题和领域。包含超 _**501**_ 种不同的标签 <br>
> - 在此列举了平台核心用户 （前十名）
> - <img src="https://github.com/user-attachments/assets/ff708041-1b2d-41af-9825-bcacc596c176" width="" height="" alt= "截图于24/10/27">

---
# 平台核心功能

| <b> 以下包含了平台核心功能  </b> |   |
|:---:|:---:|
|<img src="https://github.com/user-attachments/assets/97458dbd-9e28-45a5-9ca6-f9fc584ec58f" width="700" height="300" alt=""> | <b>单条数据</b>｜向大模型提真实问题<br>向模型提问，让三个大模型生成回答，即可获得奖励<br>|
| <b> 数据扩写 </b>｜撰写问答对，给大模型出题 <br> 提问并撰写参考答案，为大模型训练与评测注入血液 |  <img src="https://github.com/user-attachments/assets/60bcbde3-bbbe-41a4-b926-0c8716d6b442"  width="700" height="300" alt=""> | <br>
|<img src="https://github.com/user-attachments/assets/1f2fea1b-cd99-4ad3-adcb-94ec6089b2c8"  width="700" height="300" alt=""> |  <b> 评测任务</b>｜做选择题，选择你满意的内容 <br> pick你喜欢的模型回答，回答涉及文字、语音和视频等多模态内容，等你来评价！ | <br>
| <b>  模型擂台</b>｜最强大模型，由你来评 <br> 随机派送2个大模型为你服务，输入问题，选择你喜欢的回答，看看哪个模型表现好​    |  <img src="https://github.com/user-attachments/assets/3b588272-1c8a-4caf-bc82-6f5650e19220"  width="700" height="300" alt=""> | <br>


---

## AI-Ceping大模型测评知识库
  这里我们与社区用户共建了[《AI-Ceping 大模型测评知识库》](https://tapy80meo6.feishu.cn/wiki/OY2FwN1hTiJXJ5kxbuucPIMLn2c?fromScene=spaceOverview)，帮助大家快速了解入门AI大模型 ：
  > [!NOTE]
  >__📕 AI 大模型评测知识分享__。从0到1带大家入门大模型评测，成为Prompt大师和大语言模型评测专家。<br>
  >__📗   各赛道大模型榜单维护__。从市面上繁杂的大模型排行榜甄选出最具参考价值的LeaderBoard，降低用户的时间成本。<br>
  >__📘   大模型资讯更新__。最终标杆模型最新动态，快速捕捉大模型发现最前沿讯息。<br>
  >__📙   数据集渠道整合__。从海量开源数据集筛选优质数据集，方便大模型使用者快速微调、评测。<br>
  >__📙   共建[ AI-Ceping（爱测评）](https://ai-ceping.com/) 社区：大模型数据灵感众筹平台__。由同济大学发起，鼓励用户通过自己的创意和灵感，贡献真实的AI语料，以助于大模型的持续迭代和维护。<br>

## FAQ
请先访问我们的项目[Wiki](https://github.com/AI-Ceping/LLM-Ceping/wiki)，这里汇集了常见问题的解答和操作指南。如果Wiki中没有你要找的答案，欢迎提出你的问题，我们会尽快回复。

  - [数据构建操作流程](https://github.com/AI-Ceping/LLM-Ceping/wiki/%E5%B9%B3%E5%8F%B0%E6%93%8D%E4%BD%9C%E6%96%B9%E6%B3%95) 
  - [如何构思出优秀的数据？](https://github.com/AI-Ceping/LLM-Ceping/wiki/%E5%A6%82%E4%BD%95%E6%9E%84%E6%80%9D%E5%87%BA%E4%BC%98%E7%A7%80%E7%9A%84%E6%95%B0%E6%8D%AE)
  - [大模型评测小白入门指北](https://github.com/AI-Ceping/LLM-Ceping/wiki/%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%AF%84%E6%B5%8B%E5%B0%8F%E7%99%BD%E5%85%A5%E9%97%A8%E6%8C%87%E5%8C%97)



## 相关文献
# Prompt Engineering 提示词工程

| 资源名称  | 资源描述 | 资源链接     |
| :---        |    :----   |          :--- |
|   吴恩达讲ChatGPT提示工程    |    吴恩达与OpenAI官方合作的ChatGPT提示工程课程   |  [Bilibili 视频](https://www.bilibili.com/video/BV1fk4y1J7Af/) |
|  大模型时代的科研基础之：Prompt Engineering   |  微软亚洲研究院高级研究员王晋东讲提示词工程    |  [Bilibili 视频](https://www.bilibili.com/video/BV13P41197c6/) [知乎文字版](https://zhuanlan.zhihu.com/p/631922240)  |

# LeaderBord （社区评测榜单）
## 基础模型榜单
| 榜单名🚀 | 榜单介绍💬 | 榜单详情📄 |
|--------|----------|----------|
| Leaderboard | LMSYS Chatbot Arena 是一个由众包方式建立的大型语言模型（LLM）评估开放平台,已经收集了超过 1,000,000 人工成对比较数据，并使用 Bradley-Terry 模型对 LLM 进行排名，并在 Elo 评分系统中显示模型评分。 | ![image](https://github.com/2575044704/LLM-Ceping/assets/19410065/5d2dff2a-a38e-4381-9a91-64a67ce238a0) <br> [HuggingFace🤗](https://chat.lmsys.org/?leaderboard) <br> [Blog🎞](https://lmsys.org/blog/2023-05-03-arena/) <br> [GitHub🔧](https://github.com/lm-sys/FastChat) <br> [DataSet📂](https://github.com/lm-sys/FastChat/blob/main/docs/dataset_release.md) |
| C-Eval: A Multi-Level Multi-Discipline Chinese EvaluationSuite for Foundation Models | ![image](https://github.com/2575044704/LLM-Ceping/assets/19410065/986c9f6a-761f-4350-b719-2f08123aab09) C-Eval是全面的中文基础模型评估套件，涵盖了52个不同学科的13948个多项选择题，分为四个难度级别。 | ![image](https://github.com/2575044704/LLM-Ceping/assets/19410065/eef91abc-fd77-4920-8701-4b93d4dfff33) ![image](https://github.com/2575044704/LLM-Ceping/assets/19410065/eb1b5d7f-9ceb-4a91-a332-f18649202170) <br> 🌐 网站 [https://cevalbenchmark.com](https://cevalbenchmark.com) • 🤗 [Hugging Face](https://huggingface.co/datasets/ceval/ceval-exam) • ⏬ [数据](https://github.com/hkust-nlp/ceval/blob/main/README_zh.md#%E6%95%B0%E6%8D%AE) • 📃 [论文](https://arxiv.org/abs/2305.08322) 📖 [教程](https://github.com/hkust-nlp/ceval/blob/main/resources/tutorial.md)|

## 多模态榜单
| 榜单名🚀 | 榜单介绍💬 | 榜单详情📄 |
|----------|-------------|------------|
| OpenCompass 多模态评测月度榜单 | 展示了不同多模态模型在各项多模态评测基准上的性能，以平均分的降序排序。目前榜单基于以下 8 个数据集进行平均分计算：MMBench v1.1 (中英测试集), MMStar, MMMU (验证集), MathVista (迷你测试集), HallusionBench, AI2D (测试集), OCRBench, MMVet。<br>本榜单目前仅包含开源模型或是公众可访问的 API 模型。如果你想在榜单上添加新模型，并确认它符合条件，请在 VLMEvalKit 中提交 PR 以支持新模型，我们会随后完成评测与榜单更新。 | ![image](https://github.com/2575044704/LLM-Ceping/assets/19410065/c2cffc4e-283c-4d68-8345-dffe3b57b34d) <br> 🌐 [官方网站](https://opencompass.org.cn/) · 📖 [数据集社区](https://hub.opencompass.org.cn/home) · 📊 [性能榜单](https://rank.opencompass.org.cn/home) · 📘 [文档教程](https://opencompass.readthedocs.io/zh_CN/latest/index.html) · 🛠️ [安装](https://opencompass.readthedocs.io/zh_CN/latest/get_started/installation.html) |
| OpenVLM Leaderboard | 这个排行榜上分享了通过VLMEvalKit开源框架获得的VLM的评估结果 | ![image](https://github.com/2575044704/LLM-Ceping/assets/19410065/ca28c2d9-c911-4cea-8bac-28df74314f32) <br> [https://huggingface.co/spaces/opencompass/open_vlm_leaderboard](https://huggingface.co/spaces/opencompass/open_vlm_leaderboard) |

## Star History

<a href="https://star-history.com/#AI-Ceping/LLM-Ceping&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=AI-Ceping/LLM-Ceping&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=AI-Ceping/LLM-Ceping&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=AI-Ceping/LLM-Ceping&type=Date" />
 </picture>
</a>
