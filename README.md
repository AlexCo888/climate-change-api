# An API showing all the latest Climate Change News around the world.

Made with Node.js, Express, Axios and Cheerio. Deployed in Heroku.

### Website: https://api-climatechange.herokuapp.com/

## Endpoints

| ENDPOINTS | PATH                | NAME                        | DESCRIPTION                                                                                                                                                                                                                                                                                                                                          |
| --------- | ------------------- | --------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| GET       | /news               | Get All Climate Change News | This endpoint will return back all news about Climate Change from all over the world.                                                                                                                                                                                                                                                                |
| GET       | /news/{newspaperId} | Get Individual Source News  | You can choose between:<br>- The Times {thetimes},<br>- The Guardian {guardian},<br>- The Telegraph {telegraph},<br>- BBC {bbc},<br>- The Standard {es},<br>- The Sun {sun},<br>- Daily Mail {dm},<br>- New York Post {nyp},<br>- United Nations {un},<br>- Sydney Morning Herald {smh},<br>- Los Angeles Times {latimes},<br>- New York Times {nyt} |

## Response example:

```json
{
  "title": "Xi set to snub UK climate summit as Queen’s irritation grows",

  "url": "https://www.thetimes.co.uk/article/xi-jinping-expected-to-snub-uk-summit-on-climate-crisis-7vkrst6hf",

  "source": "thetimes"
}
```
