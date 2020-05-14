# Deno timezones

## Set and sync timezone

### Example use:

```
import { Timezone } from "https://raw.githubusercontent.com/wrzonki/deno-timezone/master/timezone.ts";

const polishTime = new Timezone();
polishTime.offset = -120;
console.log(time.now());
