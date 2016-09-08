web: gunicorn eventkit_cloud.wsgi --log-level=debug --logger-class=simple -b 0.0.0.0:$PORT
mapproxy: mapproxy-seed --concurrency=5 -f mapproxy.yaml -s seed.yaml --seed ALL
