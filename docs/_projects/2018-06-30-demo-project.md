---
title: 'Stocks in NASDAQ'
subtitle: Streamlit demo
date: 2018-06-30 00:00:00
description: Pulling stock data using API calls and display candlestick visualization with streamlit
featured_image: '/images/demo/candlestick.png'
---

![](/images/demo/candlestick.png)

## Demo description

This demo presents 4 stocks in NASDAQ: AAPL, TSLA, GOOG, and AMZN. Stocks data were pulled using [Polygon API](https://polygon.io/).
API response comes in json and needs to be preprocessed to be a proper dataframe for visualization.

<!-- We've included everything you need to create engaging posts about your work, and show off your case studies in a beautiful way. -->

<!-- **Obviously,** we’ve styled up *all the basic* text formatting options [available in markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). -->

Preprocessing steps can be:

* Recognizing a column as a datetime column
* Grouping each ticker individually and applying a function on them
* Reshaping data to act as an input for [Plotly API](https://plotly.com/), a popular python library for visualization

<!-- You can also add blockquotes, which are shown at a larger width to help break up the layout and draw attention to key parts of your content: -->

<!-- > “Simple can be harder than complex: You have to work hard to get your thinking clean to make it simple. But it’s worth it in the end because once you get there, you can move mountains.” -->

After preprocessing, the dataframe is displayed as follows:

| ticker  | open   | ... | close   | ... | timestamp           |
|---------|--------|-----|---------|-----|---------------------|
| AAPL    | 169.08 | ... | 172.19  | ... | 2022-01-09 00:00:00 |
| AAPL    | 172.32 | ... | 175.08  | ... | 2022-01-10 00:00:00 |
| ...     | ... | ... | ...  | ... | ... |
| AMZN    | 161.84| ... | 171.08  | ... | 2023-01-03 00:00:00 |


<!-- And footnotes[^1], which link to explanations[^2] at the bottom of the page[^3].

[^1]: Beautiful modern, minimal theme design.
[^2]: Powerful features to show off your work.
[^3]: Maintained and supported by the theme developer.

You can throw in some horizontal rules too: -->

---
