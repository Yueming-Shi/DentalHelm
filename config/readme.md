// please remove the old configmap before this
kubectl create configmap dental-appconf --from-env-file dental-appconf.configmap
// please remove the old secret before this
kubectl create secret generic dental-appconf --from-env-file dental-appconf.secret
