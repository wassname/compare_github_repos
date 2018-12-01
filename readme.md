Static site for comparing github repos/users. This is beta so it may not work for you, pull requests welcome.

# Usage:

- Go to github.io site: https://wassname.github.io/compare_github_repos/src/
- Click "Github api token" to follow the link and generate a github api token (must be logged in, it will be cached locally only)
- enter csv inputs as in the example
- open browser javascript console so you can check for errors (it's alpha)
- click go, you should see the go button replaced with a countdown
- aftr the countdown you should see a table and a box with a raw markdown table


# Example output:

|name|commits per week (for last year)|watchers|open issues|created|updated|contributors (up to 100)|
|---|---|---|---|---|---|---|
|RLgraph|59.231|35|13|2018-05-04|2018-11-29|3|
|araffin/robotics-rl-srl|16.154|198|3|2018-01-18|2018-11-29|5|
|tensorlayer/tensorlayer|14.385|4538|45|2016-06-07|2018-11-30|71|
|Stable Baselines|11.538|424|24|2018-07-02|2018-11-29|49|
|tensorpack/tensorpack|11.269|3246|13|2015-12-25|2018-11-30|36|
|lcswillems/torch-rl|7.404|71|1|2018-04-11|2018-11-28|3|
|TensorForce|6.808|2072|36|2017-03-19|2018-11-30|46|
|Vel|6.615|185|8|2018-05-09|2018-11-29|4|
|facebookresearch/Horizon|6.596|1363|5|2017-07-27|2018-11-30|15|
|kengz/SLM-Lab|6.288|407|1|2017-10-02|2018-11-26|5|
|navneet-nmk/pytorch-rl|5.673|160|0|2018-02-28|2018-11-29|1|
|Coach|5.654|955|12|2017-10-01|2018-11-30|20|
|zuoxingdong/lagom|5.173|203|6|2017-12-21|2018-11-29|4|
|ShangtongZhang|4.5|963|2|2017-04-20|2018-11-29|3|
|unixpickle/anyrl-py|4.154|94|9|2017-09-18|2018-11-29|4|
|inoryy/reaver-pysc2|3.769|271|3|2017-10-21|2018-11-30|1|
|ikostrikov|2.442|1026|20|2017-08-22|2018-11-29|17|
|rlkit|0.769|324|0|2018-01-25|2018-11-30|2|
|MorvanZhou/Reinforcement-learning-with-tensorflow|0.692|2674|7|2017-05-06|2018-11-30|4|
|TRFL|0.558|1930|0|2018-08-08|2018-11-30|6|
|deepmind/scalable_agent|0.327|535|4|2018-06-06|2018-11-29|2|
|RL-Adventure|0.212|1479|4|2018-05-26|2018-11-30|3|
|Udacity|0.173|1679|3|2018-07-06|2018-11-30|1|
|RLLAB|0.019|1930|109|2016-04-21|2018-11-29|29|


# TODO

- [x] bitbucket
- [x] github organisations
- [x] progbar
- [x] configurable repos
