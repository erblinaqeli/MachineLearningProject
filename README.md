# Costumer Retain Rate
This study aims to predict customer retention rates in the hotel industry using machine learning techniques. The dataset used for this research is the Hotel Booking Demand dataset from Kaggle, which contains information on hotel bookings, customer demographics, and booking details for two hotels. The dataset will be preprocessed, and exploratory data analysis will be performed to gain insights into the data. Feature engineering techniques will be applied to create new features, and the dataset will be split into training and testing sets. Various machine learning algorithms such as logistic regression, decision trees, random forests, and gradient boosting will be applied to the dataset, and their performances will be compared. The results of the study will provide insights into the factors that influence customer retention rates in the hotel industry and provide guidance for hotels to improve their retention rates.
 
## Dataset and Features

Link: https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand

1. hotel: Hotel (H1 = Resort Hotel or H2 = City Hotel).  
2. is_canceled: Value indicating if the booking was canceled (1) or not (0).  
3. lead_time: Number of days that elapsed between the entering date of the booking into the PMS and the arrival date.  
4. arrival_date_year: Year of arrival date.      
5. arrival_date_month: Month of arrival date.  
6. arrival_date_week_number: Week number of year for arrival date.  
7. arrival_date_day_of_month: Day of arrival date.  
8. stays_in_weekend_nights: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel.  
9. stays_in_week_nights: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel.  
10. adults: Number of adults.  
11. children: Number of children.  
12. babies: Number of babies.  
13. meal: Type of meal booked.   
14. country: Country of origin.  
15. market_segment: Market segment designation.  
16. distribution_channel: Booking distribution channel.  
17. is_repeated_guest: Value indicating if the booking name was from a repeated guest (1) or not (0).  
18. previous_cancellations: Number of previous bookings that were cancelled by the customer prior to the current booking.  
19. previous_bookings_not_canceled: Number of previous bookings not cancelled by the customer prior to the current booking.  
20. reserved_room_type: Code of room type reserved.  
21. assigned_room_type: Code for the type of room assigned to the booking.  
22. booking_changes: Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation.  
23. deposit_type: Indication on if the customer made a deposit to guarantee the booking.   
24. agent: ID of the travel agency that made the booking.  
25. company: ID of the company/entity that made the booking or responsible for paying the booking.  
26. days_in_waiting_list: Number of days the booking was in the waiting list before it was confirmed to the customer.  
27. customer_type: Type of booking, assuming one of four categories: Contract - when the booking has an allotment or other type of contract associated to it; Group – when the booking is associated to a group; Transient – when the booking is not part of a group or contract, and is not associated to other transient booking; Transient-party – when the booking is transient, but is associated to at least other transient booking.  
28. adr: Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights.  
29. required_car_parking_spaces: Number of car parking spaces required by the customer.  
30. total_of_special_requests: Number of special requests made by the customer (e.g. twin bed or high floor).  
31. reservation_status: Reservation last status, assuming one of three categories: Canceled – booking was canceled by the customer; Check-Out – customer has checked in but already departed; No-Show – customer did not check-in and did inform the hotel of the reason why.  
32. reservation_status_date:Date at which the last status was set.   

## Machine Learning Algorithms

 Various machine learning algorithms  will be applied to the dataset, and their performances will be compared such as:    
 
    1. Logistic regression  
    2. Decision trees  
    3. Random forests  
    4. KNN
    5.Extra Trees Classifier
    
## 

## Results

Model Performance: The table shows the performance of different machine learning models on the given test sizes. The models include Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree, Random Forest, and Extra Trees.
Accuracy: The results indicate the accuracy of each model on the respective test sizes. For example, Logistic Regression achieved accuracies ranging from 0.807608 to 0.811006, KNN achieved accuracies ranging from 0.880950 to 0.894975, and so on.

Comparative Performance: Comparing the models, it appears that Decision Tree, Random Forest, and Extra Trees consistently perform well across different test sizes, with accuracy scores ranging from 0.931147 to 0.956002.
Logistic Regression: While Logistic Regression also demonstrates good performance, it tends to have slightly lower accuracy scores compared to the tree-based models, ranging from 0.807608 to 0.811006.
KNN: K-Nearest Neighbors also performs well, with accuracies ranging from 0.880950 to 0.894975, but it generally falls slightly behind the tree-based models.
Impact of Test Size: It is worth noting that as the test size increases (from 0.2 to 0.5), the accuracy of all models tends to decrease. This could indicate that the models might be overfitting to the training data or that the test data becomes more challenging.

In conclusion, based on the provided results,Random Forest, Decision Tree, and Extra Trees consistently demonstrate high accuracy across different test sizes, outperforming Logistic Regression and KNN.

![Capture321](https://github.com/erblinaqeli/MachineLearningProject/assets/106601487/9cdb9fd0-1af8-4b4a-82ed-700042c00504)


  | Test Size | Logistic Regression | KNN      | Decision Tree | Random Forest | Extra Trees |
|-----------|---------------------|----------|---------------|---------------|-------------|
| 0.2       | 0.807608            | 0.894975 | 0.952143      | 0.956002      | 0.952647    |
| 0.3       | 0.809803            | 0.892235 | 0.950983      | 0.954981      | 0.951067    |
| 0.4       | 0.811006            | 0.888013 | 0.944636      | 0.952751      | 0.950843    |
| 0.5       | 0.809227            | 0.880950 | 0.931147      | 0.947437      | 0.944636    |

















