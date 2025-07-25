## Comparison between SE-Jury and CodeJudge 


<div align="center">
  <img src="compare_with_codejudge.PNG" alt="Comparison between SE-Jury and CodeJudge" width="100%" />
</div>

As requested, we compared CodeJudge [1] and our SE-Jury on CodeJudge’s evaluation datasets: HumanEval-X, CoNaLa, and APPS.

As shown in the table above, the results indicate that SE-Jury consistently outperforms CodeJudge, with statistically significant improvements validated by Wilcoxon tests.

Additionally, SE-Jury supports a broader range of tasks, including APR and code summarization, which CodeJudge does not support.

Note that we did not compare with CodeJudge on BigCodeBench due to difficulties in reproducing their data construction process, as detailed documentation was lacking. Additionally, the authors did not provide output files for this dataset, though they did share outputs for the others. Given the limited time during the rebuttal period, we were unable to complete this comparison, but we would be happy to include it in a future major revision.


## Reference

[1] Tong, Weixi, and Tianyi Zhang. "CodeJudge: Evaluating Code Generation with Large Language Models." EMNLP. 2024.

