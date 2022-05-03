---
widget: pages
headless: true
weight: 10
title: Live Stream
active: true
design:
  columns: 1
---

<!-- Add a placeholder for the Twitch embed -->
<div id="twitch-embed"></div>

<!-- Load the Twitch embed JavaScript file -->
<script src="https://embed.twitch.tv/embed/v1.js"></script>

<!-- Create a Twitch.Embed object that will render within the "twitch-embed" element -->
<script type="text/javascript">
  new Twitch.Embed("twitch-embed", {
    width: "100%",
    height: 680,
    channel: "rcllaachen",
    layout: "video",
    // Only needed if this page is going to be embedded on other websites
    parent: ["embed.example.com", "othersite.example.com"]
  });
</script>

<center><a href="https://twitch.tv/rcllaachen">twitch.tv/rcllaachen</a></center>

