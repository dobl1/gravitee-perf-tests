# gravitee-perf-tests

To run the k6 test:

    docker-compose -p gio-apim-perf-test up -d influxdb grafana

    docker-compose -p gio-apim-perf-test run -v $PWD/scenarios:/scenarios k6 run /scenarios/test.js
