nohup shell bug
=============

I've found a bug in `nohup` that causes whatever shell it's executed from hang up and take 100% of the cpu, if you know any workarounds, please do tell

#### How to execute

```sh
git clone https://github.com/steelbrain/nohup-shell-hanging-bug
cd nohup-shell-hanging-bug
./index.sh &
top
```

After doing that you'll notice a shell process with 100% cpu usage
