# cali-text

Daily 9 AM hype text pipeline.

Every morning an automated job composes a message — a short over-the-top
compliment paragraph, the day's Ann Arbor MI weather, and a description of
Trisha Paytas's most recent TikTok — and commits it to `today.txt` on `main`.

At 9:00 AM ET an iPhone Shortcuts personal automation fetches the raw file

    https://raw.githubusercontent.com/morganzietz/cali-text/main/today.txt

and auto-sends its contents as an iMessage. The recipient's phone number
lives only in the Shortcut on the phone — never in this repo.

`message-spec.md` is the style guide the daily job follows.
