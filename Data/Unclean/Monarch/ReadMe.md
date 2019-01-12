# Monarch Cleaning
## Drop Columns
* ID: Replaced by df index and not important for a filtered DataFrame
* Observed_on_string : literally a string that repeats what the observed_on and time_observed already say
* Time_zone : We have UTC times, not important for our analysis.
* User_id and user_login: why do we even have these?
* created_at : not helpful for analysis
* license_url, image_url, sound_url : links for image set, not helpful
* tag_list : hashtag butterfly, hashtag happy, hashtag fall, hashtag pumpkin spice
