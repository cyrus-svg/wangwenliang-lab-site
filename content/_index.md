---
# 首页配置
title:
date: 2024-01-01
type: landing

sections:
  # 实验室介绍
  - block: hero
    content:
      title: |
        王文亮实验室
        Wang Wenliang Lab
      image:
        filename: welcome.jpg
      text: |
        <br>

        欢迎来到**王文亮实验室**。我们致力于相关领域的前沿研究工作。

  # 简介板块
  - block: markdown
    content:
      title: 关于我们
      subtitle: ''
      text: |
        实验室简介占位文字。这里可以介绍实验室的研究方向、学术背景、主要成就等内容。

        ### 研究方向

        - 研究方向一
        - 研究方向二
        - 研究方向三

        ### 主要成果

        在相关领域发表了多篇高水平论文，取得了重要进展。
    design:
      columns: '2'

  # 团队成员按钮
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="查看研究团队 →" %}}
    design:
      columns: '1'

  # 最新论文
  - block: collection
    content:
      title: 最新发表论文
      text: ""
      count: 3
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: '1'
---