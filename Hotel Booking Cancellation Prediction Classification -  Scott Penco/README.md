# Hotel Booking Cancellation Prediction

A view of hotel reservations dataset which includes aspects related to bookings, guest profiles, and stay details. Compelting analysis helped gain insights into booking patterns, customer behavior, and factors influencing cancellations. 
This involved two key machine learning models: logistic regression and k-nearest neighbors (KNN). These models allow us to predict whether a guest is likely to cancel their reservation, enabling hotels to optimize resource allocation and enhance revenue management strategies. 



| Column Name                        | Description                                                                                           |
|------------------------------------|-------------------------------------------------------------------------------------------------------|
| Booking_ID                         | Unique identifier of each booking                                                                     |
| no_of_adults                       | Number of adults                                                                                      |
| no_of_children                     | Number of children                                                                                    |
| no_of_weekend_nights               | Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel       |
| no_of_week_nights                  | Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel              |
| type_of_meal_plan                  | Type of meal plan booked by the customer:<br>Not Selected – No meal plan selected<br>Meal Plan 1 – Breakfast<br>Meal Plan 2 – Half board (breakfast and one other meal)<br>Meal Plan 3 – Full board (breakfast, lunch, and dinner) |
| required_car_parking_space         | Does the customer require a car parking space? (0 - No, 1 - Yes)                                       |
| room_type_reserved                 | Type of room reserved by the customer (ciphered/encoded by INN Hotels)                                  |
| lead_time                          | Number of days between the date of booking and the arrival date                                        |
| arrival_year                       | Year of arrival date                                                                                  |
| arrival_month                      | Month of arrival date                                                                                 |
| arrival_date                       | Date of the month                                                                                     |
| market_segment_type                | Market segment designation                                                                            |
| repeated_guest                     | Is the customer a repeated guest? (0 - No, 1 - Yes)                                                    |
| no_of_previous_cancellations       | Number of previous bookings canceled by the customer prior to the current booking                       |
| no_of_previous_bookings_not_canceled | Number of previous bookings not canceled by the customer prior to the current booking                   |
| avg_price_per_room                 | Average price per day of the reservation; prices of the rooms are dynamic (in euros)                    |
| no_of_special_requests             | Total number of special requests made by the customer (e.g., high floor, view from the room, etc.)      |
| booking_status                     | Flag indicating if the booking was canceled or not                                                      |
