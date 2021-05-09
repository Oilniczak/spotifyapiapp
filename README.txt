Author/contact: maciekolejniczak9@gmail.com
Language: C#
.NET Framework 4.7.2

Step by step:

1. You have to add Newtonsoft JSON extension for parsing recived data.
2. Go to -> https://developer.spotify.com/dashboard/login
3. Log in.
4. Create app.
5. In app settings set Redirect URI to http://localhost:{*port}/
6. Copy your Client ID & Client Secret from spotify web app.
7. Paste Client ID & Client Secret to C# program.
8. Go to -> https://www.base64encode.org
9. Encode to base64 ---> Client ID:Client Secret <---
10. Paste encoded Client ID & Client Secret to program.


*port schould be unused in your network and the same as in project!

App may contains small bugs!

Thanks.
Maciek