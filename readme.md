""
1匹配一个com格式邮箱字符串
2匹配一个密码 8-12位数字字母下划线构成
3匹配一个数 正数 负数 整数 小数 分数 百分数
4匹配一段文字以大写字母开头的单词  文字中可能有 iPython H-base 单词可能有大写 小写字母
"""

import re
# print(re.findall(r"\w+\.com","www.baidu.com,www.youdao,cn"))
# print(re.findall(r"\w{8,12}","1582546,2546afxc944185"))
# print(re.findall(r"-?\d+/?\.?\d*%?","55,-56,12,10.5,54%,1/2"))
