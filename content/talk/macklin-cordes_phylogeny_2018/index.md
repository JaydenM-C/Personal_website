+++
title = "Phylogeny in phonotactics: A multivariate approach for stronger historical signal"
date = 2017-01-01T00:00:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2018-12-10T00:00:00
# time_end = 2030-06-01T15:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jayden L. Macklin-Cordes", "Erich R. Round"]

# Abstract and optional shortened version.
abstract = "Computational methods continue to rise in comparative fields of linguistics, historical and synchronic. However, there has been less development of the kinds of data used with these methods. Computational phylogenetic studies (e.g. Bouckaert, Bowern, and Atkinson 2018; Kolipakam et al. 2018) tend to rely on lexical data consisting of expert, manually-coded cognate judgements. This is a rate-determining step and a barrier where language documentation is limited (notwithstanding progress by List et al. 2018). \n \n Phylogenetic comparative methods can be used to identify and quantify historical patterns in comparative datasets. It is possible to empirically test whether novel kinds of linguistic data accord with known phylogenetic histories of languages (phylogenetic signal) and therefore contain information of interest to historical linguistic inquiry. Recent work (Macklin-Cordes, Round & Bowern, submitted) considers statistical phonotactic data using this approach. Phylogenetic signal is found in variables coding the frequencies of transitions from segment $x$ to segment $y$ in the sequence $xy$ relativized over all instances of $x$, extracted from wordlists and compared to an independent reference phylogeny inferred using lexical cognate data. In addition, a higher degree of phylogenetic signal is found in relative frequencies of transitions between natural sound classes. There are two limitations, however: (1) Statistics for quantifying phylogenetic signal require large datasets, becoming unstable with fewer than 40 languages. (2) Phylogenetic signal is quantified for each variable individually, which does not directly test the question of whether a language’s overall phonotactic system contains historical information more generally. \n \n In this study, we address both limitations by estimating the level of phylogenetic signal for whole phonotactic datasets using a multivariate version of the $K$ statistic (Blomberg, Garland, and Ives 2003), $K{mult}$ (Adams 2014). This method collapses a multivariate dataset into a matrix of Euclidean distances between languages and compares those distances to the phylogenetic distances between languages in a reference tree. We calculate distances between 113 Pama-Nyungan wordlists from a dataset of 1,738 variables coding transition frequencies between phonological segments and find $K{mult}=0.54$, which is statistically significant, outperforming all 10,000 random permutations of the dataset (Fig. 1). $K{mult}=0.72$ for a dataset of 389 variables coding frequency transitions between natural sound classes (Fig. 2). We detect a greater degree of phylogenetic signal by jointly estimating $K{mult}$ for all variables—comparing distances between the statistical phonotactics of languages overall—rather than estimating $K$ for each variable individually. This is despite the presence of variables with many NA or zero values creating noise. Further, phylogenetic signal remains high in samples of as few as 10 languages. \n \n We demonstrate how a high degree of historical information is recoverable from phonotactics, even in cases of dataset sparsity and small language sample sizes. This is achievable by statistically modeling a whole sets of data from each language rather than analyzing single variables at a time. Our results open the possibility of incorporating a novel data source in areas of historical linguistic inquiry where uncertainty exists or linguistic documentation is limited."
abstract_short = "The phonotactics roadshow makes its Adelaide debut."

# Name of event and optional event URL.
event = "Australian Linguistics Society Conference 2018"
event_url = "https://als.asn.au/Conference/Conference-2018/Conference-2018"

# Location of event.
location = "University of South Australia, Adelaide"

# Is this a selected talk? (true/false)
selected = true

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["internal-project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Linguistic phylogenetics", "Phylogenetic signal", "Phylogenetic comparative methods", "Historical linguistics", "Pama-Nyungan", "ALS"]

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  # caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  # focal_point = "Right"
+++

{{< figure src="fig1.png" title="Figure 1" caption="$Kmult$ for biphone transition frequency dataset. Observed $Kmult$ is indicated by the arrow. $Kmult$ for random permutations of the dataset are plotted as a histogram." >}}

{{< figure src="fig2.png" title="Figure 2" caption="$Kmult$ for sound class transition frequency dataset." >}}

**References**

Adams, Dean C. 2014. “A Generalized K Statistic for Estimating Phylogenetic Signal from Shape and Other High-Dimensional Multivariate Data.” Systematic Biology 63 (5): 685–97. doi:10.1093/sysbio/syu030.

Blomberg, Simon P., Theodore Garland, and Anthony R. Ives. 2003. “Testing for Phylogenetic Signal in Comparative Data: Behavioral Traits Are More Labile.” Evolution 57 (4): 717–45. http://onlinelibrary.wiley.com/doi/10.1111/j.0014-3820.2003.tb00285.x/abstract.

Bouckaert, Remco R., Claire Bowern, and Quentin D. Atkinson. 2018. “The Origin and Expansion of Pama–Nyungan Languages Across Australia.” Nature Ecology & Evolution 2 (4): 741–49. doi:10.1038/s41559-018-0489-3.

Kolipakam, Vishnupriya, Fiona M. Jordan, Michael Dunn, Simon J. Greenhill, Remco R. Bouckaert, Russell D. Gray, and Annemarie Verkerk. 2018. “A Bayesian Phylogenetic Study of the Dravidian Language Family.” Royal Society Open Science 5 (3): 171504. doi:10.1098/rsos.171504.

List, Johann-Mattis, Mary Walworth, Simon J. Greenhill, Tiago Tresoldi, and Robert Forkel. 2018. “Sequence Comparison in Computational Historical Linguistics.” Journal of Language Evolution lzy006. doi:10.1093/jole/lzy006.
