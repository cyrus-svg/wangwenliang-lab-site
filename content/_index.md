---
# 首页配置
title:
date: 2024-01-01
type: landing

sections:
  # 顶部横幅
  - block: hero
    content:
      title: 王文亮实验室
      image:
        filename: welcome.jpg
      text: |
        <br>

        XX大学 XX学院

  # 实验室简介
  - block: markdown
    content:
      title: 实验室简介
      text: |

        本实验室隶属于XX大学XX学院，主要从事相关领域的科学研究工作。实验室由王文亮教授主持，现有博士后、博士研究生、硕士研究生若干名。

        <br>

        实验室秉承"严谨治学、追求卓越"的理念，致力于推动学科发展，培养优秀科研人才。

    design:
      columns: '2'
      background:
        color: white
      spacing:
        padding: ['50px', '30px', '50px', '30px']

  # 研究方向
  - block: markdown
    content:
      title: 研究方向
      text: |

        ### 方向一

        相关领域的基础理论研究，探索新方法与新思路。

        <br>

        ### 方向二

        应用技术开发与产业化研究，解决实际问题。

        <br>

        ### 方向三

        跨学科交叉研究，推动学科融合发展。

    design:
      columns: '3'
      background:
        color: '#F8F9FA'
      spacing:
        padding: ['50px', '30px', '50px', '30px']

  # 团队成员链接
  - block: markdown
    content:
      title:
      text: |
        <div style="text-align: center; padding: 30px 0;">
          <a href="./people/" class="btn btn-primary">查看研究团队</a>
        </div>
    design:
      columns: '1'
      background:
        color: white

  # 联系方式
  - block: markdown
    content:
      title: 联系方式
      text: |

        |  |  |
        |:---:|:---|
        | **地址** | XX省XX市XX区XX路XX号 XX大学 XX楼 XX室 |
        | **邮箱** | wangwenliang@example.edu.cn |
        | **电话** | +86-XXX-XXXX-XXXX |
        | **传真** | +86-XXX-XXXX-XXXX |

    design:
      columns: '1'
      background:
        color: '#F8F9FA'
      spacing:
        padding: ['40px', '30px', '40px', '30px']
---