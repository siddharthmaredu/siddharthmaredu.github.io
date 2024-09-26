---
layout: post
title: Portfolio
subtitle: Statistical Analyses Projects
tags: [business analytics, portfolio]
comments: false
mathjax: false
author: Siddharth Maredu
---
You can find all the list of accomplished projects that demonstrate my skills and achievements in business problems that require data driven decision making through the help of statistically backed results. Navigate to my portfolio on github to know more details of any specific project!!
---

---
## [Analyses of High Bookings on Airbnb panel dataset](#airbnb-analysis)
## [Bank Customer Subscription Prediction](#bank-customer-prediction)
## [Visualization of Products Performance using Tableau](#tableau-visualization)
---
<h2 id="airbnb-analysis">Analyses of High Bookings on Airbnb panel dataset</h2>

- **Role:** Critical member in analyzing Airbnb's high bookings in Los Angeles.
- **Methods Used:** Ensemble methods, causality analysis, data cleaning, feature engineering.
- **Results:** Found pricing strategies and property types that yield high returns.
- **Tools:** Gradient Boosted Decision Trees, EDA (Exploratory Data Analysis).

![Data Analysis Image Stock](https://github.com/siddharthmaredu/siddharthmaredu.github.io/raw/master/assets/img/technology-7111798_1280.jpg){: .mx-auto.d-block :}

Here's a breakdown of the methods and findings:

1. **Pricing Strategies:** Developed pricing recommendations that resulted in higher bookings.
2. **Property Types:** Identified the most successful property types in the Airbnb market.

---

![Airbnb Insights Image](https://github.com/siddharthmaredu/siddharthmaredu.github.io/raw/master/assets/img/airbnb insights image.png){: .mx-auto.d-block :}

**Kaggle Competition!**  
- Participated in Kaggle Competition against other teams with different markets to see which team landed the most AUC score compared against the actual high booking data.  
- Ranked in 4th position (Team Triumph) in a team of 8 members with an AUC of 0.82897 demonstrating our ability to predict high bookings with a significant accuracy.

![Kaggle Competition Image](https://github.com/siddharthmaredu/siddharthmaredu.github.io/raw/master/assets/img/kaggle competition .png){: .mx-auto.d-block :}

---

<h2 id="bank-customer-prediction">Bank Customer Subscription Prediction</h2>

- Developed predictive models using Logistic Regression, KNN, Decision Trees, Gradient Boosting, and SVM to forecast customer subscription behavior with up to 91% accuracy.
- Cleaned and processed large datasets (4,0000+ records), including handling missing values, factorizing categorical data, and performing feature selection using Lasso Regression.
- Fine-tuned machine learning models through cross-validation, reducing error rates and increasing accuracy for complex, imbalanced datasets.
- Applied advanced R techniques, including data manipulation, visualization, and statistical modeling, with libraries such as `caret`, `ggplot2`, `glmnet`, and `e1071`.

![Classification Stock Image](https://github.com/siddharthmaredu/siddharthmaredu.github.io/raw/master/assets/img/text-classification-stock.png){: .mx-auto.d-block :}

---
<h2 id="tableau-visualization">Visualization of Products Performance using Tableau</h2>

- Produced visualizations that demonstrate product analyses and its review trends.
- <a href="https://public.tableau.com/app/profile/siddharth.maredu/viz/SiddharthExamStory/Story1?publish=yes" target="_blank">Do checkout here</a> for an Interactive dashboard that provides clear insights into product performance, consumer feedback trends and actionable insights for consumer decision making.

---


Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

## Local URLs in project sites {#local-urls}

When hosting a *project site* on GitHub Pages (for example, `https://USERNAME.github.io/MyProject`), URLs that begin with `/` and refer to local files may not work correctly due to how the root URL (`/`) is interpreted by GitHub Pages. You can read more about it [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). To demonstrate the issue, the following local image will be broken **if your site is a project site:**

![Crepe](/assets/img/crepe.jpg)

If the above image is broken, then you'll need to follow the instructions [in the FAQ](https://beautifuljekyll.com/faq/#links-in-project-page). Here is proof that it can be fixed:

![Crepe]({{ '/assets/img/crepe.jpg' | relative_url }})
