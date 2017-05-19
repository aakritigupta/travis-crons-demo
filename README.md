# Running Scheduled builds with Travis CI
This repo demonstrates the use of [Travis CI's crons jobs](https://docs.travis-ci.com/user/cron-jobs).

The branch [`demo-skip-ci`](https://github.com/aakritigupta/travis-crons-demo/tree/demo-skip-ci), demonstrates adding `[skip ci]` to the commit message to skip running a cron job on the branch.

The branch [`demo-use-of-travis-event-type`](https://github.com/aakritigupta/travis-crons-demo/tree/demo-use-of-travis-event-type), makes use of the environment variable `TRAVIS_EVENT_TYPE` to recognise a cron job and run integration tests only in crons.

Feel free to fork this repo to play around with the .travis.yml to further customise cron jobs.

(This repo was originally forked from [travis-ci/travis-web](https://github.com/travis-ci/travis-web).)
