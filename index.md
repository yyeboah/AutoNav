## Welcome to GitHub Pages
The vast majority of indoor navigation algorithms either rely on manual scene augmentation and labelling or exploit multi-sensor fusion techniques in achieving simultaneous localisation and mapping (SLAM), leading to high computational costs, hardware complexities and robustness deficiencies. This paper proposes an efficient and robust indoor navigation framework for robots which relies solely on visual input from a single RGB camera. Firstly, we put forward an end-to-end trainable siamese deep convolutional neural network (DCNN) which decomposes navigation into orientation and localisation in one branch, while achieving semantic scene mapping in another. In mitigating the computational costs associated with DCNNs, the proposed model design shares a significant amount of convolutional operations between the two branches, streamlining the model and optimising for efficiency in terms of memory and inference latency. Secondly, in addressing the insufficiency of datasets for indoor navigation, a transfer learning regime is explored in demonstrating how such siamese DCNNs can be efficiently pretrained for high convergence rates without extensive manual dataset labelling. The resulting siamese framework efficiently combines semantic scene understanding with orientation estimation towards predicting collision-free and optimal navigation paths. Experimental results demonstrate that the proposed framework is accurate, efficient and outperforms existing "navigation-by-classification" variants.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/yyeboah/yyeboah.github.io-AutoNav/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
