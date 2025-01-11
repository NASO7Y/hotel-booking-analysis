
# Hotel Booking Analysis

This project involves analyzing hotel booking data to extract meaningful insights and predict booking cancellations. The dataset includes information on bookings for city and resort hotels, such as booking dates, length of stay, number of guests, and more.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis and Results](#analysis-and-results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The objective of this project is to perform exploratory data analysis (EDA) on hotel booking data to uncover trends and patterns. Additionally, we aim to build a predictive model to determine the likelihood of booking cancellations. This analysis can help hotel management in decision-making processes, such as optimizing booking strategies and improving customer satisfaction.

## Dataset

The dataset used in this project is `hotel_bookings.csv`, which contains the following features:

- `hotel`: Type of hotel (City Hotel or Resort Hotel)
- `is_canceled`: Booking cancellation status (1 if canceled, 0 otherwise)
- `lead_time`: Number of days between booking and arrival
- `arrival_date_year`: Year of arrival date
- `arrival_date_month`: Month of arrival date
- `arrival_date_week_number`: Week number of arrival date
- `arrival_date_day_of_month`: Day of arrival date
- `stays_in_weekend_nights`: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay
- `stays_in_week_nights`: Number of week nights (Monday to Friday) the guest stayed or booked to stay
- `adults`: Number of adults
- `children`: Number of children
- `babies`: Number of babies
- `meal`: Type of meal booked
- `country`: Country of origin
- `market_segment`: Market segment designation
- `distribution_channel`: Booking distribution channel
- `is_repeated_guest`: Whether the guest is a repeated guest (1 if repeated, 0 otherwise)
- `previous_cancellations`: Number of previous bookings that were canceled by the customer
- `previous_bookings_not_canceled`: Number of previous bookings not canceled by the customer
- `reserved_room_type`: Code of room type reserved
- `assigned_room_type`: Code of room type assigned
- `booking_changes`: Number of changes made to the booking
- `deposit_type`: Type of deposit made
- `agent`: ID of the travel agency that made the booking
- `company`: ID of the company/entity that made the booking
- `days_in_waiting_list`: Number of days the booking was in the waiting list
- `customer_type`: Type of customer
- `adr`: Average Daily Rate
- `required_car_parking_spaces`: Number of car parking spaces required by the customer
- `total_of_special_requests`: Number of special requests made by the customer
- `reservation_status`: Reservation status (Canceled, Check-Out, or No-Show)
- `reservation_status_date`: Date when the reservation status was last updated

## Installation

To run the analysis, ensure you have the following packages installed:

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/NASO7Y/hotel-booking-analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd hotel-booking-analysis
   ```

3. Open the Jupyter Notebook `project.ipynb` to explore the data analysis and model building steps.

## Analysis and Results

In this project, we performed the following steps:

1. **Data Preprocessing**: Handled missing values, encoded categorical variables, and scaled numerical features.

2. **Exploratory Data Analysis (EDA)**: Visualized data distributions and relationships to uncover insights such as booking trends, cancellation rates, and customer demographics.

3. **Feature Selection**: Identified important features influencing booking cancellations using statistical methods.

4. **Model Building**: Developed a predictive model using Logistic Regression to predict the likelihood of booking cancellations.

5. **Model Evaluation**: Assessed the model's performance using metrics like accuracy and classification report.

Key findings from the analysis include:

- City hotels have a higher cancellation rate compared to resort hotels.
- Longer lead times are associated with higher cancellation probabilities.
- Repeat guests are less likely to cancel their bookings.

For detailed analysis and visualizations, refer to the `project.ipynb` notebook.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
