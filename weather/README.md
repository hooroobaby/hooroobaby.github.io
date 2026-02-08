# Weather Page Setup

## Quick Start

1. Edit `config.js` and add your API key:
   ```javascript
   const WEATHER_CONFIG = {
       API_KEY: 'your_api_key_here'
   };
   ```

2. Get your free API key at: https://openweathermap.org/api

3. node version stable 20

```
node --version

nvm use 20
nvm alias default 20
```

4. deploy

```
hexo clean && hexo generate 
hexo deploy
```