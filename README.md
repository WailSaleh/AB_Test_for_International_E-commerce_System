# A/B Test for An Improved Recommendation System for An International E-commerce 🛒🆎

Have received an analytical task from an international online store. My predecessor failed to complete it: they launched an A/B test and then quit (to start a watermelon farm in Brazil). They left only the technical specifications and the test results.

**Technical description**

Test Name: recommender_system_test

Groups: A (control) and B (new payment funnel)

Start date: 07-12-2020

When they stop receiving new users: 21-12-2020

End date: 01-01-2021

Audience: 15% of new users from the EU region

Purpose of the test: to test changes related to the introduction of an improved recommendation system

Expected result: Within 14 days of signing up, users show better conversion on product page views (the event), add items to cart (), and shopping (). At each stage of the funnel, there will be at least a 10% 
increase.product_pageproduct_cartpurchaseproduct_page → product_cart → purchase

Expected Number of Test Participants: 6000

**ab_project_marketing_events_us.csv — the calendar of marketing events for 2020:**

*name: the name of the marketing even*

*regions: regions where the ad campaign will be held*

*start_dt: campaign start date*

*finish_dt: campaign end date*

**final_ab_new_users_upd_us.csv — all users who registered in the online store from December 7 to 21, 2020:**

*user_id*

*first_date: sign-up date*

*region*

*device: device used to sign up*

**final_ab_events_upd_us.csv — all new users' events within the period from December 7, 2020 to January 1, 2021:**

*user_id*

*event_dt: event date and time*

*event_name: event type name*

*details: additional data on the event (for instance, the order total in USD for purchase events)*

**final_ab_participants_upd_us.csv  — table containing the test participants:**

*user_id*

*ab_test: test name*

*group: the test group the user belonged to*

**Goals of the Research:**

Assess the impact of the new recommendation system on user behavior, specifically looking for a 10% increase in conversion rates at each stage of the sales funnel (product page views, product card views, and purchases) within 14 days of user signup.
