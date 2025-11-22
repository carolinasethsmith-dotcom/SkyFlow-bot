# SkyFlow-Bot

**Description**  
SkyFlow-Bot is an automated workflow that connects weather and astronomy APIs to send notifications via Telegram. It helps users know which nights are clear and which planets are visible from their location.

**Main Workflow**  
1. Call weather API  
2. Filter cloudiness <30%  
3. Call astronomy API  
4. Format message  
5. Send to Telegram

**Goal**  
Automate weather and astronomy alerts with an Agile/Scrum approach for continuous improvement.

**Current Status**  
- Weather API tested and working  
- Telegram notifications working  
- Full integration pending (blocked by astronomy API)

**How to Use / Configure**  
1. Clone this repository  
2. Create a `.env` file with your API keys and Telegram chat ID  
3. Import or configure your scenario in Make  
4. Run the workflow manually for testing  

**Scrum / Agile**  
- Product Vision: automate useful alerts for astronomy enthusiasts  
- Backlog and sprints managed with GitHub Issues & Project Board
# SkyFlow-bot
Automated weather + Astronomy notifications to telegram using Make
