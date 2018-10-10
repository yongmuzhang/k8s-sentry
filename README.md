# k8s-sentry
把sentry部署到kubernetes集群

kubectl create -d sentry-pgdb.yml
kubectl create -d sentry-redis.yml
kubectl create -d sentry-web.yml
kubectl create -d sentry-worker.yml
kubectl create -d sentry-cron.yml
kubectl create -d sentry-init.yml
