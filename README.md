# Tweets Geolocation
A deep learning model for predicting coordinates of a tweet from its text

# Expected input for training

.csv files named with the coordinates (latitude_longitude) and containing the text of the tweet (column text), country (column geo_country) and optionally - meta-information.

# Output of the model

Tuple of code of the predicted country and the predicted pair of coordinates (latitude, longitude)
