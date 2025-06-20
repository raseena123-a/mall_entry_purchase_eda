# mall_entry_purchase_eda
This project analyzes customer entry behavior and purchase decisions in a mall using a synthetic dataset.
##📌 1. Purpose
To explore and understand how customer characteristics (age, gender), entry time, and time spent in the mall affect their purchasing behavior and spending patterns.

##❓ 2. Key Questions
What percentage of mall visitors actually make a purchase?

Does time spent in the mall influence the likelihood of purchasing?

Which age groups are more likely to make a purchase?

Does gender play a role in purchasing behavior and spending?

At what time of day do customers spend the most?

How does the amount spent vary between different types of customers?

Are there any strong correlations among age, duration, amount spent, and purchasing?

Can we identify a typical profile of a high spender?

Are there any outliers in spending or behavior?

(Optional) Can we predict purchase decisions based on customer behavior?

📊 3. Dataset Overview
Features:

PersonID: Unique customer identifier

Gender: Male/Female

Age: Customer’s age

EntryTime: Time of entering the mall

DurationMin: Time spent in the mall (minutes)

Purchased: Yes/No

AmountSpent: ₹ amount spent (0 if no purchase)

🧹 4. Data Cleaning
Checked for missing values (none found)

Converted EntryTime to datetime and extracted hour

Removed any duplicate rows (none found)

Ensured consistency in Purchased column ("Yes"/"No")

Validated AmountSpent is 0 when Purchased = No

📈 5. Data Analysis Steps
📌 Univariate Analysis
Gender distribution

Age distribution

Time spent in mall

Purchase rate

📌 Bivariate Analysis
Gender vs Purchase

Age vs Purchase

Duration vs Purchase

Entry hour vs Purchase

Amount spent by Gender and Age

📌 Correlation Matrix
Checked relationships between numeric fields (Age, DurationMin, AmountSpent, Purchased)
##🔍 Key Insights
🕓 Peak Purchase Times:
The majority of purchases occur at 11 AM and 6 PM, indicating two key shopping windows — late morning and early evening.

⏱ Time Spent Matters:
Visitors who spend more time in the mall are significantly more likely to make a purchase and spend more money.

🧑‍🤝‍🧑 Age & Spending:
The 25–40 age group makes up the highest number of purchases and tends to spend more compared to younger or older groups.

👩‍🦱👨‍🦱 Gender Influence:
While both genders shop actively, females had a slightly higher purchase rate and showed a marginally higher average spend.

💸 Amount Spent Distribution:
Most customers spend between ₹500 and ₹1500. A small group of high spenders contributes to higher spikes in revenue.

🔁 Correlations:
There is a positive correlation between DurationMin and both Purchased and AmountSpent. This suggests that people who linger longer are more valuable customers.

🎯 Customer Profile of High Spenders:
High spenders are typically aged 30–45, enter in the afternoon, and spend more than an hour in the mall.

🛒 Overall Conversion:
Roughly 60–70% of mall entrants make a purchase, showing strong customer engagement.

##🧾 Conclusion
This exploratory data analysis helped uncover patterns in customer behavior inside a mall. The findings indicate that time of entry, age group, and time spent in the mall are all significant factors influencing purchase decisions and amount spent. These insights can be leveraged to:

Optimize staff scheduling during peak hours

Target marketing campaigns to age groups most likely to buy

Offer personalized promotions to increase time spent and conversion rates
