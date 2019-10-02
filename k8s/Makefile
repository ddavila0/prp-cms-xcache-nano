.PHONY: configmap

configmap:
	-kubectl delete configmap cms-xcache-nano -n osg
	kubectl create configmap cms-xcache-nano -n osg \
		--from-file=90-node-xcache-disks.cfg --from-file=95-local-ucsd.cfg --from-file=00-create-dirs.sh 
