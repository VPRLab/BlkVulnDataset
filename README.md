# BlkVulnDataset

The public blockchain vulnerability dataset released in our ESEC/FSE'22 paper.

**An Empirical Study of Blockchain System Vulnerabilities: Modules, Types, and Patterns**

Paper link: https://doi.org/10.1145/3540250.3549105

The following is the bib information:

```latex
@INPROCEEDINGS{BLKVULN22,
  AUTHOR = {Xiao Yi and Daoyuan Wu and Lingxiao Jiang and Yuzhou Fang and Kehuan Zhang and Wei Zhang},
  TITLE = {An Empirical Study of Blockchain System Vulnerabilities: Modules, Types, and Patterns},
  BOOKTITLE = {Proc. ACM ESEC/FSE},
  YEAR = {2022},
}
```

## How to Use the DB

- The dataset is a SQLite database file, which is available at [here](https://drive.google.com/file/d/1ntKMt4U4FN6VTi1x-PQw-ZNh1cqKQDLD/view?usp=sharing).
- You can access the dataset db file using the SQLite Browser.
- Then make SQL queries according to your needs.

## The Database Structure

The database contains four tables, i.e., `COMMITS`, `ISSUES`, `VULN_ISSUES`, and `TOP20_VULN_ISSUES`, where 

- `COMMITS` and `ISSUES` contain the raw data of git commits and GitHub issues/PRs, respectively.
- `VULN_ISSUES` contains the vulnerability issues/PRs obtained by the vulnerability filtering framework.
- `TOP20_VULN_ISSUES` contains issues/PRs that belong to the top 20 vulnerability types, as introduced in **Table 5** of the paper.




