为中文文本识别提供文本素材，用于后续的语料合成


----
包含如下几类：
    1.文本语料：支持多个语料文件随机选取，可设置每个语料被选中的概率
    2.特殊语料：识别任务中常见的语料，已完成的有：日期、身份证、子地址、数字（带常见单位）、英文字符串
    3.任务语料：可根据任务重写BaseRender基类，提供基于任务的语料