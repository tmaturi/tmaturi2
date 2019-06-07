
## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/tmaturi/tmaturi2/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

<ul>
{% for paper in site.data.papers %}
  <li>
      {{ paper.Name }} {{paper.Year}}. {{ paper.Title }}, {{ paper.Journal }}, {{ paper.Volume }}: {{ paper.Pages }}.
  </li>
{% endfor %}
</ul>
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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/tmaturi/tmaturi2/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

### Current PhD students

- Ms Kholood Alyazidi: `Nonparametric predictive inference for inventory decisions' (jointly supervised by Frank Coolen). To start October 2018.

- Mr Abdulmajeed Alharbi: `Nonparametric predictive inference for classification' (1st supervisor Frank Coolen). To start October 2018.

- Mr Masad Alrasheedi: `Nonparametric predictive inference for credit scoring and loan data' (2nd supervisor Frank Coolen). To start October 2018.

- Mr Assamh Alluhayb: `Nonparametric predictive inference bootstrap with right-censored data' (started April 2018, jointly supervised by Frank Coolen), Department of Mathematical Sciences, Durham University.

- Ms Andrea Mikulandova: `Reproducibility of statistical tests in pharmaceutical products development' (started October 2017, jointly supervised by Frank Coolen; EPSRC-CASE project with AstraZeneca), Department of Mathematical Sciences, Durham University.

- Ms Fatimah Alghamdi: `Reproducibility of statistical tests based on randomised response data' (started October 2017, jointly supervised by Frank Coolen), Department of Mathematical Sciences, Durham University.

- Mr Ali Mahnashi: `Nonparametric predictive inference for multiple future observations based on right-censored data' (started April 2017, jointly supervised by Prof Frank Coolen), Department of Mathematical Sciences, Durham University.

- Ms Ting He: `Nonparametric predictive inference for discrete time option pricing' (started Oct 2015, jointly supervised by Prof Frank Coolen), Department of Mathematical Sciences, Durham University.

- Mr Junbin Chen: `Nonparametric predictive inference in finance' (started Feb 2016, jointly supervised by Prof Frank Coolen), Department of Mathematical Sciences, Durham University.

- Mr Banjaran Surya Indrastomo: 'Demand and Supply Condition for Islamic Finance and Banking in Indonesia: An Investigation to the Behavioural Norms of Individual and Organisational Agents’ (started Oct 2014 - 1st supervisor Prof Mehmet Asutay), Durham University Business School.


### Past PhD students

- Mr Howard Dove (Mr Hoang Duong, 2018): *Distress Risk, Financial Crisis and Investment Strategies: Evidence from the United Kingdom* (1st supervisor Prof Rob Dixon), Durham University Business School.

- Ms Manal Alabdulhadi (2018): `Direct nonparametric methods for setting diagnostic thresholds' (jointly supervised by Prof Frank Coolen), Department of Mathematical Sciences, Durham University.

- Ms Noryanti Binti Muhammad (2016). `Predictive inference with copulas for bivariate data' (jointly supervised by Prof Frank Coolen), Department of Mathematical Sciences, Durham University.
