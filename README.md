# QTUNA: a Corpus for the Generation of Quantified Statements

The QTuna Dataset, which is detailed in the paper [*Introducing and Analysing QTuna: a Corpus for the Generation of Quantified Statements*](https://www.aclweb.org/anthology/W19-8616/), in the proceeding of 12th International Conference on Natural Language Generation (INLG 2019).

## Introduction

QTUNA is a series of elicitation experiments in which human speakers were asked to perform a linguistic task that invites the use of quantified expressions in order to inform a possible Natural Language Generation algorithms that mimic humans' use of quantified expressions. This work was inspired by a line of work focusing one specific class of noun phrases, i.e., referring expression, where they focus on corpora of referring expressions  that  were  elicited  under  experimentally  controlled  conditions (e.g., [TUNA](https://www.abdn.ac.uk/ncs/departments/computing-science/tuna-318.php) experiment), but aiming  this  time  to  gain  insights into quantified noun phrases.

## Data

#### Scene

The scenes we used for the QTUNA experiements can be dount in the `scenes.pdf`.

#### Raw Data

The plain texts elicitated in the QTUNA experiments can be found in the `raw_data` folder, each of which is in the format of:
```
1	1	1	There are only blue squares.
2	1	2	No circles, half red
3	1	3	Equally devided blue objects
4	1	4	Equal amount of red circles and blue squares
5	1	5	Most of them are squares, all blue

```
where the second and the third colomns are the subject ID and the scene ID respectively.

## Citation

```
@inproceedings{chen-etal-2019-qtuna,
    title = "{QTUNA}: A Corpus for Understanding How Speakers Use Quantification",
    author = "Chen, Guanyi  and
      van Deemter, Kees  and
      Pagliaro, Silvia  and
      Smalbil, Louk  and
      Lin, Chenghua",
    booktitle = "Proceedings of the 12th International Conference on Natural Language Generation",
    month = oct # " - " # nov,
    year = "2019",
    address = "Tokyo, Japan",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/W19-8616",
    pages = "124--129",
}
```
