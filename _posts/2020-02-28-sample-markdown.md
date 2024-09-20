---
layout: post
title: Portfolio
subtitle: Statistical Analyses Projects
tags: [business analytics, portfolio]
comments: false
mathjax: false
author: Siddharth Maredu
---

## [Analyses of High Bookings on Airbnb panel dataset](#airbnb-analysis)
## [Bank Customer Subscription Prediction](#bank-customer-prediction)

---
<div class="content-wrapper">
  <img src="https://github.com/siddharthmaredu/siddharthmaredu.github.io/raw/master/assets/img/technology-7111798_1280.jpg" alt="Data Analysis Image Stock">
  <div class="text">
    <h2 id="airbnb-analysis">Analyses of High Bookings on Airbnb panel dataset</h2>
    <ul>
      <li><strong>Role:</strong> Critical member in analyzing Airbnb's high bookings in Los Angeles.</li>
      <li><strong>Methods Used:</strong> Ensemble methods, causality analysis, data cleaning, feature engineering.</li>
      <li><strong>Results:</strong> Found pricing strategies and property types that yield high returns.</li>
      <li><strong>Tools:</strong> Gradient Boosted Decision Trees, EDA (Exploratory Data Analysis).</li>
    </ul>
    <p>Here's a breakdown of the methods and findings:</p>
    <ol>
      <li><strong>Pricing Strategies:</strong> Developed pricing recommendations that resulted in higher bookings.</li>
      <li><strong>Property Types:</strong> Identified the most successful property types in the Airbnb market.</li>
    </ol>
  </div>
</div>

<hr>

<div class="content-wrapper">
  <img src="https://github.com/siddharthmaredu/siddharthmaredu.github.io/raw/master/assets/img/airbnb insights image.png" alt="Airbnb Insights Image">
  <div class="text">
    <h3><strong>Kaggle Competition!</strong></h3>
    <p>Participated in Kaggle Competition against other teams with different markets to see which team landed the most AUC score compared against the actual high booking data.</p>
    <p>Ranked in 4th position (Team Triumph) in a team of 8 members with an AUC of 0.82897 demonstrating our ability to predict high bookings with a significant accuracy.</p>
  </div>
</div>

<hr>

<div class="content-wrapper">
  <img src="https://github.com/siddharthmaredu/siddharthmaredu.github.io/raw/master/assets/img/kaggle competition .png" alt="Kaggle Competition Image">
  <div class="text">
    <h3>Kaggle Competition</h3>
    <p>Participated in Kaggle Competition against other teams with different markets to see which team landed the most AUC score compared against the actual high booking data. Ranked in 4th position with an AUC of 0.82897.</p>
  </div>
</div>

---

<h2 id="bank-customer-prediction">Bank Customer Subscription Prediction</h2>

- Developed predictive models using Logistic Regression, KNN, Decision Trees, Gradient Boosting, and SVM to forecast customer subscription behavior with up to 91% accuracy.
- Cleaned and processed large datasets (4,0000+ records), including handling missing values, factorizing categorical data, and performing feature selection using Lasso Regression.
- Fine-tuned machine learning models through cross-validation, reducing error rates and increasing accuracy for complex, imbalanced datasets.
- Applied advanced R techniques, including data manipulation, visualization, and statistical modeling, with libraries such as `caret`, `ggplot2`, `glmnet`, and `e1071`.
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
