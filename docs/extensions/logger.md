# Logger

An extension that logs events generated by Redux Beacon.

### Installation

```bash
npm install --save @redux-beacon/logger
```

### Import

```js
import logger from '@redux-beacon/logger';
```

### Usage

Include the logger when creating a middleware or meta reducer:


```js
const middleware = createMiddleware(eventsMap, target, { logger });
const metaReducer = createMetaReducer(eventsMap, target, { logger });
```
