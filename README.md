# Play-store-app-analytics

##  Problem Statement

Have you ever thought about building your own iOS or Android app? If so, you've probably wondered how the app stores work and what makes an app successful.

In this project,Ireplicate some of the analytics provided by industry tools like **App Annie** or **Sensor Tower** to answer key business questions for developers and marketers. With thousands of apps published every year, it's important to understand:

- How competitive different app categories are (e.g., Games, Lifestyle, Weather)
- Which categories offer compelling opportunities based on their popularity
- The trade-offs between launching a **free** vs. **paid** app
- How much you can reasonably charge for a paid app
- Which categories have the **highest revenue potential**
- Whether an average paid app can recover its **development cost** (~$30,000)

Understanding these insights can help developers make smarter choices in product development and marketing strategy.

---

##  Solution

Using a dataset of thousands of Android apps from the **Google Play Store**,Iperformed exploratory data analysis to uncover:

- Median downloads of **free vs. paid apps**
- Median **price per category** for paid apps
- Revenue estimations per category
- Which categories are more likely to contain **high-revenue outliers**
- Categories where customers are more **willing to pay**

The dataset included features such as app category, price, number of downloads, and app type (free or paid), which enabled us to calculate key metrics and generate visualizations.

---

##  Results

### Free vs. Paid Apps

- The **median number of downloads** for free apps is **500,000**, compared to just **5,000** for paid apps.
- This shows a massive drop-off in user adoption when charging for an app.

### Revenue Insights

- The **median revenue** of a paid **Photography** app is ~$20,000 — **not enough to recoup** typical development costs.
- Only a **few categories** (e.g., Medical, Tools, Game, Family) have outliers with significantly high estimated revenue.
- This suggests that in most cases, apps may require **alternative revenue streams** such as in-app purchases or ads.

### App Pricing by Category

- The **overall median price** for a paid app is **$2.99**.
- Categories with higher-than-average **median prices**:
  - **Dating**: $6.99
  - **Medical**: $5.49
  - **Business**: $4.99
- **Personalisation** apps are among the cheapest, with a median price of just **$1.49**.
- Customers in certain categories appear more **willing to pay premium prices**.

---

##  Conclusion

This analysis reveals important trade-offs in Android app development and pricing strategies. While free apps dominate in terms of user acquisition, some paid app categories can still command high prices and revenue — particularly if they hit the right niche or offer unique value.

Developers should carefully evaluate their **category**, **monetization strategy**, and **pricing model** to increase the chances of a successful app launch.

