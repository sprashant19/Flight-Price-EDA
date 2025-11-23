📘 Flight Price Prediction – Exploratory Data Analysis (EDA)

This project focuses on understanding the key factors that influence flight ticket prices using Exploratory Data Analysis (EDA) in Python. The dataset contains various flight-related attributes such as airline, class, duration, number of stops, and more.
The goal is to clean, preprocess, and explore these features to prepare the dataset for further modeling.

✈️ Dataset Features

Below are the features included in the cleaned dataset:

Airline: Name of the airline (6 categories)

Flight: Flight code (categorical)

Source City: Starting city (6 unique cities)

Departure Time: Time-category bins created from departure timestamps

Stops: Number of stops (3 categories)

Arrival Time: Time-category bins created from arrival timestamps

Destination City: Landing city (6 unique cities)

Class: Seat class — Business or Economy

Duration: Total travel time in hours (continuous)

Days Left: Days left for travel (derived: journey date − booking date)

Price: Target variable, ticket price

🛠️ Steps I performed during EDA:

 1️⃣ Imported all required Python libraries

 2️⃣ Loaded the cleaned dataset

 3️⃣ Explored the structure using df.info() and summary statistics using df.describe()

 4️⃣ Extracted Day, Month, and Year from the Journey Date

 5️⃣ Performed similar feature extraction for Departure Time, Arrival Time, and Duration

 6️⃣ Converted engineered columns into appropriate numeric types

 7️⃣ Applied One-Hot Encoding / Label Encoding to categorical features like Airline, Source City, and Destination City

 8️⃣ Prepared the data for future modeling and visualization
