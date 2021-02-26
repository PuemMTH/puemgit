# Python 3.9 Client And Server
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item


First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac

#1
mojombo#1
mojombo/github-flavored-markdown#1

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

def foo():
    if not bar:
        return True
        
I think you should use an
`<addr>` element here instead.

http://github.com - automatic!
[GitHub](http://github.com)

As Kanye West said:

> We're living the future so
> the present is our past.
> 

* Item 1
* Item 2
  * Item 2a
  * Item 2b

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

```python
import pymysql
db = pymysql.connect("localhost","root","ipuemipuem","python",\
    use_unicode=True,charset='utf8')
    # use_unicode=True,charset='utf8' เปิด utf8 เพื่อลองรับภาษาไทย
cursor = db.cursor()
def showuse():
    try:
        # sql = "SELECT * FROM user WHERE id = 1"
        sql = "SELECT * FROM user WHERE id BETWEEN 1 AND 10"
        cursor.execute(sql)
        # fetchall() คือ method ที่นำข้อมูลออกมาเก็บในตัวเเปล
        results = cursor.fetchall()
        for row in results:
        # "for row in results",loop เเต่ละเเถวจากตัวเเปล results เก็บไว้ในตัวเเปล
        # row ในรูปเเบบ Array
            print(row[0],'\t',row[1],row[2])
    except:
        print("Error")
showuse()
db.close()

#Cr.PuemMTH("กูเอง")
```
