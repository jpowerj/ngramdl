# ngramdl

R package for downloading Google Ngram Viewer data

1. Make sure you have `devtools` installed (`install.packages("devtools")`) and loaded (`require(devtools)`)
2. Install using `install_github("jpowerj/ngramdl")`
3. Then load using `require(ngramdl)`
4. You can now use `ngram2csv()` to download the data you want: it takes in a list of phrases (first argument) and a filename for the csv (second argument), outputs the csv, and returns the data.frame -- this way you can preview the data right after saving, like:

```R
ngram_data <- ngram2csv(c("phrase1","phrase2"),"ngram_counts.csv")
```

(c) Jeff Jacobs 2020<br>
http://cs.stanford.edu/~jjacobs3