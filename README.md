# NBA Datasets

Welcome to the **NBA Datasets** repository! This project aims to provide comprehensive datasets related to the National Basketball Association (NBA) sourced from [basketball-reference.com](https://www.basketball-reference.com/).

## Project Status

⚠️ Early Stages: This project is currently in the early stages of development. The datasets provided are limited, but i'm actively working on incorporating play-by-play stats and shot charts data.

## Datasets

### Schedule

League,Season,Date,Start (ET),Visitor,Visitor PTS,Visitor Record,Home,Home PTS,Home Record,Game Reference,OT,Attendance,Arena,Playoffs,Series
NBA,2022-2023,2023-06-12,8:30p,MIA,89,1-4,DEN,94,4-1,202306120DEN,,"19,537",Ball Arena,True,Finals


|League|Season|Date|Start (ET)|Visitor|Visitor PTS|Visitor Record|Home|Home PTS|Home Record|Game Reference|OT|Attendance|Arena|Playoffs|Series|
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|NBA|2022-2023|2023-06-12|8:30p|MIA|89|1-4|DEN|94|4-1|202306120DEN||"19,537"|Ball Arena|True|Finals|

### Boxscores

#### Basic

|Player Name|Player Reference|Game Reference|Team|Period|Starter|MP|FG|FGA|FG%|3P|3PA|3P%|FT|FTA|FT%|ORB|DRB|TRB|AST|STL|BLK|TOV|PF|PTS|+/-|
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Jamal Murray|murraja01|202306120DEN|DEN|game|True|41:15|6|15|.400|2|7|.286|0|0||0|8|8|8|1|0|6|2|14|+12|

#### Advanced

|Player Name|Player Reference|Game Reference|Team|Period|Starter|MP|TS%|eFG%|3PAr|FTr|ORB%|DRB%|TRB%|AST%|STL%|BLK%|TOV%|USG%|ORtg|DRtg|BPM|
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Jamal Murray|murraja01|202306120DEN|DEN|game|True|41:15|.467|.467|.467|.000|0.0|16.3|9.2|30.0|1.2|0.0|28.6|22.6|80|95|-2.9|

## Data Collection
The datasets have been collected using a custom API designed specifically for scraping basketball-related data from basketball-reference.com. This API will be published as a separate project once it's finished. We are committed to ensuring that the scraping process is respectful of the website's terms of service.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

**Disclaimer: This project is not affiliated with or endorsed by basketball-reference.com. Please review and comply with the terms of service of the website when using this data.**