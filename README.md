# Migrations

A demo of things that can go wrong when doing online migrations in relational databases, and some examples of how to
structure migrations to avoid those pitfalls.

TODO:
1. ~Setup core fakestack infrastructure~
2. Update fakestack (either the docker image or the service) to run migrations at startup
2. ~Add script to stream data to fakestack~
3. ~Setup prometheus container~
4. Setup grafana container talking to Prometheus
5. Setup fakestack with metrics and publish to prometheus
7. Get a great deal of satisfaction out of watching the metrics stream in while streaming data to fakestack
7. Figure out how to initialize a grafana dashboard so that the container is setup correctly by default
8. ~Setup nginx for load balancing~
9. Setup blue/green deployments
10. Setup migration as part of blue/green deployment
11. Write some bad migrations!
12. Add xml deserialization support for the data models so we can load data directly from the official dumps
