# volkswagen

Volkswagen detects when your tests are being run in a CI server, and makes them pass.

[![Build Status](https://travis-ci.org/repeatedly/d-volkswagen.svg?branch = master)](https://travis-ci.org/repeatedly/d-volkswagen)

## Why?

If you want your software to be adopted by Americans, good tests scores 
from the CI server are very important. Volkswagen uses a defeat device to 
detect when it's being tested in a CI server and will automatically 
reduce errors to an acceptable level for the tests to pass. This will
allow you to spend _less_ time worrying about testing and _more_ time
enjoying the good life as a trustful software developer.

## Usage

Import only one file;

```js
import volkswagen;
```

## Project status

CI servers detected:

- [Travis CI](http://travis-ci.org)
- [CircleCI](http://circleci.com)
- [Jenkins CI](https://jenkins-ci.org)

## License

MIT

## Credits

Inspired by https://github.com/hmlb/phpunit-vw and https://github.com/auchenberg/volkswagen
