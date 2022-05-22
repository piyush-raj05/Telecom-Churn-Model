<h1> Telecom-Churn-Model </h1>
Analyze customer data quality of the leading telecommunications firm, create predictable models to identify customers at high risk of disruption and identify key indicators.
<h2> Gist of the Business problem </h2>
In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry earns between 15-25% per annum. Considering the fact that it costs 5-10 times more to get a new customer than an existing one, customer retention is now more important than customer acquisition.
For many operating companies, keeping customers high profit is the first goal of the business.

In order to reduce customer congestion, telecommunications companies must predict which customers are most at risk of intrusion.
<h3> In this project, you will analyze the customer data of a leading communications firm, create predictable models to identify customers at high risk of extinction and identify key churn indicators. </h3>
<h2> Definitions of Churn </h2>
There are various ways to define a churn, such as: 1. Churn-based churn 2. Consumption churn

<b> In this project, you will use a usage-based definition to define a churn. </b>
<h3> Consumer-based churn: </h3> 
<i> Active customers, incoming or outgoing - depending on calls, internet etc. at some point. A possible mistake with this definition is that if a customer stops using the services for a while, it may be too late to take any remedial action. For example, if you define a churn based on a 'two-month use' period, the churn prediction may not work as by that time the customer will have switched to another operator.</i>
<h2> Purpose of Business </h2>
The goal of the business is to predict the fluctuations of the previous month (i.e. the ninth) using data (features) from the first three months. In order to do this job well, understanding the normal behavior of the customer during the interview will help.
<br>
<img src="/model.png" alt="Alt text" title="Optional title">

<br>________________________________________________________________________________________________________________________________________________________<br>
Understanding Customer Conduct During Churn Customers usually do not decide to switch competitors immediately, but rather over time (this applies especially to high value customers). In churn prediction, we assume that there are three phases of the customer life cycle:
<br>________________________________________________________________________________________________________________________________________________________<br>
<b>‘Good’ Category:</b> At this stage, the customer is happy with the service and behaves as usual.
<br>________________________________________________________________________________________________________________________________________________________<br>
<b>‘Action’ category:</b> Customer information starts to hurt at this stage, e.g. you get a compelling gift from a competitor, you incur unnecessary costs, you are not happy with the quality of service etc. At this stage, the customer usually exhibits a different behavior than the 'good' months. Also, it is important to identify the most vulnerable customers at this stage, as other remedial measures may be taken at this point (such as comparisons provided by competitors / to improve service quality, etc.)
<br>________________________________________________________________________________________________________________________________________________________<br>
<b>'Churn' category:</b> Currently, the customer is said to have changed. Defines a churn based on this category. Also, it is important to note that during the forecast period (i.e. months of action), this data is not available for you to predict. Therefore, after marking a churn as 1/0 based on this section, you discard all data associated with this category.
<br>________________________________________________________________________________________________________________________________________________________<br>
In this case, as you work through a four-month window, the first two months 'good' phase, the third month 'action' phase, and the fourth month 'maturity' phase.
