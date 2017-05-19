# Running Scheduled Builds with Travis CI
This repo demonstrates the use of [Travis CI's Crons Feature](https://docs.travis-ci.com/user/cron-jobs).

The branch [`demo-skip-ci`](https://github.com/aakritigupta/travis-crons-demo/tree/demo-skip-ci), demonstrates adding `[skip ci]` to the commit message to skip running a cron job on the branch.

The branch [`demo-use-of-travis-event-type`](https://github.com/aakritigupta/travis-crons-demo/tree/demo-use-of-travis-event-type), makes use of the environment variable `TRAVIS_EVENT_TYPE` to recognise a cron job and and use it as a conditional in deployments.

The other branches ca be used to setup crons and try out various options.

Feel free to fork this repo to play around with the `.travis.yml` to further customise cron jobs. :)
