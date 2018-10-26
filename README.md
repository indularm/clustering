## Clustering: an Introduction

The purpose of clstering data is to identify unique differences that cannot be otherwise determined by looking at data. The algorithms exploit different mathematical approaches to dfferentiate one data point form the other and conglomerate the points that has similar properties. It's an unsupervised learning method and is highly used in statistical data analysis. 

The most well known clustering method is the k-means clustering and we'll study here forth how to use the algorithm with our data

K- Means Clustering

The basic algorithms in step wise is as follows, 
  1. Determine the number of classes the data needs to be clsutered and randomly initialize the cluster centroid of each class within the data points. (Determining the number of clusters can be done by having a look in to the data with visualization techniques such as Prciple Component Analysis(PCA) or Selef Organizing Maps(Kohonen Networks) - we'll study those in upcoming lessons. Also it's valuable to remember that the algorithm is sensitive for the initial initialization of centroid points which we did randomly here)
  2. Each data point is assigned to the nearest neighbouring cluster centroid according to the distance from the centroid. 
  3.  
  
  
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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/indularm/clustering/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
