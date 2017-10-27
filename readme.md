# esp3-parser
Checks if the received buffer is a vaild EnOcean Serial Protocol 3 packet.

## Requirements
This parser is made for >= serialport@5.0.0

## Usage
Only create a new parser:
```javascript
const ESP3Parser = require('esp3-parser');
...
const parser = new ESP3Parser();
```
Then pipe it to serialport.

## Note
This parser only validates if a packet is a vaild ESP3 packet.

## Changes
### 0.0.5
Catch if the length of the buffer isn't correct.
