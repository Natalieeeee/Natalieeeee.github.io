## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Natalieeeee/Natalieeeee.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.
[test](/test.html)

```R
data(iris)

#使用 iris 資料繪圖
#histogram柱狀圖

sepalLength <- iris$Sepal.Length
hist(sepalLength, breaks = 15)點凸

# 1.點圖
plot(sepalLength)
plot(sepalLength, type = 'p',
     pch = 19)

# 1.1改變顏色和符號(pch)
plot(sepalLength, type = 'p',
     pch = 19, col='green')

# 1.2
plot(sepalLength, type = 'p',
     pch = 19, col='green',
     main = 'SpepalLength(cm)')

#拆線圖
plot(sepalLength, type = 'l',
     pch = 19, col='green', main = 'Iris data-sepal Length(cm),
     xlab = 'index', ylab = 'Sepal Length(cm))

#加上文字(text)
plot(sepalLength, type = 'l',
     pch = 19, col='red', main = 'Iris data-sepal Length(cm),
     xlab = 'index', ylab = 'Sepal Length(cm)')
#圖的精細控制
#改變顏色和符號(pch)
#help(pch)
```

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

![description](https://github.com/Natalieeeee/Natalieeeee.github.io/raw/master/img/DSC06567.JPG)

1. Numbered
2. List
4. List2
3. List5


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List
4. List2
3. List5


**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Natalieeeee/Natalieeeee.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
