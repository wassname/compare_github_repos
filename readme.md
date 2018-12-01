Static site for comparing github repositories/users by commits, issues, updated, contributors and other statistics. 

This is beta so it may not work for everyone, fixed via pull requests welcome :)

# Usage:

- Go to github.io site: https://wassname.github.io/compare_github_repos/src/
- Click "Github api token" to follow the link and generate a github api token (must be logged in, it will be cached locally only)
- enter csv inputs as in the example
- open browser javascript console so you can check for errors (it's alpha) (probobly turn off "disable cache" in the network tab so it goes faster)
- click go, you should see the go button replaced with a countdown
- after the countdown you should see a table and a box with a raw markdown table


# Example output:

|title|commits per week (for last year)|watchers|open issues|created|updated|contributors (up to 100)|forks|url|
|---|---|---|---|---|---|---|---|---|
|[RLgraph](https://github.com/rlgraph/rlgraph)|59.385|35|13|2018-05-04|2018-11-30|3|2|https://github.com/rlgraph/rlgraph|
|[araffin/robotics-rl-srl](https://github.com/araffin/robotics-rl-srl)|16.154|199|3|2018-01-18|2018-11-30|5|13|https://github.com/araffin/robotics-rl-srl|
|[tensorlayer/tensorlayer](https://github.com/tensorlayer/tensorlayer)|14.365|4540|45|2016-06-07|2018-11-30|71|1085|https://github.com/tensorlayer/tensorlayer|
|[Stable Baselines](https://github.com/hill-a/stable-baselines)|11.538|427|24|2018-07-02|2018-11-30|49|46|https://github.com/hill-a/stable-baselines|
|[tensorpack/tensorpack](https://github.com/tensorpack/tensorpack)|11.269|3256|13|2015-12-25|2018-12-01|36|1026|https://github.com/tensorpack/tensorpack|
|[lcswillems/torch-rl](https://github.com/lcswillems/torch-rl)|7.346|71|1|2018-04-11|2018-11-28|3|15|https://github.com/lcswillems/torch-rl|
|[TensorForce](https://github.com/reinforceio/tensorforce)|6.788|2073|36|2017-03-19|2018-11-30|46|378|https://github.com/reinforceio/tensorforce|
|[Vel](https://github.com/MillionIntegrals/vel)|6.615|186|8|2018-05-09|2018-11-30|4|17|https://github.com/MillionIntegrals/vel|
|[facebookresearch/Horizon](https://github.com/facebookresearch/Horizon)|6.596|1369|5|2017-07-27|2018-11-30|15|148|https://github.com/facebookresearch/Horizon|
|[kengz/SLM-Lab](https://github.com/kengz/SLM-Lab)|6.288|407|1|2017-10-02|2018-11-26|5|60|https://github.com/kengz/SLM-Lab|
|[navneet-nmk/pytorch-rl](https://github.com/navneet-nmk/pytorch-rl)|5.692|161|0|2018-02-28|2018-11-30|1|18|https://github.com/navneet-nmk/pytorch-rl|
|[Coach](https://github.com/NervanaSystems/coach)|5.654|958|12|2017-10-01|2018-12-01|21|177|https://github.com/NervanaSystems/coach|
|[zuoxingdong/lagom](https://github.com/zuoxingdong/lagom)|5.192|203|8|2017-12-21|2018-11-30|4|15|https://github.com/zuoxingdong/lagom|
|[ShangtongZhang](https://github.com/ShangtongZhang/DeepRL)|4.5|966|2|2017-04-20|2018-11-30|3|211|https://github.com/ShangtongZhang/DeepRL|
|[unixpickle/anyrl-py](https://github.com/unixpickle/anyrl-py)|4.135|94|9|2017-09-18|2018-11-29|4|20|https://github.com/unixpickle/anyrl-py|
|[inoryy/reaver-pysc2](https://github.com/inoryy/reaver-pysc2)|3.769|274|3|2017-10-21|2018-11-30|1|45|https://github.com/inoryy/reaver-pysc2|
|[ikostrikov](https://github.com/ikostrikov/pytorch-a2c-ppo-acktr)|2.462|1030|20|2017-08-22|2018-11-30|17|216|https://github.com/ikostrikov/pytorch-a2c-ppo-acktr|
|[rlkit](https://github.com/vitchyr/rlkit)|0.769|325|0|2018-01-25|2018-12-01|2|65|https://github.com/vitchyr/rlkit|
|[MorvanZhou/Reinforcement-learning-with-tensorflow](https://github.com/MorvanZhou/Reinforcement-learning-with-tensorflow)|0.692|2678|7|2017-05-06|2018-11-30|4|1729|https://github.com/MorvanZhou/Reinforcement-learning-with-tensorflow|
|[TRFL](https://github.com/deepmind/trfl)|0.558|1934|0|2018-08-08|2018-11-30|6|215|https://github.com/deepmind/trfl|
|[deepmind/scalable_agent](https://github.com/deepmind/scalable_agent)|0.327|535|4|2018-06-06|2018-11-29|2|68|https://github.com/deepmind/scalable_agent|
|[RL-Adventure](https://github.com/higgsfield/RL-Adventure-2)|0.212|1481|4|2018-05-26|2018-11-30|3|157|https://github.com/higgsfield/RL-Adventure-2|
|[Udacity](https://github.com/udacity/deep-reinforcement-learning)|0.173|1683|3|2018-07-06|2018-11-30|1|519|https://github.com/udacity/deep-reinforcement-learning|
|[RLLAB](https://github.com/rll/rllab)|0.019|1932|109|2016-04-21|2018-11-30|29|615|https://github.com/rll/rllab|



# TODO

- [x] bitbucket
- [x] github organisations
- [x] progbar
- [x] configurable repos
