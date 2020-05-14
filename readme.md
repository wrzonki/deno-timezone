# Deno timezones

## Set and sync timezone

### Example use:

```
import { Timezone } from "./timezone.ts";

const polishTime = new Timezone();
polishTime.offset = -120;
console.log(time.now());
