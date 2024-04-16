# Hawkes-Knowledge: Exploring the Dynamics of Hawkes Processes

This repository provides an overview of papers on Hawkes processes, tailored primarily for researchers. Our aim is to categorize papers into different applications, provide links to official and unofficial code resources, and explore the general properties of Hawkes processes.

Currently, the repository is incomplete. For those with limited knowledge about stochastic processes and Hawkes processes, we highly recommend starting with Laub et al. [4] or Rizoiu et al. [5] to familiarize yourself with the basics before delving into the original papers [1, 2, 3].
<!-- All references are formatted in APA style. -->

## Original Papers
- [1] Hawkes, A. G. (1971). [Spectra of some self-exciting and mutually exciting point processes](https://doi.org/10.2307/2334319). _Biometrika_, 58(1), 83-90.
- [2] Hawkes, A. G. (1971). [Point spectra of some mutually exciting point processes](https://doi.org/10.1111/j.2517-6161.1971.tb01530.x). _Journal of the Royal Statistical Society Series B: Statistical Methodology_, 33(3), 438-443.
- [3] Hawkes, A. G., & Oakes, D. (1974). [A cluster process representation of a self-exciting process](https://doi.org/10.2307/3212693). _Journal of Applied Probability_, 11(3), 493-503.

## Books & Book Chapters
- [4] Laub, P. J., Lee, Y., & Taimre, T. (2021). [_The elements of Hawkes processes_](https://doi.org/10.1007/978-3-030-84639-8). New York: Springer. [\[Code\]](https://github.com/Pat-Laub/hawkesbook)
- [5] Rizoiu, M. A., Lee, Y., Mishra, S., & Xie, L. (2017). [Hawkes processes for events in social media](https://doi.org/10.1145/3122865.3122874). In _Frontiers of multimedia research_ (pp. 191-218).

## Literature Reviews
- Overview of Hawkes processes:
  - [6] Lima, R. (2023). [Hawkes processes modeling, inference, and control: An overview](https://doi.org/10.1137/21M1396927). _SIAM Review_, 65(2), 331-374.
- Review with a focus on spatio-temporal processes:
  - [7] Reinhart, A. (2018). [A review of self-exciting spatio-temporal point processes and their applications](https://doi.org/10.1214/17-STS629). _Statistical Science_, 33(3), 299-318.
- Reviews with a focus on financial applications:
  - [8] Bacry, E., Mastromatteo, I., & Muzy, J. F. (2015). [Hawkes processes in finance](https://doi.org/10.1142/S2382626615500057). Market Microstructure and Liquidity, 1(01), 1550005.
  - [9] Hawkes, A. G. (2018). [Hawkes processes and their applications to finance: A review](https://doi.org/10.1080/14697688.2017.1403131). _Quantitative Finance_, 18(2), 193-198.
  - [10] Hawkes, A. G. (2022). [Hawkes jump-diffusions and finance: A brief history and review](https://doi.org/10.1080/1351847X.2020.1755712). _European Journal of Finance_, 28(7), 627-641.
- Review on neural Hawkes processes:
  - [11] Shchur, O., T ̈urkmen, A. C., Januschowski, T., & G ̈unnemann, S. (2021). [Neural temporal point processes: A review](https://doi.org/10.24963/ijcai.2021/623). In _Proceedings of the 30th International Joint Conference on Artificial Intelligence_ (pp. 4585–4593).

## Simulation
- [12] Ogata, Y. (1981). [On Lewis' simulation method for point processes](https://doi.org/10.1109/TIT.1981.1056305). _IEEE Transactions on Information Theory_, 27(1), 23-31.

## Statistical Inference
- Maximimum-likelihood estimation (MLE)
  - Ogata, Y. (1978). [The asymptotic behaviour of maximum likelihood estimators for stationary point processes](https://doi.org/10.1007/BF02480216). Ann. Inst. Statist. Math, 30, 243-261
- Expectation maximization (EM)
  - ... 
  - [13] Mark, M., & Weber, T. A. (2020). [Robust identification of controlled Hawkes processes](https://doi.org/10.1103/PhysRevE.101.043305). Physical Review E, 101(4), 043305.
- Non-parametric estimation:
  - [14] Bacry, E., & Muzy, J. F. (2016). [First-and second-order statistics characterization of Hawkes processes and non-parametric estimation](https://doi.org/10.1109/TIT.2016.2533397). _IEEE Transactions on Information Theory_, 62(4), 2184-2202.
  - [15] Kirchner, M. (2017). [An estimation procedure for the Hawkes process](https://doi.org/10.1080/14697688.2016.1211312). _Quantitative Finance_, 17(4), 571-595.
  - [16] Achab, M., Bacry, E., Gaïffas, S., Mastromatteo, I., & Muzy, J. F. (2017). [Uncovering causality from multivariate Hawkes integrated cumulants](https://proceedings.mlr.press/v70/achab17a.html). In _Proceedings of the 34th International Conference on Machine Learning_, PMLR 70:1-10. [\[Code\]](https://github.com/achab/nphc)

- ...

## Neural Hawkes processes
- [17] Mei, H., & Eisner, J. M. (2017). [The neural Hawkes process: A neurally self-modulating multivariate point process](https://proceedings.neurips.cc/paper_files/paper/2017/hash/6463c88460bd63bbe256e495c63aa40b-Abstract.html). _Advances in Neural Information Processing Systems_, 30.
- [18] Du, N., Dai, H., Trivedi, R., Upadhyay, U., Gomez-Rodriguez, M., & Song, L. (2016). [Recurrent marked temporal point processes: Embedding event history to vector](https://doi.org/10.1145/2939672.2939875). In _Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining_ (pp. 1555-1564). [\[Code\]](https://github.com/dunan/NeuralPointProcess)
- [19] Zuo, S., Jiang, H., Li, Z., Zhao, T., & Zha, H. (2020). [Transformer Hawkes process](https://proceedings.mlr.press/v119/zuo20a.html). In _Proceedings of the 37th International Conference on Machine Learning_, PMLR 119:11692-11702. [\[Code\]](https://github.com/SimiaoZuo/Transformer-Hawkes-Process)

## Applications
- Earthquake modeling:
  - [20] Ogata, Y. (1988). [Statistical models for earthquake occurrences and residual analysis for point processes](https://doi.org/10.1080/01621459.1988.10478560). _Journal of the American Statistical Association_, 83(401), 9-27.
- Social media:
  - [21] Zhao, Q., Erdogdu, M. A., He, H. Y., Rajaraman, A., & Leskovec, J. (2015). [SEISMIC: A self-exciting point process model for predicting tweet popularity](https://doi.org/10.1145/2783258.2783401). In _Proceedings of the 21th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining_ (pp. 1513-1522). [\[Code\]](https://cran.r-project.org/web/packages/seismic/)
  - [22] Rizoiu, M. A., Xie, L., Sanner, S., Cebrian, M., Yu, H., & Van Hentenryck, P. (2017). [Expecting to be hip: Hawkes intensity processes for social media popularity](https://doi.org/10.1145/3038912.3052650). In _Proceedings of the 26th International Conference on World Wide Web_ (pp. 735-744).[\[Code\]](https://github.com/andrei-rizoiu/hip-popularity)
  - [23] Schneider, P. J., & Rizoiu, M. A. (2023). [The effectiveness of moderating harmful online content](https://doi.org/10.1073/pnas.2307360120). _Proceedings of the National Academy of Sciences_, 120(34), e2307360120. [\[Code\]](https://github.com/behavioral-ds/harmful-content-moderation)
- Criminology:
  - [24] Mohler, G. O., Short, M. B., Brantingham, P. J., Schoenberg, F. P., & Tita, G. E. (2011). [Self-exciting point process modeling of crime](https://doi.org/10.1198/jasa.2011.ap09546). _Journal of the American Statistical Association_, 106(493), 100-108.
- Finance:
  - [25] Aït-Sahalia, Y., Cacho-Diaz, J., & Laeven, R. J. (2015). [Modeling financial contagion using mutually exciting jump processes](https://doi.org/10.1016/j.jfineco.2015.03.002). _Journal of Financial Economics_, 117(3), 585-606.
  - [26] Rambaldi, M., Pennesi, P., & Lillo, F. (2015). [Modeling foreign exchange market activity around macroeconomic news: Hawkes-process approach](https://doi.org/10.1103/PhysRevE.91.012819). _Physical Review E_, 91(1), 012819.
  - [27] Mark, M., Sila, J., & Weber, T. A. (2022). [Quantifying endogeneity of cryptocurrency markets](https://doi.org/10.1080/1351847X.2020.1791925). _European Journal of Finance_, 28(7), 784-799.
- Epidemiology:
  - [28] Rizoiu, M. A., Mishra, S., Kong, Q., Carman, M., & Xie, L. (2018). [SIR-Hawkes: Linking epidemic models and Hawkes processes to model diffusions in finite populations](https://doi.org/10.1145/3178876.3186108). In _Proceedings of the 2018 World Wide Web Conference_ (pp. 419-428). [\[Code\]](https://github.com/computationalmedia/sir-hawkes)
  - [29] Bertozzi, A. L., Franco, E., Mohler, G., Short, M. B., & Sledge, D. (2020). [The challenges of modeling and forecasting the spread of COVID-19](https://doi.org/10.1073/pnas.2006520117). _Proceedings of the National Academy of Sciences_, 117(29), 16732-16738. [\[Code\]](https://github.com/gomohler/pnas2020)
