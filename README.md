# docker-puppeteer
Puppeteer execution docker environment. (nodejs, chromium installed)

### Usage
```typescript
import * as puppeteer from 'puppeteer';

 const browser = await puppeteer.launch( {
    executablePath: process.env.CHROMIUM_PATH,
    args: ['--no-sandbox', '--disable-dev-shm-usage'],
});
```