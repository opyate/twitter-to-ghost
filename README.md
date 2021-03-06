# Twitter to Ghost

Upload all your Tweets to Ghost.

# Steps

# Dependencies

    pip install -r requirements.txt

## Download

Download your Twitter archive from [the account page](https://twitter.com/settings/account) by clicking on *Request your archive*

![request your archive](tweetarchive.png)

[Mine](https://twitter.com/opyate) is [included](tweets/) as an example. (I clearly never had anything interesting to say, but hey.)

## Unzip

Unzip your archive. Call the resulting directory `tweets` or modify the code to suit.

## Make
Run `make` and it will spit out `out.json`.

## Import

Go to Ghost Labs admin menu, and import `out.json`

![Ghost import](ghostimport.png)

## Enjoy

Sit back and enjoy your jabberings off-silo, and perhaps start referring to them as *chirps*. [Here's mine.](http://www.opyate.com/tag/noise/)

Remember &mdash; [IndieWeb FTW](https://indieweb.org/).

# Caveats

I've hard-coded two tags, but you should modify this. Please send me a PR to make this bit of the tool configurable.
