RUN.md

To compile:
```
make MACOSX_DEPLOYMENT_TARGET=10.14
```

To run:
```
./wrk -t2 -d2s -c10 -R10 -s scripts/multiple-endpoints_in_json.lua https://gmail.com:443 -L
```
