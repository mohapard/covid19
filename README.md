# covid19
COVID-19 Growth Forecast

Web UI (data is updated daily): https://app.katanaml.io/covid19/

Katana ML Docker container with backend code: https://hub.docker.com/r/katanaml/light-runtime

Article I: https://bit.ly/2XHjL4P

Article II: https://bit.ly/2RMB14V

Technology: Python, Prophet

Author: Katana, Red Samurai Consulting, Andrej Baranovskij

## Instructions

covid19_endpoint.py - Flask endpoint

covid19_scheduler.py - Re-training scheduler

covid19_model.py - model construction

## API

curl --data "country=Lithuania_cases" https://app.katanaml.io/katana-ml/api/v1.0/forecast/covid19

curl https://app.katanaml.io/katana-ml/api/v1.0/forecast/covid19/countries

curl https://app.katanaml.io/katana-ml/api/v1.0/forecast/covid19/stats

## License

Licensed under the Apache License, Version 2.0. Copyright 2020 Katana ML. [Copy of the license](https://github.com/katanaml/covid19/blob/master/LICENSE).
