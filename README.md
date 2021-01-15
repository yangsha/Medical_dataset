# Medical_dataset
Chinese dataset for entity and relation extraction research based on Medicine instructions.


1.为了对医药说明书领域的实体关系抽取技术进行研究，本文构造了一份基于医药说明书的标注语料，从爬取的说明书中文本筛选出200篇包含较多实体关系内容的说明书作为标注对象；
  标注工具选择的是开源BRAT标注工具.
  
 
  标注过程如下图所示:
  
  
  ![Image text](https://github.com/yangsha/Medical_dataset/blob/master/1.jpg)
  
  
  标注结果在data文件夹内，该文件夹内包含200篇txt文档和对应的200篇标注结果文档.每篇文档中都标注出了对应的实体和关系，可以基于该标注语料进行实体和关系抽取；
  
  
 2.表抽取是文本提出的新任务，旨在从非结构化的说明书文本中抽取出结构化的表信息，为了研究说明书的用法用量表抽取，本文基于爬取的说明书文本，标注了一份说明书用法用量语料，选择200篇说明书用法用量文本，对其进行标注，部分标注结果如下图所示：
 
  ![Image text](https://github.com/yangsha/Medical_dataset/blob/master/2.jpg)
 
  
   标注结果在dosage文件夹内，该文件夹内包含200篇txt文档和对应的200篇标注结果json文档.
   
  
  
  
  
  
   
   
