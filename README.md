# Raid West Trail 2025 Analysis 🏃
A project aimed to compare and contrast my running performance at the 2025 Raid West Trail Race using the gpxpy package and Jupyter notebook. 

> ⚠️ This is only meant as a quick and dirty project written by a semi-asleep developer (me). The best practices were ignored as much as common sense.

Recently, during one of my training sessions, I had the following conversation with my coach:

> _me: ...I have the feeling that I was a bit slower on the descent during the race than when I ran during the reconnaissance run the week before..._

>_coach: ...is it just a feeling or is it factual..?

I could have easily answered this question by browsing the Garmin Connect App. But as a true developer and data engineer, I had to make things a lot more complicated just get the chance to tinker with data 😅.

## Requirements
- Python on your host machine
- The python package `jupyter` installed at global-level

## Data Source
- Log in to https://connect.garmin.com/
- Browser through `Activities`
- Click on `Export to GPX`
- Files are stored within the `data` directory

## Launch Notebook
Execute the following in the root directory of the repository:

```shell
jupyter notebook .
```




