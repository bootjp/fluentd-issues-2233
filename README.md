# fluentd-issues-2233

## how to use

```bash
git clone git@github.com:bootjp/fluentd-issues-2233.git
docker-compose up
```

```
forwarder_1   | 2018-12-17 07:21:29 +0000 [debug]: #0 fluent/log.rb:302:debug: checking pong
forwarder_1   | 2018-12-17 07:21:29 +0000 [debug]: #0 fluent/log.rb:302:debug: connection established host="host.docker.internal" port=24284
aggregator_1  | 2018-12-17 07:21:29 +0000 [debug]: plugin/input_session.rb:122:on_read: on_read
aggregator_1  | 2018-12-17 07:21:29 +0000 dummy_log: {"count":174}
aggregator_1  | 2018-12-17 07:21:29 +0000 dummy_log: {"count":175}
aggregator_1  | 2018-12-17 07:21:29 +0000 dummy_log: {"count":176}
aggregator_1  | 2018-12-17 07:21:29 +0000 dummy_log: {"count":177}
aggregator_1  | 2018-12-17 07:21:29 +0000 dummy_log: {"count":178}
aggregator_1  | 2018-12-17 07:21:29 +0000 dummy_log: {"count":179}
aggregator_1  | 2018-12-17 07:21:29 +0000 dummy_log: {"count":180}
aggregator_1  | 2018-12-17 07:21:29 +0000 dummy_log: {"count":181}
aggregator_1  | 2018-12-17 07:21:29 +0000 dummy_log: {"count":182}
aggregator_1  | 2018-12-17 07:21:29 +0000 dummy_log: {"count":183}
aggregator_1  | 2018-12-17 07:21:29 +0000 dummy_log: {"count":184}
aggregator_1  | 2018-12-17 07:21:29 +0000 [debug]: plugin/input_session.rb:148:start: starting server
aggregator_1  | 2018-12-17 07:21:29 +0000 [debug]: plugin/input_session.rb:63:generate_helo: generating helo
aggregator_1  | 2018-12-17 07:21:29 +0000 [debug]: plugin/input_session.rb:192:rescue in block in start: Connection closed from '172.18.0.1'(172.18.0.1)
aggregator_1  | 2018-12-17 07:21:29 +0000 [debug]: plugin/input_session.rb:201:start: Shutting down 172.18.0.1:47100
aggregator_1  | 2018-12-17 07:21:29 +0000 [debug]: plugin/input_session.rb:207:shutdown: Shutdown called
aggregator_1  | 2018-12-17 07:21:30 +0000 [debug]: plugin/input_session.rb:148:start: starting server
aggregator_1  | 2018-12-17 07:21:30 +0000 [debug]: plugin/input_session.rb:63:generate_helo: generating helo
forwarder_1   | 2018-12-17 07:21:30 +0000 [debug]: #0 fluent/log.rb:302:debug: checking helo
forwarder_1   | 2018-12-17 07:21:30 +0000 [debug]: #0 fluent/log.rb:302:debug: generating ping
forwarder_1   | 2018-12-17 07:21:30 +0000 [debug]: #0 fluent/log.rb:302:debug: Created new chunk chunk_id="57d32a13765d9422f501bd9d978940c2" metadata=#<struct Fluent::Plugin::Buffer::Metadata timekey=nil, tag="fluent.debug", variables=nil>
aggregator_1  | 2018-12-17 07:21:30 +0000 [debug]: plugin/input_session.rb:122:on_read: on_read
aggregator_1  | 2018-12-17 07:21:30 +0000 [debug]: plugin/input_session.rb:69:check_ping: checking ping
aggregator_1  | 2018-12-17 07:21:30 +0000 [debug]: plugin/input_session.rb:105:generate_pong: generating pong
aggregator_1  | 2018-12-17 07:21:30 +0000 [debug]: plugin/input_session.rb:137:on_read: connection established
forwarder_1   | 2018-12-17 07:21:30 +0000 [debug]: #0 fluent/log.rb:302:debug: checking pong
forwarder_1   | 2018-12-17 07:21:30 +0000 [debug]: #0 fluent/log.rb:302:debug: connection established host="host.docker.internal" port=24284
aggregator_1  | 2018-12-17 07:21:30 +0000 [debug]: plugin/input_session.rb:122:on_read: on_read
aggregator_1  | 2018-12-17 07:21:30 +0000 [debug]: plugin/input_session.rb:148:start: starting server
aggregator_1  | 2018-12-17 07:21:30 +0000 [debug]: plugin/input_session.rb:63:generate_helo: generating helo
aggregator_1  | 2018-12-17 07:21:30 +0000 [debug]: plugin/input_session.rb:192:rescue in block in start: Connection closed from '172.18.0.1'(172.18.0.1)
aggregator_1  | 2018-12-17 07:21:30 +0000 [debug]: plugin/input_session.rb:201:start: Shutting down 172.18.0.1:47108
aggregator_1  | 2018-12-17 07:21:30 +0000 [debug]: plugin/input_session.rb:207:shutdown: Shutdown called
aggregator_1  | 2018-12-17 07:21:31 +0000 [debug]: plugin/input_session.rb:148:start: starting server
aggregator_1  | 2018-12-17 07:21:31 +0000 [debug]: plugin/input_session.rb:63:generate_helo: generating helo
aggregator_1  | 2018-12-17 07:21:32 +0000 [debug]: plugin/input_session.rb:192:rescue in block in start: Connection closed from '172.18.0.1'(172.18.0.1)
aggregator_1  | 2018-12-17 07:21:32 +0000 [debug]: plugin/input_session.rb:201:start: Shutting down 172.18.0.1:47112
aggregator_1  | 2018-12-17 07:21:32 +0000 [debug]: plugin/input_session.rb:207:shutdown: Shutdown called
aggregator_1  | 2018-12-17 07:21:32 +0000 [debug]: plugin/input_session.rb:148:start: starting server
aggregator_1  | 2018-12-17 07:21:32 +0000 [debug]: plugin/input_session.rb:63:generate_helo: generating helo
aggregator_1  | 2018-12-17 07:21:32 +0000 [debug]: plugin/input_session.rb:192:rescue in block in start: Connection closed from '172.18.0.1'(172.18.0.1)
aggregator_1  | 2018-12-17 07:21:32 +0000 [debug]: plugin/input_session.rb:201:start: Shutting down 172.18.0.1:47116
aggregator_1  | 2018-12-17 07:21:32 +0000 [debug]: plugin/input_session.rb:207:shutdown: Shutdown called
aggregator_1  | 2018-12-17 07:21:33 +0000 [debug]: plugin/input_session.rb:148:start: starting server
aggregator_1  | 2018-12-17 07:21:33 +0000 [debug]: plugin/input_session.rb:63:generate_helo: generating helo
aggregator_1  | 2018-12-17 07:21:33 +0000 [debug]: plugin/input_session.rb:192:rescue in block in start: Connection closed from '172.18.0.1'(172.18.0.1)
aggregator_1  | 2018-12-17 07:21:33 +0000 [debug]: plugin/input_session.rb:201:start: Shutting down 172.18.0.1:47120
aggregator_1  | 2018-12-17 07:21:33 +0000 [debug]: plugin/input_session.rb:207:shutdown: Shutdown called
forwarder_1   | 2018-12-17 07:21:34 +0000 [warn]: #0 fluent/log.rb:342:warn: no response from node. regard it as unavailable. host="host.docker.internal" port=24284
forwarder_1   | 2018-12-17 07:21:34 +0000 [debug]: #0 fluent/log.rb:302:debug: Created new chunk chunk_id="57d32a17d1cf9233ccb638ae4ebbbe74" metadata=#<struct Fluent::Plugin::Buffer::Metadata timekey=nil, tag="fluent.warn", variables=nil>
forwarder_1   | 2018-12-17 07:21:34 +0000 [debug]: #0 fluent/log.rb:302:debug: taking back chunk for errors. chunk="57d328f6f00f4803a9486c66636221da"
forwarder_1   | 2018-12-17 07:21:34 +0000 [warn]: #0 fluent/log.rb:342:warn: failed to flush the buffer. retry_time=0 next_retry_seconds=2018-12-17 07:21:35 +0000 chunk="57d328f6f00f4803a9486c66636221da" error_class=Fluent::Plugin::ForwardOutput::NoNodesAvailable error="no nodes are available"
forwarder_1   |   2018-12-17 07:21:34 +0000 [warn]: #0 plugin/output.rb:1176:rescue in try_flush: /usr/lib/ruby/gems/2.5.0/gems/fluentd-1.3.1/lib/fluent/plugin/out_forward.rb:333:in `select_a_healthy_node'
forwarder_1   |   2018-12-17 07:21:34 +0000 [warn]: #0 plugin/output.rb:1176:rescue in try_flush: /usr/lib/ruby/gems/2.5.0/gems/fluentd-1.3.1/lib/fluent/plugin/out_forward.rb:305:in `try_write'
forwarder_1   |   2018-12-17 07:21:34 +0000 [warn]: #0 plugin/output.rb:1176:rescue in try_flush: /usr/lib/ruby/gems/2.5.0/gems/fluentd-1.3.1/lib/fluent/plugin/output.rb:1114:in `try_flush'
forwarder_1   |   2018-12-17 07:21:34 +0000 [warn]: #0 plugin/output.rb:1176:rescue in try_flush: /usr/lib/ruby/gems/2.5.0/gems/fluentd-1.3.1/lib/fluent/plugin/output.rb:1423:in `flush_thread_run'
forwarder_1   |   2018-12-17 07:21:34 +0000 [warn]: #0 plugin/output.rb:1176:rescue in try_flush: /usr/lib/ruby/gems/2.5.0/gems/fluentd-1.3.1/lib/fluent/plugin/output.rb:452:in `block (2 levels) in start'
forwarder_1   |   2018-12-17 07:21:34 +0000 [warn]: #0 plugin/output.rb:1176:rescue in try_flush: /usr/lib/ruby/gems/2.5.0/gems/fluentd-1.3.1/lib/fluent/plugin_helper/thread.rb:78:in `block in thread_create'
aggregator_1  | 2018-12-17 07:21:34 +0000 [debug]: plugin/input_session.rb:148:start: starting server
aggregator_1  | 2018-12-17 07:21:34 +0000 [debug]: plugin/input_session.rb:63:generate_helo: generating helo

…

aggregator_1  | 2018-12-17 07:21:53 +0000 [debug]: plugin/input_session.rb:63:generate_helo: generating helo
forwarder_1   | 2018-12-17 07:21:53 +0000 [debug]: #0 fluent/log.rb:302:debug: checking helo
forwarder_1   | 2018-12-17 07:21:53 +0000 [debug]: #0 fluent/log.rb:302:debug: generating ping
aggregator_1  | 2018-12-17 07:21:53 +0000 [debug]: plugin/input_session.rb:122:on_read: on_read
aggregator_1  | 2018-12-17 07:21:53 +0000 dummy_log: {"count":99}
aggregator_1  | 2018-12-17 07:21:53 +0000 dummy_log: {"count":100}
aggregator_1  | 2018-12-17 07:21:53 +0000 dummy_log: {"count":101}
aggregator_1  | 2018-12-17 07:21:53 +0000 dummy_log: {"count":102}
aggregator_1  | 2018-12-17 07:21:53 +0000 dummy_log: {"count":103}
aggregator_1  | 2018-12-17 07:21:53 +0000 dummy_log: {"count":104}
aggregator_1  | 2018-12-17 07:21:53 +0000 dummy_log: {"count":0}
aggregator_1  | 2018-12-17 07:21:53 +0000 dummy_log: {"count":1}
aggregator_1  | 2018-12-17 07:21:53 +0000 dummy_log: {"count":2}
aggregator_1  | 2018-12-17 07:21:53 +0000 dummy_log: {"count":3}
aggregator_1  | 2018-12-17 07:21:53 +0000 dummy_log: {"count":4}
aggregator_1  | 2018-12-17 07:21:53 +0000 dummy_log: {"count":5}
aggregator_1  | 2018-12-17 07:21:53 +0000 dummy_log: {"count":6}
aggregator_1  | 2018-12-17 07:21:53 +0000 dummy_log: {"count":7}
aggregator_1  | 2018-12-17 07:21:53 +0000 dummy_log: {"count":8}
aggregator_1  | 2018-12-17 07:21:53 +0000 [debug]: plugin/input_session.rb:122:on_read: on_read
aggregator_1  | 2018-12-17 07:21:53 +0000 [debug]: plugin/input_session.rb:69:check_ping: checking ping
aggregator_1  | 2018-12-17 07:21:53 +0000 [debug]: plugin/input_session.rb:105:generate_pong: generating pong
aggregator_1  | 2018-12-17 07:21:53 +0000 [debug]: plugin/input_session.rb:137:on_read: connection established
forwarder_1   | 2018-12-17 07:21:53 +0000 [debug]: #0 fluent/log.rb:302:debug: checking pong
forwarder_1   | 2018-12-17 07:21:53 +0000 [debug]: #0 fluent/log.rb:302:debug: connection established host="host.docker.in
```
