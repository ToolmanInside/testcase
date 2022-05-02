# 用法

1. 每个json都有对应名字的文件夹，一个文件夹即一个test case
2. 每个test case里面都有S0, S1, S2...，一个S即一个step
3. 每个step里面有四个东西：pngs（widget的裁剪截图）、event_metadata.txt（这个step的关键信息）、graph.dot（widget的层级关系图）、texts.txt（widget的信息）
4. 这四个东西里最关键的是`event_metadata.txt`
5. `event_metadata.txt`共有四行，其中第一行表示widget的裁剪截图路径，第二行表示widget在手机上的坐标（**注意：手机的型号为Pixel XL**），第三行为对应的text信息，第四行为event类型