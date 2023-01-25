# Google_Cyclistic
dataset: https://divvy-tripdata.s3.amazonaws.com/index.html

The data came from company called Divvy at Chicago provided by Google. In these dataset we will see how much the bike user activity from this Company on January 2022.

# User Category in Divvy
There are 2 type of user using Divvy bike sharing service: Member and Casual. We will see the importance of each these user category based on their activity.
 <p align="center">
 <img src="https://github.com/salmanzf/Google_Cyclistic/blob/streamlit/Gambar/gambar1.png">
 </p>
It turns out that the number of Member user in January 2022 far exceeds the Casual user in frequency and total duration.

Aside from User category, Divvy also has bike type for user: Electric bike, classic bike, and docked bike.
[gambar2]
Electric bike and classic bike each has more Member user than Casual user, except for docked bike which looked like reserved for Casual user.

## Is It Worth Keeping Docked Bike?
[gambar3]
Despite the really low count of use in January 2022, docked bike contribute about 10% total duration of usage. This is a considerable amount, as we can see docked bike has a much higher median duration which means higher duration per person and has tremendous potential. So regarding the low count number, is it because the lack of user or the lack of facility on docked bike?

# Difference Between Member and Casuar User
[gambar4]
Member user has high uses during weekdays, compared to Casual user which has peak use during weekend (Saturday).
[gambar5]
Overall Casual user has more duration per user, mostly during weekend. From the distribution throughout the wee can also see that Member user has more uniform distribution than Casual users, implying Member user use it for daily necessities (work, school, etc). My hypothesis is most of the Member users are worker and student, and casual user are reguler citizen for sightseeing and tourists.

## Popular Station
To prove our hypothesis, we can see the behaviour of each category by observing the most popular spot.
[gambar6]
From the top 10 station of each user category, most of the popular station for Member users are residential and metropolitan area for office, shop, cafe, etc. However, most of the popular station for Casual users are recreation spot like city park, museum, aquarium, etc. And once again, Member user has more uniform distribution than Casual user, implying that each area has similar behaviour which is daily necessities compared to impulsive behaviour like recreation. These graphs support our hypothesis and we can conclude that most of the Member users are worker and student, and Most of the Casual users are regular citizen and tourist for recreation.

# What This Mean In The Future?
Now we know our demographic in each category, we know that some of the Casual user are the potential future Member user (worker & student) who just started using bike sharing service. Then what about regular citizens and tourists who uses it for recreational purposes once in a while?
[gambar7]
Despite only contributing 18% in the number of count ride frequency, casual user manage to contribute 31% of total duration in January 2022
[gambar8]
Thoughout the month, we can see the Casual users are harder to predict than Member user. Member user tend to dip during weekend (1st-2nd, 8th-9th,...), whereas Casual user peak during New Year's Eve and during the weekday when theres no event or holiday tend to dip really low. Despite the high potential, we must realize that most of these Casual user didn't really need Membership status since their only interests is during holiday or big events.

## Suggestion
Let's see the popular spot from Casual user
[gambar9]
[gambar10]
Among the Top 10 popular spot the distribution is too skewed, where Top 2 has 49% of Total Duration compared the rest. This leaves for improvement for the rest of the spot in the Top 10.
According all of the graphs shown, here are my recommendation:
- Coordinating with officials in the respected area to have or maintain a bike-friendly road to popular spot (focus the top 10 first)
- Prepare a promo or event during weekend and holiday among the popular spot for bike user
- Prepare more unit for docked bike type, since it has huge potential despite the low count
