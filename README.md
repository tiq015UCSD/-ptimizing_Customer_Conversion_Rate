# Optimizing Customer Conversion Rate

We have data about users who hit an E-commerce site. We know some of their characteristics, such as their country, marketing channel, age, whether they are repeat users, and the number of pages visited during that session. We also know whether they converted or not.

The goal is to come up with recommendations for the product and the marketing teams to improve conversion rate.

## The database
- country : user country based on the IP address

- age : user age. Self-reported at sign-up step

- new_user : whether the user created the account during this session or had already an account and simply came back to the site

- source : marketing channel source
 
- total_pages_visited: number of total pages visited during the session. This can be seen as a proxy for time spent on site and engagement

- converted: this is our label. 1 means they converted within the session, 0 means they left without buying anything. The company goal is to increase conversion rate: # conversions / total sessions

## Questions to answer: 

1. what is the user profile?

2. what is the association between conversion rate and the user profile?

3. what are some key indicators for a high/low conversion rate?

4. what would a group of users with a high conversion rate look like?

5. If we wanna run a marketing campaign, what do think could be the target audience?

6. How do you predict the conversion rate? What model do you wanna use? Implement it

7. After completing your model, think about what would be the next after having the prediction? Eg. how to improve conversion rate based on the prediction?

