# Real-time-Insights-from-Twitter-Data

While we might not be Twitter fans, we have to admit that it has a huge influence on the world (who doesn't know about Trump's tweets). Twitter data is not only gold in terms of insights, but Twitter-storms are available for analysis in near real-time. This means we can learn about the big waves of thoughts and moods around the world as they arise.

As any place filled with riches, Twitter has security guards blocking us from laying our hands on the data right away ⛔️ Some authentication steps (really straightforward) are needed to call their APIs for data collection. Since our goal today is learning to extract insights from data, we have already gotten a green-pass from security ✅ Our data is ready for usage in the datasets folder — we can concentrate on the fun part! 🕵️‍♀️🌎

---
Twitter provides both global and local trends. Let's load and inspect data for topics that were hot worldwide (WW) and in the United States (US) at the moment of query — snapshot of JSON response from the call to Twitter's GET trends/place API.
<br>
Note: Here is the documentation for this call, and here a full overview on Twitter's APIs.
