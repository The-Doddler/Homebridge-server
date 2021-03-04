# Homebridge-server
Homebridge Server won't start
3/4/2021, 10:00:06 PM] [HB Supervisor] Restarting Homebridge...
[3/4/2021, 10:00:06 PM] [HB Supervisor] Starting Homebridge with extra flags: -I
[3/4/2021, 10:00:06 PM] [HB Supervisor] Started Homebridge v1.3.2 with PID: 2613
Initializing HAP-NodeJS v0.9.2...
Error: Cannot find module './functions/clean'
Require stack:
- /usr/lib/node_modules/homebridge/node_modules/semver/index.js
- /usr/lib/node_modules/homebridge/lib/plugin.js
- /usr/lib/node_modules/homebridge/lib/pluginManager.js
- /usr/lib/node_modules/homebridge/lib/server.js
- /usr/lib/node_modules/homebridge/lib/cli.js
- /usr/lib/node_modules/homebridge/bin/homebridge
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:880:15)
    at Function.Module._load (internal/modules/cjs/loader.js:725:27)
    at Module.require (internal/modules/cjs/loader.js:952:19)
    at require (internal/modules/cjs/helpers.js:88:18)
    at Object.<anonymous> (/usr/lib/node_modules/homebridge/node_modules/semver/index.js:13:10)
    at Module._compile (internal/modules/cjs/loader.js:1063:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1092:10)
    at Module.load (internal/modules/cjs/loader.js:928:32)
    at Function.Module._load (internal/modules/cjs/loader.js:769:14)
    at Module.require (internal/modules/cjs/loader.js:952:19)
[3/4/2021, 10:00:07 PM] [HB Supervisor] Homebridge Process Ended. Code: 1, Signal: null
