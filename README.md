# comments_keywords_abstract
题目：使用python3提取美团外卖的评论，并根据算法提取出关键词，做成评论标签。最后，将评论标签展现在前端界面上(数据是实时从美团获取的，标签是实时生成的)。

## 实现准备：
pycharm软件和mongoDB数据库

## 文件说明
运行save_shops_info.py文件可获取美团.美食上汕头市所有店铺的基本信息。如：商铺名字，uuid，以及跳转到详情页所需要的poiId.并保存到mongoDB和.csv文件中。

运行detailPage_getComments.py文件可读取数据库中的商铺基本信息，以此获得所有评论。并将评论信息保存到mongoDB数据库和.csv文件夹中。

output_file文件夹里的是保存的所有数据。如：商铺名字，uuid，poiId，以此美团店家的所有评论。所以该文件夹会有点大。

## 特别说明
工程项目使用的是绝对路径，放在‪D:\python\meituan路径下。因此保存项目时，避免出错，应该将项目保存至此。
