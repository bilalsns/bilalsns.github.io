+++
template = 'home.html'

[extra]
lang = 'en'

# Show footer in home page
footer = false

# If you don't want to display id/bio/avatar, simply comment out that line
name = "Bilal S. B. (Bilol Bakhrillaev)"
id = "bilalsea"
bio = "engineer, athlete"
avatar = "img/avatar-1.webp"
links = [
    { name = "GitHub", icon = "github", url = "https://github.com/bilalsea2" },
    { name = "LinkedIn", icon = "linkedin", url = "https://linkedin.com/in/bilalsea" },
    # { name = "Strava", icon = "strava", url = "https://www.strava.com/athletes/bilalsea" },
]

# Show a few recent posts in home page
recent = false
recent_max = 15
recent_more_text = "more »"
date_format = "%b %-d, %Y"
+++
<script>
    let options = {
        timeZone: 'Asia/Tashkent',
        hour: 'numeric',
        minute: 'numeric',
        second: 'numeric',
    },
    formatter = new Intl.DateTimeFormat([], options);
    setInterval(
        () => {
            document.querySelector("#time").innerText = formatter.format(new Date());
        }
    , 1000)
</script>
<br>
<a href="https://24timezones.com/Tashkent/time">TIME IN TASHKENT CITY</a> - <span id="time"></span><a href="https://24timezones.com/time-zone/utc+05">UTC+5</a>