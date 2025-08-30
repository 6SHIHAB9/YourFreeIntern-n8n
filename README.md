⚡ Workflow Overview


Schedule Trigger ⏰

Runs 3 times a day (8am, 12pm, 6pm).

Optional time randomizer makes posts appear at pseudo-random intervals.

Content vs Promo Selector 🎲

Generates a random pick.

80% chance → content tweet

20% chance → promotional ad

Content Path ✍️

Uses Google Gemini to generate unique tweets.

Cross-checks with database to avoid repetition.

Logs tweet into Google Sheets for future tracking.

Promo Path 💰

Uses a dedicated promotional template generator.

Posts the ad without logging (keeps database clean).

Tweet Publishing 🐦

Posts final tweet to X (Twitter).

🛠️ Tech Stack

n8n (workflow automation)

Google Gemini API (AI-generated content)

Google Sheets (content logging + history)

Twitter API (X) (tweet publishing)
