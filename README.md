# revenue-and-capacity-calculator

## Install
Initially I didn't want to have any pre-requisites, but I've been using
named parameters which was introduced in Ruby 2.0. Therefore, make sure that
your currently active ruby (`which ruby`) is version 2.0 and above.
(Sorry about that)

```bash
git clone git@github.com:mikeys/revenue-and-capacity-calculator.git
cd revenue-and-capacity-calculator
chmod +x calculate
```

## Run Test Input
```bash
./calculate --file data.csv --date 2000-01
./calculate --file data.csv --date 2018-01
./calculate --file data.csv --date 2013-01
./calculate --file data.csv --date 2014-08
```
