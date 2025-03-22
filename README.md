# 🏙️ NYC Airbnb Price Analysis (2019)

This project investigates the average price and the proportion of Airbnb listings over $150 in New York City using real-world data from 2019. It was completed as part of a statistics coursework assignment focused on sampling and inference methods.

Using data from [Inside Airbnb](http://insideairbnb.com/) (via Kaggle), we apply both **Simple Random Sampling (SRS)** and **Stratified Sampling** to estimate:

- 📊 The average Airbnb listing price in NYC
- 💸 The proportion of listings exceeding $150 per night

By stratifying the sample by room type (entire home/apt, private room, shared room), we achieve more precise estimates. Confidence intervals and standard errors were calculated for both methods, with stratified sampling yielding significantly better precision.

---

## 🔍 Key Results

| Estimate                                | SRS                   | Stratified Sampling     |
|----------------------------------------|------------------------|-------------------------|
| Average Price                          | $165.44 (SE: 11.91)    | **$149.83 (SE: 4.84)**  |
| Proportion of Listings > $150          | 0.31 (SE: 0.014)       | **0.31 (SE: 0.012)**     |
| 95% CI for Avg Price                   | (142.35, 188.53)       | **(140.44, 159.22)**     |
| 95% CI for Proportion > $150           | (0.29, 0.34)           | **(0.28, 0.33)**         |

---

## 📌 Conclusion

Stratified sampling provided more accurate and stable estimates due to better representation of room types. The final recommendation is that tourists can expect a typical Airbnb listing to cost around **$149.83**, and **only about 31% of listings exceed $150**, making most listings affordable for domestic travelers.

---

## 📚 Tools Used

- R
- Statistical inference techniques (SRS, Stratified Sampling, CI estimation)

---

## 📌 Academic Info

This project was completed as part of a university-level statistics course on survey sampling and estimation.
