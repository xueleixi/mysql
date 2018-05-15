
# 排序

```sql

SELECT GROUP_CONCAT(id ORDER by field(word,'这个','分词','总','失败','啊')) as split_word,GROUP_CONCAT(word ORDER BY field(word,'这个','分词','总','失败','啊')) as split_word_text
FROM `dic_word` WHERE word IN('这个','分词','总','失败','啊');

```
