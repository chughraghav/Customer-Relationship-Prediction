# Customer Relationship Prediction
A Machine Learning Case Study (KDD Cup 2009)

## Business Problem
The KDD Cup 2009 challenge was to predict, from customer data provided by the
French Telecom company Orange, the urge of customers to switch providers (churn), buy
new products or services (appetency), or buy upgrades or add-ons (up-selling).

Definitions (from KDD Cup webpage):

● Churn : Churn rate is also sometimes called attrition rate. It is one of two primary
factors that determine the steady-state level of customers a business will support.
In its broadest sense, churn rate is a measure of the number of individuals or items
moving into or out of a collection over a specific period of time. The term is used
in many contexts, but is most widely applied in business with respect to a
contractual customer base. For instance, it is an important factor for any business
with a subscriber-based service model, including mobile telephone networks and
pay TV operators. The term is also used to refer to participant turnover in
peer-to-peer networks.

● Appetency: In our context, the appetency is the propensity to buy a service or a
product.

● Up-selling: Up-selling is a sales technique whereby a salesman attempts to have
the customer purchase more expensive items, upgrades, or other add-ons in an
attempt to make a more profitable sale. Up-selling usually involves marketing
more profitable services or products, but up-selling can also be simply exposing
the customer to other options he or she may not have considered previously.
Up-selling can imply selling something additional, or selling something that is
more profitable or otherwise preferable for the seller instead of the original sale.

## ML formulation of the business problem

It is a classification based problem containing two classes +1 and -1 for each of the tasks
i.e churn, appetency and up-selling.

## Performance Metric

The performances are evaluated according to the arithmetic mean of the AUC for the
three tasks (churn, appetency. and up-selling). This is what we call "Score".

Goal: to get the best possible Score.


