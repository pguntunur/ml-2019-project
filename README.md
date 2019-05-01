## Classifying aggression in Wikipedia comments

Using 100k comments gathered by the Wikipedia Detox project, we aim to create a program that can read in comments and generate a rating for how aggressive they are.

![_Dataset_](https://github.com/pguntunur/ml-2019-project/blob/master/photos/pic-dataset.png)

First, we run the comment data through various preprocessing steps, filtering out punctuation and stop words and using the data to create an array. Using the aggression ratings given by Wikipedia Detox, we then create a target vector of whether a comment is aggressive or not. After, we generate a vector using TfidfVectorizer that represents the words contained in each comment. From the data and target vectors, we finally use a LinearSVC model to fit the data with an accuracy of 91.4%.


<!---
You can use the [editor on GitHub](https://github.com/pguntunur/ml-2019-project/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

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

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/pguntunur/ml-2019-project/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

-->
