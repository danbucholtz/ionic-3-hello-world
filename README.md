
## Instructions to Run
1. npm install
2. npm run ionic:build --prod
3. source-map-explorer www/build/main.js www/build/main.js.map

## Details
This is a "hello world" Ionic project running Ionic 3 and Angular 4 RC5. It has 3rd party packages like `ionic-native` and other common Ionic libs stripped out to keep things simple.

By default, we have the following flags set to remove decorators (not all, but the important ones), generate source maps with a prod build, and writing the AoT files/metadata to disk in the `.tmp` directory.

```
"ionic_experimental_purge_decorators": true,
"ionic_generate_source_map": true,
"ionic_aot_write_to_disk": true
```

## Findings
To follow