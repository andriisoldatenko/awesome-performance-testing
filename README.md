# Awesome performance testing collection

A collection of awesome performance testing resources

* [Software performance testing](http://en.wikipedia.org/wiki/Software_performance_testing) - In software engineering, performance testing is in general testing performed to determine how a system performs in terms of responsiveness and stability under a particular workload. It can also serve to investigate, measure, validate or verify other quality attributes of the system, such as scalability, reliability and resource usage.

* [Tsung](http://tsung.erlang-projects.org/) - is an open-source multi-protocol distributed load testing tool. It can be used to stress HTTP, WebDAV, SOAP, PostgreSQL, MySQL, LDAP and Jabber/XMPP servers.
* [Apache Jmeter](http://jmeter.apache.org/) - is an Apache project that can be used as a load testing tool for analyzing and measuring the performance of a variety of services, with a focus on web applications.
* [Yandex.Tank](https://github.com/yandex/yandex-tank) - is an extendable open source load testing tool for advanced linux users which is especially good as a part of automated load testing suit.
* [Gatling](https://github.com/gatling/gatling) - is an Akka and Netty backed asynchronous loading test tool for HTTP/HTTPS with nice Scala DSL for writing tests
* [k6](https://github.com/grafana/k6) - is a modern and developer-centric load testing tool for API and website testing, tests are written in ES6 JS with support for HTTP/1.1, HTTP/2.0 and WebSocket protocols, written in Go.
* [Locust](https://github.com/locustio/locust) - is an easily distributed loading test tool for load testing web sites and services, tests are written in Python. Featured in <https://cloud.google.com/solutions/distributed-load-testing-using-kubernetes>
* [YSlow](http://yslow.org/) - analyzes web pages and why they're slow based on Yahoo!'s rules for high performance web sites.
* [PageSpeed](https://developers.google.com/speed/pagespeed/) - Fast and optimized pages lead to higher visitor engagement, retention, and conversions. The PageSpeed family of tools is designed to help you optimize the performance of your website. PageSpeed Insights products will help you identify performance best practices that can be applied to your site, and PageSpeed optimization tools can help you automate.
* [ApacheBench](http://httpd.apache.org/docs/2.2/programs/ab.html) - (ab) is a single-threaded command line computer program for measuring the performance of HTTP web servers. Originally designed to test the Apache HTTP Server, it is generic enough to test any web server.
* [artillery.io](https://artillery.io) - distributed load testing tool in NodeJS, supports tests for HTTP, socket.io, WebSockets and AWS Kinesis. Configuration is written in YAML or JSON, and further customization via templating in Node. Also has APIs for functional tests via assert/expect.
* [tcpkali](https://github.com/satori-com/tcpkali) - Fast multi-core TCP and WebSockets load generator.
* [hey](https://github.com/rakyll/hey) - hey is a tiny program that sends some load to a web application. It was originally called boom and was influenced from Tarek Ziade's tool at tarekziade/boom. Using the same name was a mistake as it resulted in cases where binary name conflicts created confusion. To preserve the name for its original owner, we renamed this project to hey.
* [stress](https://linux.die.net/man/1/stress) - stress - tool to impose load on and stress test systems.
* [fortio](https://github.com/fortio/fortio) - Fortio (Φορτίο) started as, and is, Istio's load testing tool and now graduated to be its own project. Fortio runs at a specified query per second (qps) and records an histogram of execution time and calculates percentiles (e.g. p99 ie the response time such as 99% of the requests take less than that number (in seconds, SI unit)).
* [wrk](https://github.com/wg/wrk) - wrk is a modern HTTP benchmarking tool capable of generating significant load when run on a single multi-core CPU. It combines a multithreaded design with scalable event notification systems such as epoll and kqueue. An optional LuaJIT script can perform HTTP request generation, response processing, and custom reporting. Examples available.
* [wrk2](https://github.com/giltene/wrk2) - wrk2 is wrk modifed to produce a constant throughput load, and accurate latency details to the high 9s (i.e. can produce accurate 99.9999%'ile when run long enough). In addition to wrk's arguments, wrk2 takes a throughput argument (in total requests per second) via either the --rate or -R parameters (default is 1000).
* [httperf](https://github.com/httperf/httperf) - httperf is a tool for measuring web server performance. It provides a flexible facility for generating various HTTP workloads and for measuring server performance. The focus of httperf is not on implementing one particular benchmark but on providing a robust, high-performance tool that facilitates the construction of both micro- and macro-level benchmarks. The three distinguishing characteristics of httperf are its robustness, which includes the ability to generate and sustain server overload, support for the HTTP/1.1 and SSL protocols, and its extensibility to new workload generators and performance measurements.
* [ali](https://github.com/nakabonne/ali) - ali is a load testing tool capable of performing real-time analysis, inspired by vegeta and jplot. Ali comes with an embedded terminal-based UI where you can plot the metrics in real-time, so lets you perform real-time analysis on the terminal.
* [fasthttploader](https://github.com/hagen1778/fasthttploader) - Fasthttploader was created to simplify http benchmarking. Options like QueryPerSecond(QPS) and number of connections are not required anymore. Fasthttploader detects server possibilities by analyzing repsonses and choosing optimal conditions for testing. To avoid adjustment stage (cause it takes some extra time) - just set -q and -c flags. Fasthttploader generates html-report after testing with some useful charts.
* [ddosify](https://github.com/ddosify/ddosify) - High-performance load testing scenario-based tool with current support of HTTP, HTTPS, HTTP/2, you can create your flow in a JSON file without a line of code.
* [plow](https://github.com/six-ddc/plow) - Plow is a HTTP(S) benchmarking tool, written in Golang. It uses fasthttp instead of Go's default net/http due to its lightning fast performance. Plow runs at a specified connections concurrently and real-time records a summary statistics, histogram of execution time and calculates percentiles to display on Web UI and terminal. It can run for a set duration, for a fixed number of requests or until Ctrl-C interrupted.
* [oha](https://github.com/hatoo/oha) - oha is a tiny program that sends some load to a web application and show realtime tui inspired by rakyll/hey. This program is written in Rust and powered by tokio and beautiful tui by tui-rs.
* [hyperfine](https://github.com/sharkdp/hyperfine) - A command-line benchmarking tool. It supports statistical analysis across multiple runs and support for arbitrary shell commands.
* [drill](https://github.com/fcsonline/drill) - Drill is a HTTP load testing application written in Rust. The main goal for this project is to build a really lightweight tool as alternative to other that require JVM and other stuff. You can write benchmark files, in YAML format, describing all the stuff you want to test.
* [h2load](https://nghttp2.org/documentation/h2load-howto.html) - h2load(1) is benchmarking tool for HTTP/2 and HTTP/1.1. It supports SSL/TLS and clear text for all supported protocols.
* [bombardier](https://github.com/codesenberg/bombardier) - bombardier is a HTTP(S) benchmarking tool. It is written in Go programming language and uses excellent fasthttp instead of Go's default http library, because of its lightning fast performance.
* [cassowary](https://github.com/rogerwelin/cassowary) - Cassowary is a modern HTTP/S, intuitive & cross-platform load testing tool built in Go for developers, testers and sysadmins. Cassowary draws inspiration from awesome projects like k6, ab & httpstat.
* [slowhttptest](https://github.com/shekyan/slowhttptest) - SlowHTTPTest is a highly configurable tool that simulates some Application Layer Denial of Service attacks by prolonging HTTP connections in different ways. Use it to test your web server for DoS vulnerabilites, or just to figure out how many concurrent connections it can handl
* [autocannon](https://github.com/mcollina/autocannon) - An HTTP/1.1 benchmarking tool written in node, greatly inspired by wrk and wrk2, with support for HTTP pipelining and HTTPS. On my box, autocannon can produce more load than wrk and wrk2, see limitations for more details.
* [vegeta](https://github.com/tsenart/vegeta) - Vegeta is a versatile HTTP load testing tool built out of a need to drill HTTP services with a constant request rate.