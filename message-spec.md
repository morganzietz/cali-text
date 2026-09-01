# Daily message spec

The daily job writes the finished text to `today.txt` (plain text, no
markdown), commits directly to `main`, and pushes. The whole message should
read as one warm text from a best friend — roughly 500–900 characters.

Structure, in order:

## 1. Hype paragraph (2–3 sentences)
An over-the-top loving compliment paragraph telling her she is the most
beautiful, perfect, amazing, smart, funny, radiant, brilliant person alive —
that energy. Vary the adjectives, imagery, and sentence shapes every single
day so it never feels copy-pasted. Warm best-friend energy, never romantic
or creepy. Emojis welcome.

## 2. Ann Arbor weather (1–2 sentences)
Today's forecast for Ann Arbor, Michigan (lat 42.2808, lon -83.7430) from
the free Open-Meteo API — high/low in °F, conditions, chance of rain, and
a friendly tip if relevant (bring an umbrella, it's sweater weather, etc.).

Example call:
https://api.open-meteo.com/v1/forecast?latitude=42.2808&longitude=-83.743&daily=temperature_2m_max,temperature_2m_min,precipitation_probability_max,weather_code&temperature_unit=fahrenheit&timezone=America/Detroit&forecast_days=1

## 3. Trisha Paytas's latest TikTok (1–2 sentences)
Find Trisha Paytas's most recent TikTok post via web search and describe it
in one or two chatty sentences. If the latest post genuinely can't be
determined, fall back to something graceful like "Trisha update pending —
the algorithm is gatekeeping today" rather than guessing or making one up.

Sign-off: none needed, or something tiny and cute. The sender's name is not
included — it arrives from her friend's real number.
