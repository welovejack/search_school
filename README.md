# 1. 测试地图插件
优先处理关键点内容，通过CSDN上成功的demo测试，并标注学校位置；

# 2. 获取学校具体数据；
帮我查找map_demo.html中八个小学的如下数据：公立还是私立、学校位置、学校介绍、外界评价、升学情况、入学条件、学区范围；

# 3. 将数据添加至地图网页中
请生成一个包含上面的推荐内容的 HTML 页面,用好看的图像化表达出来。
​
页面应使用 Bootstrap 5 框架进行布局和样式设计，并包含以下几个部分：
​
1.  头部（Header）：
    *   包含一个标题，显示“青浦新城地铁站周边小学”。
    *   包含一个副标题，显示“上海五大新城之一，未来潜力无限”。
    *   包含一个更新时间，显示“更新时间: (自动获取今天时间，如：2025年4月12日)”。
​
2.  地图（Map）：
    *   将map_demo.html中高德地图嵌入网页中，显示所有小学学校的位置。
    *   地图应具有 100% 的宽度和 400px 的高度。
​
3.  小学列表（Cafe List）：
    *   以卡片形式展示小学学校信息，每行显示 4 个小学学校，共显示4行。
    *   住宿小区信息应包括：
        *   学校名称
        *   位置
        *   学校简介
        *   外界对学校的评价
        *   升学情况
        *   入学条件
        *   学校对应学区
    *   使用 Unsplash API 获取学校的图片，每张图片的高度为 200px。
​

4.  页脚（Footer）：
    *   包含版权信息，显示“© 2025 地铁站周边学校推荐 | 数据来源: 高德地图 | 制作：LucianaiB”。
​
使用 CSS 自定义样式，包括：
​
*   主色调（primary-color）：#6f4e37
*   辅助色调（secondary-color）：#f5f5dc
*   强调色调（accent-color）：#d4a76a
*   卡片hover效果：鼠标悬停时卡片向上移动并增加阴影
​
确保页面具有响应式布局，可以在不同设备上正常显示。

Reference:

[在网页中插入高德地图插件](https://blog.csdn.net/qq_42445490/article/details/89155610?depth_1-utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-1&utm_source=distribute.pc_relevant.none-task-blog-BlogCommendFromMachineLearnPai2-1)