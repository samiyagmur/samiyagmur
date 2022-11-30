### 👋Hi,I'm Ömer Sami :)
#### 👀I'm İnterested in Game Development
#### I'm learning unity nowadays
#### I work so much for entering Game Bootcamps

## ![Alt Text](https://media.giphy.com/media/ToMjGpzot8uTh5nUwnu/giphy.gif)
#### I've some programming learning document.
#### I hope These documents help your needed.

Contact📫:
E-Mail: Samiyagmur@gmail.com
LinkedIn: linkedin.com/in/ömer-sami-yağmur-6b64b018b
Itch.io_: https://sami-yagmur.itch.io/

<img src="https://media.giphy.com/media/Rs2iAnfEImXIs/giphy.gif" alt="Alt Sol Text" style="zoom:150%;" />
<!-- Include the library. -->
<script
  src="https://unpkg.com/github-calendar@latest/dist/github-calendar.min.js">
</script>

<!-- Optionally, include the theme (if you don't want to struggle to write the CSS) -->
<link
  rel="stylesheet"
  href="https://unpkg.com/github-calendar@latest/dist/github-calendar-responsive.css"
/>

<!-- Prepare a container for your calendar. -->
<div class="calendar">
    <!-- Loading stuff -->
    Loading the data just for you.
</div>

<script>
    GitHubCalendar(".calendar", "your-username");

    // or enable responsive functionality:
    GitHubCalendar(".calendar", "your-username", { responsive: true });

    // Use a proxy
    GitHubCalendar(".calendar", "your-username", {
       proxy (username) {
         return fetch(`https://your-proxy.com/github?user=${username}`)
       }
    }).then(r => r.text())
</script>
