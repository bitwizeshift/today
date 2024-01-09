# What is today's date?

This groundbreaking repository finally answers the day-old question:
"What day is it today?". Finally, no more questions. Just clone this repository,
and `cat` the file `today` to get today's date. Easy!

## 🚀 Features

* [x] Simple and easy to use
* [x] Always available
* [x] The easiest way to get today's date
* [ ] Timezone aware (some day 🤔)
* [x] Available under the [most permissive license](LICENSE) ever

## Why?

Can you think of a better way to tell today's date? No more googling the time;
simply clone this repository and `cat today` to see what the date is -- accurate
to within Eastern Standard Time only (which is the only important time zone).

## How to use

1. Clone this repository

   ```text
   git clone git@github.com:bitwizeshift/today
   cd today
   ```

2. Read the file

   ```text
   $ cat today/today
   2023-03-26
   ```

## ... Okay, but really, why?

This is a cheap and easy way to fill in the Github commit graph while also
playing around with Github automation. Every 24 hours, this repo will open a
[GitHub Issue](issues) for the date being wrong -- which will trigger a Pull
Request creation that automatically fixes the date. Free Github credits!
