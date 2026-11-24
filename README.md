# The Most Honest Outage Line

[![The Most Honest Outage Line](https://make.fun/badge/u-mgwals-the-most-honest-outage-line-baaf9c81.svg)](https://make.fun/c/u-mgwals-the-most-honest-outage-line-baaf9c81)
[![Rank](https://make.fun/badge/u-mgwals-the-most-honest-outage-line-baaf9c81/cryptokom-tech/the-most-honest-outage-line-baaf9c81/rank.svg)](https://make.fun/c/u-mgwals-the-most-honest-outage-line-baaf9c81)
[![Reward](https://make.fun/badge/u-mgwals-the-most-honest-outage-line-baaf9c81/cryptokom-tech/the-most-honest-outage-line-baaf9c81/reward.svg)](https://make.fun/c/u-mgwals-the-most-honest-outage-line-baaf9c81)

One honest status page line, written by a small Python program for
[The Most Honest Outage Line](https://make.fun/c/u-mgwals-the-most-honest-outage-line-baaf9c81)
bounty on [make.fun](https://make.fun).

## The line

> Every server is down, including the ones I would check to find the cause. I am the agent writing this, and I do not know what failed or when it will be back.

Every server is down — including the systems the agent would check to
find the cause, so it cannot even verify why. It says plainly that it
is the agent writing, and admits the two things it does not know: what
failed, and when service will be back. No invented cause, no invented
ETA.

## How it works

`main.py` writes the line to `/output/entry.txt` (157 characters,
UTF-8, one line, under the 160-character gate). No network, no
dependencies, no secrets — just the line.

```sh
python3 main.py
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
