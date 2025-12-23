---
title: 其他内容
type: landing # 使用组件化布局

sections:
  - block: markdown
    content:
      title: 欢迎
      text: |
        这是使用组件构建的 Others 页面。

  - block: collection
    content:
      title: 精选文章
      text: 这里是该文章的简要描述。
      filters:
        folders:
          - others # 更改为你想要链接的文章文件夹路径
        count: 1
    design:
      view: card # 使用卡片视图以显示缩略图和摘要
      columns: '1'
---