# **Investigating Netflix Movies**

**Netflix**! What started in 1997 as a DVD rental service has since exploded into one of the largest entertainment and media companies.
Given the large number of movies and series available on the platform, it is a perfect opportunity to flex your exploratory data analysis skills and dive into the entertainment industry.
You work for a production company that specializes in nostalgic styles. You want to do some research on movies released in the 1990's. You'll delve into Netflix data and perform exploratory data analysis to better understand this awesome movie decade!
You have been supplied with the dataset `netflix_data.csv`, along with the following table detailing the column names and descriptions. Feel free to experiment further after submitting!

## The data
### **netflix_data.csv**
| Column | Description |
|--------|-------------|
| `show_id` | The ID of the show |
| `type` | Type of show |
| `title` | Title of the show |
| `director` | Director of the show |
| `cast` | Cast of the show |
| `country` | Country of origin |
| `date_added` | Date added to Netflix |
| `release_year` | Year of Netflix release |
| `duration` | Duration of the show in minutes |
| `description` | Description of the show |
| `genre` | Show genre |


# In this project you are tasked to perform exploratory data analysis on the netflix_data.csv data to understand more about movies from the 1990s decade.

    1. What was the most frequent movie duration in the 1990s? Save an approximate answer as an integer called duration (use 1990 as the decade's start year).

    2. A movie is considered short if it is less than 90 minutes. Count the number of short action movies released in the 1990s and save this integer as short_movie_count.

# Most Frequent Movie Duration in the 1990s
<img width="699" height="564" alt="image" src="https://github.com/user-attachments/assets/49f5d130-b018-4f47-b89b-287f059cdb36" />
**Based on the histogram provided the most frequent duration in the 1990s is 94 minutes**

# Count of short action movies in 1990s (<90 minutes)
<img width="706" height="550" alt="image" src="https://github.com/user-attachments/assets/12c2042e-1562-4be2-855e-3d48595cc16d" />
**Based on the histogram There are 7 movies that are considered short action movies
"EVANGELION: DEATH (TRUE)²" is the shortest movie with a duration of 69 minutes
89 minutes is the most frequent movie duration among the shortest action movies in the 1990s**
