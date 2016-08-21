---
layout: post
title: GSOC - Final Submissions
category: GSOC
---

## <b> Welcome </b>

Hi, my name is Saurabh Shah. I worked on Long Running Ruby and Rails Benchmarks project this Google Summer of Code under Ruby organization.

## <b> Description </b>

[RubyBench](https://rubybench.org/) is an amazing effort to keep long running benchmarks for Ruby and related projects (like Rails). Fixing performance bugs early on with proper set of benchmarks is cheap. Usually the longer we wait the more expensive it is to fix. This project aimed to improve RubyBench architecture with several added functionalities.

## <b> Work Done! </b>

=> Added sequel benchmarks for comparison with activerecord benchmarks in terms of performance. This included 3 repositories; ruby-bench-suite for adding sequel benchmarks, ruby-bench-docker for writing docker scripts and ruby-bench-web to run the benchmarks whenever there is an incoming hook from github.


  * ruby-bench-suite

  [https://github.com/ruby-bench/ruby-bench-suite/commit/e8c495dce58b9902503b73ef2ec05e0c87be41a4](https://github.com/ruby-bench/ruby-bench-suite/commit/e8c495dce58b9902503b73ef2ec05e0c87be41a4)
  [https://github.com/ruby-bench/ruby-bench-suite/commit/8f6d93e0a680c27745b6a07b1c87f9285bcd1d80](https://github.com/ruby-bench/ruby-bench-suite/commit/8f6d93e0a680c27745b6a07b1c87f9285bcd1d80)
  [https://github.com/ruby-bench/ruby-bench-suite/commit/227bad262a060caee951e7ca50fe52c7bc1234f2](https://github.com/ruby-bench/ruby-bench-suite/commit/227bad262a060caee951e7ca50fe52c7bc1234f2)
  [https://github.com/ruby-bench/ruby-bench-suite/commit/cc10265ea8e5df19b6f94454b81d262361aca183](https://github.com/ruby-bench/ruby-bench-suite/commit/cc10265ea8e5df19b6f94454b81d262361aca183)

  * ruby-bench-docker

[https://github.com/ruby-bench/ruby-bench-docker/commit/e71204cdc6931a3249f556e043c36eca307c8429](https://github.com/ruby-bench/ruby-bench-docker/commit/e71204cdc6931a3249f556e043c36eca307c8429)

[https://github.com/ruby-bench/ruby-bench-docker/pull/20](https://github.com/ruby-bench/ruby-bench-docker/pull/20)

  * ruby-bench-web

    [https://github.com/ruby-bench/ruby-bench-web/pull/171](https://github.com/ruby-bench/ruby-bench-web/pull/171)

=> Update readme and add bash scripts in all the directories to run respective benchmarks

  [https://github.com/ruby-bench/ruby-bench-docker/pull/22](https://github.com/ruby-bench/ruby-bench-docker/pull/22)

=> A simple benchmark regression notifier built into RubyBench. Have it track the benchmark results of the last X number of commits and report a regression if a new result exceeds the previous baseline.

  [https://github.com/ruby-bench/ruby-bench-web/pull/174](https://github.com/ruby-bench/ruby-bench-web/pull/174)


## <b> Other Links </b>

* [Rubybench - Long Running Benchmarks](https://rubybench.org/)
* [Ruby-Bench-Web](https://github.com/ruby-bench/ruby-bench-web)
* [Ruby-Bench-Docker](https://github.com/ruby-bench/ruby-bench-docker)
* [Ruby-Bench-Suite](https://github.com/ruby-bench/ruby-bench-suite)
* [GSoC Project](https://summerofcode.withgoogle.com/projects/#5326839702618112)

## <b> Contact </b>

* shahsaurabh0103@gmail.com
* [shahsaurabh.me](http://shahsaurabh.me/)
