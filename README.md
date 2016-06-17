# varnish4-freebsd

sysctl.conf

https://www.varnish-cache.org/trac/wiki/Performance
```
kern.ipc.nmbclusters=65536 (126184)
kern.ipc.somaxconn=16384 (128 kern.ipc.soacceptqueue)
kern.maxfiles=131072 (261364)
kern.maxfilesperproc=104856 (235224)
kern.threads.max_threads_per_proc=4096 (1500)

kern.ipc.maxsockets="131072" (261365)
kern.ipc.maxpipekva="104857600" (133816320)
```
