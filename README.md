# navio-builder
Simple repo that builds `navio-core` using `guix`

## Usage
```sh
git clone https://github.com/mxaddict/navio-builder.git /navio
cd navio
./build
```

And you can add this to crontab
```sh
* * * * * cd /navio && git fetch && git checkout -f origin/main && ./build >> builds/build.log.txt 2>&1
```
