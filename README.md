# 公交平台可视化系统
该项目是北京是公交线网优化可视化平台，主要分为三个模块的功能：
1. 原始线网，通过调取高德API，选择所需要的线路并将其展示，该处展示的线路是区分上下行的。
2. 路网状况，主要区域在北京奥林匹克公园附近，展现该区域内一段时间的事故情况，将路段分为不同的编号，通过输入编号即可查询。
3. 优化线网，提出某些线网优化的方法将其运用到北京市实际的公交线路中，选取的优化的线路与原始线网中展示的线路对应，通过直观比对分析优化前后的差别并对优化前后指标进行展示。
目前部分示例数据已展示完成，后期如有更多数据直接传入后端数据库即可。
现将该项目的代码开源，欢迎读者进行功能的完善以及界面的美化，该项目的网站地址为：https://roadnetvisual.netlify.app/