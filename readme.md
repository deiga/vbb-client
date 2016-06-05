# *vbb-client*

**An [API](https://github.com/derhuerst/vbb-rest) client for Berlin & Brandenburg public transport.** It's just a thin wrapper around [`got`](https://github.com/sindresorhus/got#usage).

[![npm version](https://img.shields.io/npm/v/vbb-client.svg)](https://www.npmjs.com/package/vbb-client)
[![build status](https://img.shields.io/travis/derhuerst/vbb-client.svg)](https://travis-ci.org/derhuerst/vbb-client)
[![dependency status](https://img.shields.io/david/derhuerst/vbb-client.svg)](https://david-dm.org/derhuerst/vbb-client)
[![dev dependency status](https://img.shields.io/david/dev/derhuerst/vbb-client.svg)](https://david-dm.org/derhuerst/vbb-client#info=devDependencies)
![ISC-licensed](https://img.shields.io/github/license/derhuerst/vbb-client.svg)


## Installing

```shell
npm install vbb-client
```


## Usage

Refer to the [API docs](https://github.com/derhuerst/vbb-rest/blob/master/docs/index.md) for available parameters.

- `stations([query])` → [`Promise`][promise]/[`stream.Readable`][stream]
- `nearby([query])` → [`stream.Readable`][stream]
- `station(id)` → [`Promise`][promise]
- `departures(id, [query])` → [`Promise`][promise]
- `lines([query])` → [`stream.Readable`][stream]
- `line(id)` → [`Promise`][promise]
- `routes(from, to, [query])` → [`Promise`][promise]
- `map(type)` → [`stream.Readable`][stream]

[promise]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise
[stream]: https://nodejs.org/api/stream.html#stream_class_stream_readable


## Contributing

If you **have a question**, **found a bug** or want to **propose a feature**, have a look at [the issues page](https://github.com/derhuerst/vbb-client/issues).
