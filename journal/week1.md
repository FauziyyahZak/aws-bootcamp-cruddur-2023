# Week 1 — App Containerization
- I have containerized my application.

- I have documented the notification endpoint for the OpenAI document.

- I have a flask backend endpoint notification written.

- There is a react page for notifications.

- I have run DynamoDB local container, and ensured it works.

- I have run Postgres container and ensured it works.


- After I was done with the running of DynamoDB and Postgres, somehow, my port 3000 was persistently not running. Being quite new to all of these, it took me a while to understand what was going on. But with the help of ChatGPT, I was able to check the containers, and manually run the frontend container.

- At some point, I had gotten my frontend and backend running, the app was up, but without content. Tried troubleshooting personally and with a colleague. But at the end, I just needed to restart my docker compose file.
- ![Home feed](Materials/HomeFeed.png)
- ![Notifications feed](Materials/NotificationFeed.png)
- ![Postgres](Materials/Postgres.png)
