# Statistical-analysis-of-2018-Russian-presidential-elections-data

I performed a rough and short analysis of the preliminary results of the Russian presidential elections (March 18th, 2018) in terms of possible election irregularities, making use of the famous libraries like pandas, matplotlib, numpy, seaborn. As data source I used the preliminary results pointed out by podmoskovnik (Sergei Shpilkin) on [his blog](https://translate.google.com/translate?hl=en&sl=ru&tl=en&u=https%3A%2F%2Fpodmoskovnik.livejournal.com%2F178700.html%23comments) as of March 19th, 2018.

When plotting the result in percent for a candidate or party against the voter turnout in percent for every election site, possible irregularities can be visualized as deviations from a 2-dimensional gauss form. A statistical clustering of points near the 100% turnout/100% votes-corner of the diagram for example is regarded as a hint for ballot stuffing (as an appropriate scientific publication, see for example *Statistical detection of systematic election irregularities* by Klimek et. al, PNAS, 2012, [link](http://www.pnas.org/content/109/41/16469)).

My first analysis revealed irregularities not only for the results of the winning candidate Putin Vladimir Vladimirovich, but also for at least one other candidate (Grudinin Pavel Nikolayevich)
