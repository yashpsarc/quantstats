# quantstats
 portfolio analytics with python
Creating a report

You can create 7 different report tearsheets:

    qs.reports.metrics(mode='basic|full", ...) - shows basic/full metrics
    qs.reports.plots(mode='basic|full", ...) - shows basic/full plots
    qs.reports.basic(...) - shows basic metrics and plots
    qs.reports.full(...) - shows full metrics and plots
    qs.reports.html(...) - generates a complete report as html

Let' create an html tearsheet

(benchmark can be a pandas Series or ticker)
qs.reports.html(stock, "SPY")

Output will generate something like this:

HTML tearsheet
