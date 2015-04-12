# grsu-shedule-parser

[![npm package](https://nodei.co/npm/grsu-shedule-parser.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/grsu-shedule-parser/)

## Super simple to use
This module is designed to parse the GRSU schedules page.
data - is a html page with the schedule,
parsedata - ready weekly schedule.

```js
var SheduleParse = require('grsu-shedule-parser');
SheduleParse(data, function(err, parsedata) {
                    if(err)
                        throw new Exception(err);
                    console.log(parsedata);
});
```
