# Jmeter_Project_PetStore
This JMeter project simulates and tests the performance of a typical e-commerce  website  workflow. The test plan is divided into four main scenarios, each executed under an Ultimate Thread Group to allow fine-grained control over load testing parameters.


📌 Scenarios Included: Scenario 1 – Search

Thread Group: Senario 1 - Search jp@gc - Ultimate Thread Group

Steps:

01_Step_1_Open_Url – Open the main site URL

01_Step_2_Search – Perform a product search

👁️ Scenario 2 – View Details

Thread Group: Senario 2 - View Details jp@gc - Ultimate Thread Group

Steps:

02_Step_1_Open_Url – Open site

02_Step_2_Click_On_Category – Navigate to a product category

02_Step_3_Click_On_ProductId – Click on a product

02_Step_4_Click_On_ItemId – View item detail page

🛒 Scenario 3 – Add to Cart

Thread Group: Senario 3 - Add to Cart jp@gc - Ultimate Thread Group

Steps:

03_Step_1_Open_Url – Open site

03_Step_2_Click_On_Sign-In – Click sign-in button

03_Step_3_Key-In_UserName_Password – Enter username and password

03_Step_4_Click_On_Category – Select a category

03_Step_5_Click_On_ProductId – Choose a product

03_Step_6_Click_On_Add_To_Cart – Add item to cart

03_Step_7_Click_On_Sign_Out – Log out

💳 Scenario 4 – Checkout

Thread Group: Senario 4 - Checkout jp@gc - Ultimate Thread Group

Steps:

04_Step_1_Open_Url – Open site

04_Step_2_Click_On_Sign_In – Sign in

04_Step_3_Enter_UserName_Password – Submit login details

04_Step_4_Click_On_Category – Go to product category

04_Step_5_Click_On_Product_ID – Select product

04_Step_6_Click_On_Add_To_Cart – Add to cart

04_Step_7_Click_on_Proceed_to_checkout – Proceed to checkout

04_Step_8_Key_in_payment_details_and_click_continue – Input payment and continue

04_Step_9_Click_On_Confirm – Confirm order

04_Step_10_Click_On_Sign_Out – Logout

📈 Listeners Used
View Results Tree

jp@gc - Active Threads Over Time

jp@gc - Bytes Throughput Over Time

jp@gc - Response Times Over Time

jp@gc - Response Latencies Over Time

These listeners measure:

Performance under concurrent users

Latency and throughput

User experience responsiveness

At Last  I have provided some Result Summary
