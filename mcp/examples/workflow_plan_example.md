## Example Workflow Plan (Planner Output)
1. Trigger: Cron at 02:00
2. Fetch Twitch VOD via HTTP Request
3. Send VOD URL to OpusClip API
4. Wait for webhook callback
5. Generate captions with GPT
6. Send to Slack for approval
7. Post approved clip to YouTube Shorts
