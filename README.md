# Nook Café's Transformation: Bridging Coffee Culture and Nightlife

Erdos UX Research - Spring 2025

<b>Objective:</b>

Nook Café, a coffee shop, seeks to diversify into alcoholic beverages. It is located on the campus of a Southern University, one of the largest and most cosmopolitan cities in the United States. As of February 2025, the city is the fourth most populated city in the US, with diverse cultures and restaurants in the area. The university is the largest in the city, with a total enrollment of 47,980 students in 2024. To diversify into alcohol, Nook Café must extend its opening hours, among other strategic moves. Nook Café intends to attract patrons both on and off campus.

A unique characteristic of the city where Nook Café is located is its limited public transit system. Among the top 5 most populous metro areas, the city had the second-lowest public transit ridership rate in 2019, with only 18 rides per resident, compared to New York City, where people took almost 200 annual rides per resident. Hence, the question of how external patrons would commute to Nook Café may pose a challenge. Above all, external patrons must be motivated enough to travel past competitors to reach Nook Café for alcoholic beverages.

<h2 id="Table-of-Contents">Table of Contents</h2>

<ul>
    <li><a href="#Introduction">Introduction</a></li>
    <ul>
            <li><a href="#Hours">Business Hours</a></li>
            <li><a href="#Location">Location</a></li>
            <li><a href="#Predicting-consumers">Predicting alcohol consumers from the University of Houston</a></li>
        </ul>
    <li><a href="#Customer-Survey">Customer Survey</a>
    <li><a href="#Market-Size">Market Size Analysis</a>
        <ul>
            <li><a href="#University-of-Houston-students">Student Data Analysis</a></li>
            <li><a href="#International-Students">International Student Data Analysis</a></li>
            <li><a href="#University-of-Houston-faculty">Faculty Data Analysis</a></li>
            <li><a href="#Predicting-consumers">Predicting alcohol consumers from the University of Houston</a></li>
        </ul>
    <li><a href="#Market-Analysis">Market Analysis</a></li>
    <li><a href="#Cost">Cost of Diversification</a></li>
    <li><a href="#Revenue-Forecast">Sales & Revenue Forecast</a></li>
    <li><a href="#Conclusion">Conclusion</a></li>
    <li><a href="#Resource">Resource</a></li>
    <li><a href="#Code-Description">Code Description</a></li>
</ul>

---

<h3 id="Introduction">Introduction</h3>

Nook Café has established itself as one of the favorite spots on campus for university stakeholders to relax and have coffee. It has existed for eighteen years on campus and has recorded steady growth. However, in 2020, the café recorded a significant decline in sales and profit. The global COVID-19 pandemic and lockdown were responsible for the decline. However, many years after the pandemic and the return to normalcy, Nook Café returned to profitability. Still, sales and profit have remained stagnant, indicating that these business indices have reached their ceiling.

The business reality with Nook Café suggests that we should look beyond the 2020 COVID-19 pandemic for problems mitigating against Nook Café's business growth as the pandemic appears to no longer pose a threat. Our preliminary interview of 10 patrons sited at Nook Café suggests other problems may be responsible for the stagnation of growth. Several coffee shops are located outside the campus but within a radius of 5 miles, competing with Nook Café. In our preliminary study of competition, we noticed a common and emerging trend of hybridity, including coffee and alcohol offerings among the surrounding coffee shops. For example, Double Trouble Caffeine & Cocktails is located 2.6 miles from Nook and offers alcoholic beverages. We concluded that including alcohol in the coffee shop business has become a trend, and it is long overdue for Nook Café to diversify into the alcohol market. The exclusion of Nook from the alcohol market is a problem that contributes to stagnation in business growth.

<h4 id='Hours'>Business Hours</h4>

Nook Café closes at 5 pm on weekdays and 2 pm on weekends. We discovered that competitors stay open for extended hours; for instance, Cowboy Café, located 3.6 miles from Nook, operates daily from 8 am to 12 am. One challenge for Nook in competing is the university's restriction on alcohol sales during working hours (9 am – 5 pm). Therefore, Nook should consider selling alcohol after 5 pm and extending its operating hours. Google statistics revealed that while Nook maintains a steady number of patrons during the day, it loses them to competitors later in the day. To address this, Nook must focus on improving customer retention during the evening and nighttime hours.

<p float="center">
  <img src="/Figure/Nook_hours.PNG" width="1000" />
</p>

While it is easy for Nook to enter the alcohol market, it must make extra strategic efforts to achieve competitive differentiation and leverage brand expansion opportunities accompanying diversification into new markets. Since surrounding coffee shops are competing and existing threats, operating in the hybridity of coffee and alcohol, the challenge for Nook is to attain brand and service distinction to draw alcohol consumers and retain them for steady profitability. The apparent question for Nook is how it would stay far away from the madding crowd without losing attraction and patronage.

<h4 id='Location'>Location</h4>

Nook is located on a large campus with an enrollment of 47,980 in 2024. Besides, it is located in a city adjudged as the 4th largest city in the US. This geographical location means there are tremendous opportunities within the campus and more significant opportunities outside the campus if Nook taps into these external opportunities. Besides, Nook has achieved a strong brand image on campus. It can leverage these strengths to tap into opportunities comprising various activities on campus that attract outside vendors to sell alcohol on campus. For example, the campus welcomes over 1000 guests across all sports divisions during the game season. With Nook's opportunities and strength, it must navigate its proposed entry into the alcoholic market cautiously to tap the benefits of a new market.

---

<h3 id="Customer-Survey">Customer Survey</h3>

To investigate the preferences of Nook Café patrons, we conducted a survey asking customers for their thoughts on alcohol.

```
<form>
1. How often do you drink alcohol?
Never <hspace=5mm> - 1-2 days per week


<label>What is your age group?</label>
    <input type="radio" id="18-25" name="age" value="18-25">
    <label for="18-25">18-25</label>
    <input type="radio" id="26-35" name="age" value="26-35">
    <label for="26-35">26-35</label>
```
<label>What is your age group?</label>
    <input type="radio" id="18-25" name="age" value="18-25">
    <label for="18-25">18-25</label>
    <input type="radio" id="26-35" name="age" value="26-35">
    <label for="26-35">26-35</label>
</form>

<form>
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">
  <label for="css">CSS</label><br>
  <input type="radio" id="javascript" name="fav_language" value="JavaScript">
  <label for="javascript">JavaScript</label>
</form>

<div class="for-form">
                <p>Which option best describes your current role</p>
                <select name="role" id="dropdown" class="for-input" required>
                <option disabled selected value>Select current role</option>
                <option value="student">Student</option>
                <option value="job">Full Time Job</option>
                <option value="learner">Full Time Learner</option>
                <option value="preferNot">Prefer not to say</option>
                <option value="other">Other</option>
                </select>
            </div>
            
---

<h3 id="Market-Size">Market Size Analysis</h3>

We first began by analyzing potential customers using enrollment data from Spring 2014 to Fall 2024, obtained from [The University of Houston website](https://www.uh.edu/ir/reports/statistical-handbook/student-enrollment/). Different countries impose different drinking cultures; therefore, we consider both U.S. student data and international student data. Additionally, each term (spring, summer, and fall) exhibits different trends, making it necessary to analyze data according to each term.

<h4 id="University-of-Houston-students">Student data analysis</h4>

We considered the following attributes from [students.csv](https://github.com/kpnguyen21/erdos-coffee-bar/blob/main/Data/students.csv) for our analyses: 

`Semester`: Spring, Summer, or Fall, followed by a number indicating the year between 2014 and 2024.

`Total_enrollment`: the total number of students enrolled, including both U.S. and international students. 

`Male`: the number of male students enrolled during that semester.

`Female`: the number of female students enrolled during that semester.

`White`: the number of White students enrolled during that semester.

`Hispanic`: the number of Hispanic students enrolled during that semester.

`Asian_American`: the number of Asian American students enrolled during that semester.

`African_American`: the number of African American students enrolled during that semester.

`Undegrad_Male`: the number of male students enrolled in the undergraduate program during that semester.

`Undergrad_Female`: the number of female students enrolled in the undergraduate program during that semester.

Prior to Fall 2017, male students were the majority at the University of Houston (see figure below). The solid lines were the student data and the dashed lines were the fit from `polyfit`. Since males are more likely to drink than females, this could indicate that our market size may decrease.

<p float="left">
  <img src="/Figure/Spring_Gender_prediction.jpg" width="400" />
  <img src="/Figure/Fall_Gender_prediction.jpg" width="400" /> 
</p>

The population of Hispanic students spiked and surpassed the White population since Fall 2015. In 2021, Asian American students also surpassed the White population to become the second majority. According to 2022 statistics, White students were more likely to drink, so this decline could impact the Nook Café.

<p float="left">
  <img src="/Figure/Spring_Race_prediction.jpg" width="400" />
  <img src="/Figure/Fall_Race_prediction.jpg" width="400" /> 
</p>

We were more interested in the undergraduate student group than other groups, such as postbaccalaureate, Master's, or Doctoral, because undergraduate students had a larger population size with smaller variance compared to other groups. This made them a more stable and representative sample for our analysis. Additionally, focusing on undergraduate students allowed us to identify trends and patterns that are specifically relevant to the largest segment of the student body.

<p float="left">
  <img src="/Figure/Spring_Undergrad_prediction.jpg" width="400" />
  <img src="/Figure/Fall_Undergrad_prediction.jpg" width="400" /> 
</p>

We used `polyfit` of a degree 4 to fit data from 2014 and 2024. From the fit, we predicted the population of `Male`, `Female`, `White`, `Hispanic`, `African American`, `Asian American`, `Undergraduate Male`, and `Undergraduate Female` for Spring 2025-2027 and Fall 2025-2027.

<table>
  <tr>
    <th rowspan="2">Population</th>
    <th colspan="3">Spring</th>
    <th colspan="3">Fall</th>
  </tr>
  <tr>
    <th>2025</th>
      <th>2026</th>
      <th>2027</th>
    <th>2025</th>
      <th>2026</th>
      <th>2027</th>
</tr>
    <tr>
        <td>Male</td>
        <td>21,290</td>
        <td>22,243</td>
        <td>23,832</td>
        <td>23,931</td>
        <td>25,796</td>
        <td>28,749</td>
    </tr>
    <tr>
        <td>Female</td>
        <td>22,751</td>
        <td>22,838</td>
        <td>23,006</td>
        <td>26,014</td>
        <td>27,960</td>
        <td>31,196</td>
    </tr>
    <tr>
        <td>White</td>
        <td>7,660</td>
        <td>7,336</td>
        <td>7,283</td>
        <td>8,521</td>
        <td>9,141</td>
        <td>10,614</td>
    </tr>
    <tr>
        <td>African American</td>
        <td>4,990</td>
        <td>5,104</td>
        <td>5,168</td>
        <td>6,128</td>
        <td>6,836</td>
        <td>7,844</td>
    </tr>
    <tr>
        <td>Asian American</td>
        <td>8,893</td>
        <td>7,770</td>
        <td>5,890</td>
        <td>9,820</td>
        <td>9,205</td>
        <td>8,247</td>
    </tr>
    <tr>
        <td>Undergraduate Male</td>
        <td>17,092</td>
        <td>18,359</td>
        <td>20,702</td>
        <td>20,080</td>
        <td>23,058</td>
        <td>28,036</td>
    </tr>
    <tr>
        <td>Undergraduate Female</td>
        <td>18,332</td>
        <td>19,088</td>
        <td>20,408</td>
        <td>21,347</td>
        <td>23,815</td>
        <td>27,919</td>
    </tr>
</table>

<!--
| **Population**       | Spring 2025 | Spring 2026 | Spring 2027 | Fall 2025 | Fall 2026 | Fall 2027 |
| -------------------- | ----------- | ----------- | ----------- | --------- | --------- | --------- |
| Male                 | 21,290      | 22,243      | 23,832      | 23,931    | 25,796    | 28,749    |
| Female               | 22,751      | 22,838      | 23,006      | 26,014    | 27,960    | 31,196    |
| White                | 7,660       | 7,336       | 7,283       | 8,521     | 9,141     | 10,614    |
| Hispanic             | 15,157      | 16,393      | 18,566      | 17,771    | 20,548    | 25,194    |
| African American     | 4,990       | 5,104       | 5,168       | 6,128     | 6,836     | 7,844     |
| Asian American       | 8,893       | 7,770       | 5,890       | 9,820     | 9,205     | 8,247     |
| Undergraduate Male   | 17,092      | 18,359      | 20,702      | 20,080    | 23,058    | 28,036    |
| Undergraduate Female | 18,332      | 19,088      | 20,408      | 21,347    | 23,815    | 27,919    |
-->
<h4 id="International-Students">International students data</h4>

We considered the top 10 most populous countries for each semester between Spring 2014 and Fall 2024: `China`, `India`, `Vietnam`, `Nigeria`, `Saudi_Arabia`, `South_Korea`, `Iran`, `Mexico`, `Venezuela`, `Canada`, `Taiwan`, `Turkey`, `Peru`, `Pakistan`, `Nepal`, `Ukraine`, `Bangladesh`, and `Sri Lanka`. Rows containing empty cells indicate that the student population from that country did not make it to the top 10 most populous that semester. To simplify our analysis and ensure consistency, we eliminated any countries that had at least one empty entry. That yielded four countries: `China`, `India`, `Vietnam`, and `Nigeria`.


<p float="left">
  <img src="/Figure/Spring_Country_prediction.jpg" width="400" />
  <img src="/Figure/Fall_Country_prediction.jpg" width="400" /> 
</p>

We could not fit the Indian student population, so we excluded India from our prediction. We also used `polyfit` of a degree 4 to fit international student data.

<table>
  <tr>
    <th rowspan="2">Population</th>
    <th colspan="3">Spring</th>
    <th colspan="3">Fall</th>
  </tr>
  <tr>
    <th>2025</th>
      <th>2026</th>
      <th>2027</th>
    <th>2025</th>
      <th>2026</th>
      <th>2027</th>
</tr>
    <tr>
        <td>China</td>
        <td>1,028</td>
        <td>1,397</td>
        <td>1,926</td>
        <td>1,145</td>
        <td>1,346</td>
        <td>1,561</td>
    </tr>
    <tr>
        <td>Vietnam</td>
        <td>232</td>
        <td>156</td>
        <td>74</td>
        <td>284</td>
        <td>281</td>
        <td>327</td>
    </tr>
    <tr>
        <td>Nigeria</td>
        <td>207</td>
        <td>202</td>
        <td>165</td>
        <td>244</td>
        <td>261</td>
        <td>264</td>
    </tr>
</table>

<!--
| **Population** | Spring 2025 | Spring 2026 | Spring 2027 | Fall 2025 | Fall 2026 | Fall 2027 |
| -------------- | ----------- | ----------- | ----------- | --------- | --------- | --------- |
| China          | 1,028       | 1,397       | 1,926       | 1,145     | 1,346     | 1,561     |
| Vietnam        | 232         | 156         | 74          | 284       | 281       | 327       |
| Nigeria        | 207         | 202         | 165         | 244       | 261       | 264       |
-->

<h4 id="University-of-Houston-faculty">Faculty Data analysis</h4>

We considered the following attributes from [faculty.csv](https://github.com/kpnguyen21/erdos-coffee-bar/blob/main/Data/faculty.csv) for our analyses: 

`Year`: Faculty data is organized by year, not by semester.

`Total_faculty`: the total faculty for that year. 

`Male`: the number of male faculty for that year.

`Female`: the number of female faculty for that year.

`African_American`: the number of African American faculty for that year.

`Asian_American`: the number of Asian American faculty for that year.

`Hispanic`: the number of Hispanic faculty for that year.

`White`: the number of White faculty for that year.


<h4 id="Predicting-consumers">Predicting alcohol consumers from the University of Houston</h4>

We considered preferences and drinking probabilities across various races, genders, and beverage types. Given the large student population on this college campus, household income levels were deemed less significant. The following probabilities were applied, based on Gallup's 2022 article, [What Percentage of Americans Drink Alcohol?](https://news.gallup.com/poll/467507/percentage-americans-drink-alcohol.aspx).

**General Drinking Probabilities:**

According to Gallup's study, American men, irrespective of race, are more likely to consume alcohol than women. This trend reflects a broader social and cultural pattern, potentially influenced by gender roles, societal expectations, and differences in social behaviors. 

$$ P(\text{men drinking}) = 0.66 $$
$$ P(\text{women drinking}) = 0.61 $$

Furthermore, the study reveals that the youngest American age group—those aged 18 to 29—are less likely to drink alcohol compared to older age groups. This may be due to stricter enforcement of legal drinking age laws, shifting attitudes toward alcohol consumption among younger generations, or increasing awareness of alcohol's health impacts.
In contrast, older age groups tend to exhibit a higher probability of drinking, which could be attributed to greater disposable income, established social habits involving alcohol, or the role of alcohol in certain professional or social settings. These patterns highlight the interplay between age, gender, and cultural dynamics in shaping alcohol consumption behaviors in American society.

$$ P(\text{people between 18 to 29 drinking}) = 0.60$$
$$ P(\text{people between 21 to 29 drinking}) = 0.71$$
$$ P(\text{people between 30 to 49 drinking}) = 0.70$$

**Drinking Probabilities by Race & Gender:**

$$ P(\text{White drinking}) = 0.68$$
$$ P(\text{Black drinking}) = 0.50$$
$$ P(\text{Hispanic drinking}) = 0.59$$
$$ P(\text{Asian Americans drinking}) = 0.318 $$

$$ P(\text{White men drinking}) = 0.68$$
$$ P(\text{White women drinking}) = 0.68$$

$$ P(\text{Hispanic men drinking}) = 0.6$$
$$ P(\text{Hispanic women drinking}) = 0.57$$

$$ P(\text{Black men drinking}) = 0.52$$
$$ P(\text{Black women drinking}) = 0.48$$

<p float="center">
  <img src="/Figure/output.png" width="1000" />
</p>

---
<h3 id="Market-Analysis">Market Analysis</h3>

<!-- ### **Alcohol Preferences (Beer, Wine, Spirits)** -->

To better predict customer behavior, we incorporated national statistics on **alcohol preferences**:

- **Beer**: 37% of drinkers prefer beer.
- **Wine**: 29% of drinkers prefer wine.
- **Spirits**: 31% of drinkers prefer spirits.

We applied these probabilities to our estimates for alcohol consumers to determine the expected number of customers for each category.

<!-- #### **Estimated Distribution of Alcohol Consumers by Beverage Type** -->

<!--
<p float="center">
  <img src="/Figure/beer_wine_spirits_distribution.png" width="1000" />
</p>
-->
<p float="center">
  <img src="/Figure/spring_preference.jpg" width="1000" />
  <img src="/Figure/fall_preference.jpg" width="1000" />
</p>

---

<h3 id="Cost">Cost of Diversification</h3>

The diversification project for Nook Café to enter the alcohol market is estimated to cost $171,985 in the first year. The cost includes licensing and permits, renovations and equipment, inventory and supplies, staffing and training, marketing and branding, and ongoing costs. Although Nook Café is an existing business known for serving coffee to customers, the drive for diversification into alcohol will require the acquisition of a liquor license, a business permit modification to accommodate the new business line, and training and certification for six new employees to operate the bar in the evenings and nights. The cost for licensing and permits is an estimated $7,500.

Nook Café focuses on serving coffee only, and the diversification drive requires renovating existing facilities to enable an alcohol offering. The need for renovation also involves acquiring new equipment, including bar coolers and refrigerators, bar blenders or frozen drink machines, draft beer dispensers, underbar sinks, commercial glass washers, and point-of-sale software. Inventory and supplies are estimated to cost $6,740.

The newly diversified Nook Café will offer alcoholic beverages and side drinks alongside coffee drinks. The initial alcohol stock, consisting of beer, wine, liquor, and side drinks, including mixers, garnishes, and supplies, will cost $6,740. Since Nook Café offers fast-moving consumer goods (FMCG), the cost of inventory and supplies will continuously increase with higher market demand.

The new Nook Café requires additional staffing of six workers to man the café in the evenings and nights. We estimate three workers to handle a day's shift at a time. We estimate the new workers' training and annual wages at $132,290. We recommend that Nook Café pay a wage above the state's minimum of $7.25.

A Nook Café, a hybrid business serving coffee and alcoholic beverages, requires promotion. Thus, the management may need to spend $4,925 to create business awareness. The promotional effort will include signage, rebranding, advertising, and promotions. In addition to marketing and branding costs, the management needs to set aside funds for ongoing costs, which will include insurance premiums and other miscellaneous expenses estimated at $7,880. The cost breakdown explains the estimations in more detail.

<table>
  <tr>
    <th colspan="4">Estimated Cost for Diversification into Bar - First Year</th>
  </tr>
  <tr>
      <th colspan="2">Licensing and Permit</th>
</tr>
    <tr>
        <td>Liquor license</td>
        <td>3,500</td>
    </tr>
   <tr>
        <td>Business Permit Modification</td>
        <td>1,000</td>
    </tr>
    <tr>
        <td>Training & certification (6 employees)</td>
        <td>3,000</td>
    </tr>
    <tr>
        <th>Subtotal</th>
        <th>7,500</th>
    </tr>
    <tr>
      <th colspan="2">Renovations & Equipment</th>
</tr>
    <tr>
        <td>Bar Setup</td>
        <td>7,500</td>
    </tr>
   <tr>
        <td>Draft Beer System</td>
        <td>2,000</td>
    </tr>
    <tr>
        <td>Wine Storage & Refrigeration</td>
        <td>3,150</td>
    </tr>
    <tr>
        <th>Subtotal</th>
        <th>12,650</th>
    </tr>
    <tr>
      <th colspan="2">Inventory & Suppliers</th>
    </tr>
    <tr>
        <td>Initial Alcohol Stock (beer, wine & spirits)</td>
        <td>5,000</td>
    </tr>
   <tr>
        <td>Mixers, Garnishes & Supplies</td>
        <td>1,740</td>
    </tr>
    <tr>
        <th>Subtotal</th>
        <th>6,740</th>
    </tr>
    <tr>
      <th colspan="2">Staffing & Training</th>
    </tr>
    <tr>
        <td>Bartenders/ servers' salary (3 workers*84 hours/week* $10*52)</td>
        <td>131,040</td>
    </tr>
   <tr>
        <td>Supplementary Training Cost</td>
        <td>1,250</td>
    </tr>
    <tr>
        <th>Subtotal</th>
        <th>132,290</th>
    </tr>
    <tr>
      <th colspan="2">Marketing & Branding</th>
    </tr>
    <tr>
        <td>Signage & Rebranding</td>
        <td>2,755</td>
    </tr>
   <tr>
        <td>Advertising & Promotions</td>
        <td>2,170</td>
    </tr>
    <tr>
        <th>Subtotal</th>
        <th>4,925</th>
    </tr>
    <tr>
      <th colspan="2">Ongoing Cost</th>
    </tr>
    <tr>
        <td>Insurance Premium</td>
        <td>2,880</td>
    </tr>
   <tr>
        <td>Miscellaneous</td>
        <td>5,000</td>
    </tr>
    <tr>
        <th>Subtotal</th>
        <th>7,880</th>
    </tr>
    <tr>
      <th>Grand Total</th>
        <th>171,985</th>
    </tr>
</table>

---

<h3 id="Revenue-Forecast">Sales & Revenue Forecast</h3>

Alcohol sales at Nook Café will differ between weekdays and weekends. We envision peak weekend sales. We expect Nook Café to gross $383,200 and $420,420 in the first and second years, respectively, with an anticipated 10% business growth in the second year. The estimated profits are $229,320 and $252,252 for the first and second years, respectively. The sales and revenue forecasts highlight the new venture’s prospects. Observations of surrounding cafés indicate that an average of ten patrons walk in to buy alcohol in the evenings. We extrapolate this figure for Nook Café’s forecast.

<table>
  <tr>
    <th colspan="4">Sales & Revenue Forecast</th>
  </tr>
  <tr>
      <th>Weekday Sales (Monday - Thursday)</th>
    <th>Year 1</th>
      <th>Year 2(*10%)</th>
      <th>Total 2 years</th>
</tr>
    <tr>
        <td>Customers per hour</td>
        <td>10</td>
        <td>11</td>
        <td>21</td>
    </tr>
    <tr>
        <td>Customers per evening</td>
        <td>70</td>
        <td>77</td>
        <td>147</td>
    </tr>
    <tr>
        <td>Average drinks per customer</td>
        <td>1.5</td>
        <td>1.65</td>
        <td>3.15</td>
    </tr>
    <tr>
        <td>Total drink sale per evening</td>
        <td>105</td>
        <td>115.5</td>
        <td>220.5</td>
    </tr>
    <tr>
        <td>Revenue per day (Total drink sale per evening*7)</td>
        <td>735</td>
        <td>808.5</td>
        <td>1,543.5</td>
    </tr>
    <tr>
        <td>Sales per week (Revenue per day*4)</td>
        <td>2,940</td>
        <td>3,234</td>
        <td>6,174</td>
    </tr>
    <tr>
        <td>Weekdays annual revenue</td>
        <td><b>152,880</b></td>
        <td><b>168,168</b></td>
        <td><b>321,048</b></td>
    </tr>
    <th>Weekend Sales (Friday - Sunday)</th>
    <th>Year 1</th>
      <th>Year 2(*10%)</th>
      <th>Total 2 years</th>
</tr>
    <tr>
        <td>Customers per hour</td>
        <td>20</td>
        <td>22</td>
        <td>42</td>
    </tr>
    <tr>
        <td>Customers per evening</td>
        <td>140</td>
        <td>154</td>
        <td>294</td>
    </tr>
    <tr>
        <td>Average drinks per customer</td>
        <td>1.5</td>
        <td>1.65</td>
        <td>3.15</td>
    </tr>
    <tr>
        <td>Total drink sale per evening</td>
        <td>210</td>
        <td>231</td>
        <td>441</td>
    </tr>
    <tr>
        <td>Revenue per day (Total drink sale per evening*7)</td>
        <td>1,470</td>
        <td>1,617</td>
        <td>3,087</td>
    </tr>
    <tr>
        <td>Sales per week (Revenue per day*3)</td>
        <td>4,410</td>
        <td>4,851</td>
        <td>9,261</td>
    </tr>
    <tr>
        <td>Weekend annual revenue</td>
        <td><b>229,320</b></td>
        <td><b>252,252</b></td>
        <td><b>481,572</b></td>
    </tr>
    <tr>
        <th>Total</th>
        <td><b>382,200</b></td>
        <td><b>420,420</b></td>
        <td><b>802,620</b></td>
    </tr>
    <tr>
        <th>Estimated Profit</th>
        <td><b>229,320</b></td>
        <td><b>252,252</b></td>
        <td><b>481,572</b></td>
    </tr>
</table>

---
<h3 id="Conclusion">Conclusion</h3>

By focusing on value-added service experiences, Nook can differentiate itself from competitors in the hybrid Coffee Shop market. This approach involves providing exceptional customer service, personalized offerings, and unique experiences that cater to the diverse needs of customers. As a result, Nook can build a loyal customer base and attract new patrons who appreciate the added value. With consistent efforts and strategic growth, Nook is well-positioned to achieve profitability in the next three years, capitalizing on its strong reputation and customer-centric approach.

---

<h3 id="Resource">Resource</h3>

- National Institute on Alcohol Abuse and Alcoholism (NIAAA)
- Haitao Zhang, W. June Ruan, S. Patricia Chou, Tulshi D. Saha, Amy Z. Fan, Boji Huang, Aaron M. White, _Exploring Patterns of Alcohol Use and Alcohol Use Disorder Among Asian Americans with a Finer Lens_, Drug and Alcohol Dependence, Volume 257, 2024.
- [Percentage of Americans Drinking Alcohol](https://news.gallup.com/poll/467507/percentage-americans-drink-alcohol.aspx)
- [Young Adults' Alcohol Consumption Trends](https://news.gallup.com/poll/648413/alcohol-consumption-increasingly-viewed-unhealthy.aspx)

---

<h3 id="Code-Description">Code Description</h3>

[data_inputs.ipynb](https://github.com/kpnguyen21/erdos-coffee-bar/blob/main/data_inputs.ipynb): Created [students.csv](https://github.com/kpnguyen21/erdos-coffee-bar/blob/main/Data/students.csv) and [international_students/csv](https://github.com/kpnguyen21/erdos-coffee-bar/blob/main/Data/international_students.csv)

[regression.ipynb](https://github.com/kpnguyen21/erdos-coffee-bar/blob/main/regression.ipynb): Fitted 2014-2024 data and made predictions for 2025-2027. Estimated number of drinkers from the University of Houston student population and the preferences on Beer, Wine, and Spirits.
