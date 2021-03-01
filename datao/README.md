### 数据说明
.pkl后缀的文件为服务的数据，已经转为向量，由pickle打包，保存为数组格式。<br>
.csv后缀的文件为链接数据，保存不同类型边的数据。<br>

#### bigfile
将大于25M的文件进行了压缩，包括<br>
1. api_textdata_tr_doc2vec.pkl API的文本描述信息，已经经过了摘要提取和Doc2vec的处理，文本转换为向量保存。<br>
2. api_otherdata.pkl API的属性信息，经过One-hot处理，转为向量保存。<br>

#### 其他文件
1. ms_textdata_tr_doc2vec.pkl Mashup的文本描述信息，已经经过了摘要提取和Doc2vec的处理，文本转换为向量保存。<br>
2. ms_otherdata.pkl Mashup的属性信息，经过One-hot处理，转为向量保存。<br>
3. api_time.csv API发布时间的数据，2006年1月份为1，2007年1月份为12，以此类推。<br>
4. ms_time.csv Mashup发布时间的数据，2006年1月份为1，2007年1月份为12，以此类推。<br>
5. api-ca.csv API-Category边<br>
6. api-pro.csv API-Provider边<br>
7. ms-api.csv Mashup-API边<br>
8. ms-ca.csv Mashup-Category边<br>
9. usr-api.csv Developer-API边<br>
10. usr-dms.csv Developer-(develop)Mashup边<br>
11. usr-fms.csv Developer-(follow)Mashup边<br>