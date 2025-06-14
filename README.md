# Hotels_Problem_Analysis
Both City Hotel and Resort Hotel have faced rising cancellations, resulting in lost revenue and unused rooms. Reducing cancellations is now a top priority to boost revenue. This report examines booking cancellations and indirect factors impacting annual performance.
# Dataset
This dataset contains 119390 observations for a City Hotel and a Resort Hotel. Each observation represents a hotel booking between the 1st of July 2015 and 31st of August 2017, including booking that effectively arrived and booking that were canceled.

Columns:

hotel: One of the hotels is a resort hotel and the other is a city hotel.
is_canceled lead_time: Value indicating if the booking was canceled (1) or not (0).
arrival_date_year: Year of arrival date.
arrival_date_month: Month of arrival date with 12 categories: “January” to “December”.
arrival_date_week_number: Week number of the arrival date.
arrival_date_day_of_month: Day of the month of the arrival date.
stays_in_weekend_nights: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel.
stays_in_week_nights: Number of week nights (Monday to Friday) the guest stayed.
adults: Number of adults
children: Number of Childern
babies: Number of Babies
meal: BB – Bed & Breakfast
country: Country of origin.
market_segment: Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”
distribution_channel: Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”
is_repeated_guest: Value indicating if the booking name was from a repeated guest (1) or not (0)
previous_cancellations: Number of previous bookings that were cancelled by the customer prior to the current booking
previous_bookings_not_canceled: Number of previous bookings not cancelled by the customer prior to the current booking
reserved_room_type: Code of room type reserved. Code is presented instead of designation for anonymity reasons.
assigned_room_type: Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due to hotel operation reasons (e.g. overbooking) or by customer request. Code is presented instead of designation for anonymity reasons
booking_changes: Number of changes/amendments made to the booking.
deposit_type: No Deposit – no deposit was made; Non Refund – a deposit was made in the value of the total stay cost; Refundable – a deposit was made with a value under the total cost of stay.
agent: ID of the travel agency that made the booking
company: ID of the company/entity that made the booking or responsible for paying the booking. ID is presented instead of designation for anonymity reasons
days_in_waiting_list: Number of days the booking was in the waiting list before it was confirmed to the customer
customer_type: Group – when the booking is associated to a group; Transient – when the booking is not part of a group or contract, and is not associated to other transient booking; Transient-party – when the booking is transient, but is associated to at least other transient booking
adr: Average Daily Rate (Calculated by dividing the sum of all lodging transactions by the total number of staying nights)
required_car_parking_spaces: Number of car parking spaces required by the customer
total_of_special_requests: Number of special requests made by the customer (e.g. twin bed or high floor)
reservation_status: Check-Out – customer has checked in but already departed; No-Show – customer did not check-in and did inform the hotel of the reason why
reservation_status_date: Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the booking canceled or when did the customer checked-out of the hotel
name: Name of the Guest (Not Real)
email: Email (Not Real)
phone-number: Phone number (not real)
