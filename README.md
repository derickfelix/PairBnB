# PairBnB

A place booking app, where people can offer their places and you can book other places, a little bit like AirBnB

## Important
Paste this code below as a new file <code>src/environments/environment.ts</code>

```typescript
// This file can be replaced during build by using the `fileReplacements` array.
// `ng build --prod` replaces `environment.ts` with `environment.prod.ts`.
// The list of file replacements can be found in `angular.json`.

export const environment = {
  production: false,
  // I am using firebase's realtime database url, you can use any other
  serverBaseUrl: '<PLACE YOUR BACKEND URL HERE>',
  googleMapsApiKey: '<PLACE YOUR GOOGLE MAPS API KEY HERE>'
};

/*
 * For easier debugging in development mode, you can import the following file
 * to ignore zone related error stack frames such as `zone.run`, `zoneDelegate.invokeTask`.
 *
 * This import should be commented out in production mode because it will have a negative impact
 * on performance if an error is thrown.
 */
// import 'zone.js/dist/zone-error';  // Included with Angular CLI.
```
