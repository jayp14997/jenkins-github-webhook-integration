# jenkins-github-webhook-integration

Ngrok Setup:
1. Go to  - https://ngrok.com/
2. Sign Up and download zip file and extract the .exe file in some folder
3. Get your authtoken from your ngrok account
4. Go to ngrok.exe folder and open terminal
5. Pass this command - ngrok.exe authtoken “your token value” hit enter
6. Pass this command - Ngrok.exe http 8080 hit enter
7. Get the Forwarding URL – from ngrok CLI – http://e530a6f192dd.ngrok.io
 Github Setting:
8. Go to GitHub project setting - Webhooks
9. Add webhooks url - http://e530a6f192dd.ngrok.io/github-w...
10. Now make git commit
11. Build will start automatically
