# Hawkes-Knowledge: Exploring the Dynamics of Hawkes Processes

This repository provides an overview of papers on Hawkes processes, tailored primarily for researchers. Our aim is to categorize papers into different applications, provide links to official and unofficial code resources, and explore the general properties of Hawkes processes.

Currently, the repository is incomplete. For those with limited knowledge about stochastic processes and Hawkes processes, we highly recommend starting with Laub et al. [4] or Rizoiu et al. [5] to familiarize yourself with the basics before delving into the original papers [1, 2, 3].
<!-- All references are formatted in APA style. -->

## Original Papers
- [1] Hawkes, A. G. (1971). [Spectra of some self-exciting and mutually exciting point processes](https://doi.org/10.2307/2334319). _Biometrika_, 58(1), 83-90.
- [2] Hawkes, A. G. (1971). [Point spectra of some mutually exciting point processes](https://doi.org/10.1111/j.2517-6161.1971.tb01530.x). _Journal of the Royal Statistical Society Series B: Statistical Methodology_, 33(3), 438-443.
- [3] Hawkes, A. G., & Oakes, D. (1974). [A cluster process representation of a self-exciting process](https://doi.org/10.2307/3212693). _Journal of Applied Probability_, 11(3), 493-503.

Fascinating insights into the origins of Hawkes processes:
> Hawkes, A., & Chen, J. (2021). [A personal history of Hawkes process](https://orca.cardiff.ac.uk/id/eprint/141988/1/hawkes2021toukeisuuri-1st-submission%5B1%5D.pdf). _Proceedings of the Institute of Statistical Mathematics_ (統計数理), 69(2), 123-143.

## Books & Book Chapters
- [4] Laub, P. J., Lee, Y., & Taimre, T. (2021). [_The elements of Hawkes processes_](https://doi.org/10.1007/978-3-030-84639-8). Springer Cham, Switzerland. [\[Code\]](https://github.com/Pat-Laub/hawkesbook)
- [5] Rizoiu, M. A., Lee, Y., Mishra, S., & Xie, L. (2017). [Hawkes processes for events in social media](https://doi.org/10.1145/3122865.3122874). In _Frontiers of multimedia research_ (pp. 191-218).

For a general introduction into stochastic processes refer to:
- [6] Daley, D. J., & Vere-Jones, D. (2003). [_An introduction to the theory of point processes: Volume I: Elementary theory and methods_](https://doi.org/10.1007/b97277). Springer New York, NY.
- [7] Daley, D. J., & Vere-Jones, D. (2008). [_An introduction to the theory of point processes: Volume II: General theory and structure_](https://doi.org/10.1007/978-0-387-49835-5). Springer New York, NY.

## Literature Reviews
If you're searching for a reference and not interested in reading a book, here are a couple of literature reviews, with most focusing on a selected topic:
- Overview of Hawkes processes:
  - [8] Lima, R. (2023). [Hawkes processes modeling, inference, and control: An overview](https://doi.org/10.1137/21M1396927). _SIAM Review_, 65(2), 331-374.
- Review with a focus on spatio-temporal processes:
  - [9] Reinhart, A. (2018). [A review of self-exciting spatio-temporal point processes and their applications](https://doi.org/10.1214/17-STS629). _Statistical Science_, 33(3), 299-318.
- Reviews with a focus on financial applications:
  - [10] Bacry, E., Mastromatteo, I., & Muzy, J. F. (2015). [Hawkes processes in finance](https://doi.org/10.1142/S2382626615500057). _Market Microstructure and Liquidity_, 1(01), 1550005.
  - [11] Hawkes, A. G. (2018). [Hawkes processes and their applications to finance: A review](https://doi.org/10.1080/14697688.2017.1403131). _Quantitative Finance_, 18(2), 193-198.
  - [12] Hawkes, A. G. (2022). [Hawkes jump-diffusions and finance: A brief history and review](https://doi.org/10.1080/1351847X.2020.1755712). _European Journal of Finance_, 28(7), 627-641.
- Review on neural Hawkes processes:
  - [13] Shchur, O., T ̈urkmen, A. C., Januschowski, T., & G ̈unnemann, S. (2021). [Neural temporal point processes: A review](https://doi.org/10.24963/ijcai.2021/623). In _Proceedings of the 30th International Joint Conference on Artificial Intelligence_ (pp. 4585–4593).

## Theoretical Properties
- [14] Oakes, D. (1975). [The Markovian self-exciting process](https://doi.org/10.2307/3212408). _Journal of Applied Probability_, 12(1), 69-77.
- [15] Brémaud, P., & Massoulié, L. (1996). [Stability of nonlinear Hawkes processes](https://doi.org/10.1214/aop/1065725193). _Annals of Probability_, 24(3), 1563-1588.
- [16] Brémaud, P., Nappo, G., & Torrisi, G. L. (2002). [Rate of convergence to equilibrium of marked Hawkes processes](https://doi.org/10.1239/jap/1019737993). _Journal of Applied Probability_, 39(1), 123-136.
- [17] Zhu, L. (2013). [Central limit theorem for nonlinear Hawkes processes](https://doi.org/10.1239/jap/1378401234). _Journal of Applied Probability_, 50(3), 760-771.
- [18] Jovanović, S., Hertz, J., & Rotter, S. (2015). [Cumulants of Hawkes point processes](https://doi.org/10.1103/PhysRevE.91.042802). _Physical Review E_, 91(4), 042802.
- [19] Cui, L., Hawkes, A., & Yi, H. (2020). [An elementary derivation of moments of Hawkes processes](https://doi.org/10.1017/apr.2019.53). _Advances in Applied Probability_, 52(1), 102-137.
- [20] Daw, A. (2024). [Conditional uniformity and Hawkes processes](https://doi.org/10.1287/moor.2022.1348). _Mathematics of Operations Research_, 49(1), 40-57.

## Libraries
As previously mentioned, the book by Laub et al. [4] contains code snippets, and there are code implementations available in the Python package `hawkesbook`, which serves as an accompanying library to the book. Additionally, notable libraries include `tick`, a Python library mainly focusing on the fast simulation and estimation of Hawkes processes, and the `EasyTPP` library, which serves as a benchmarking tool, particularly for "neural" temporal point processes.
- [21] Bacry, E., Bompaire, M., Deegan, P., Gaïffas, S., & Poulsen, S. V. (2018). [tick: a Python library for statistical learning, with an emphasis on Hawkes processes and time-dependent models](). _Journal of Machine Learning Research_, 18(214), 1-5. [\[Code\]](https://github.com/X-DataInitiative/tick)
- [22] Xue, S., Shi, X., Chu, Z., Wang, Y., Zhou, F., Hao, H., ... & Mei, H. (2024). [EasyTPP: Towards open benchmarking temporal point processes](https://arxiv.org/abs/2307.08097). In _International Conference on Learning Representations_.

## Simulation
- [23] Ogata, Y. (1981). [On Lewis' simulation method for point processes](https://doi.org/10.1109/TIT.1981.1056305). _IEEE Transactions on Information Theory_, 27(1), 23-31.
- [24] Dassios, A., & Zhao, H. (2013). [Exact simulation of Hawkes process with exponentially decaying intensity](https://doi.org/10.1214/ECP.v18-2717). _Electron. Commun. Probab._, 18, 1-13

## Statistical Inference
Fitting Hawkes processes is a notoriously difficult task. The selection of a statistical inference method should always depend on the amount of data at hand, the specific application domain, and the task to be accomplished. General statistical inference methods include the following:
- Maximimum-likelihood estimation (MLE)
  - [25] Ogata, Y. (1978). [The asymptotic behaviour of maximum likelihood estimators for stationary point processes](https://doi.org/10.1007/BF02480216). _Annals of the Institute of Statistical Mathematics_, 30, 243-261
  - [26] Ozaki, T. (1979). [Maximum likelihood estimation of Hawkes' self-exciting point processes](https://doi.org/10.1007/BF02480272). _Annals of the Institute of Statistical Mathematics_, 31, 145-155.
- Expectation maximization (EM)
  - ... 
  - [27] Mark, M., & Weber, T. A. (2020). [Robust identification of controlled Hawkes processes](https://doi.org/10.1103/PhysRevE.101.043305). _Physical Review E_, 101(4), 043305.
- Bayesian
  - [28] Rasmussen, J. G. (2013). [Bayesian inference for Hawkes processes](https://doi.org/10.1007/s11009-011-9272-5). _Methodology and Computing in Applied Probability_, 15, 623-642.
- Non-parametric estimation:
  - [29] Lewis, E., & Mohler, G. (2011). [A nonparametric EM algorithm for multiscale Hawkes processes](https://www.georgemohler.com/_files/ugd/9226cc_89f6c24da28f4fa385b52d52eaffecc1.pdf). Technical Report.
  - [30] Bacry, E., & Muzy, J. F. (2016). [First-and second-order statistics characterization of Hawkes processes and non-parametric estimation](https://doi.org/10.1109/TIT.2016.2533397). _IEEE Transactions on Information Theory_, 62(4), 2184-2202.
  - [31] Kirchner, M. (2017). [An estimation procedure for the Hawkes process](https://doi.org/10.1080/14697688.2016.1211312). _Quantitative Finance_, 17(4), 571-595.
  - [32] Achab, M., Bacry, E., Gaïffas, S., Mastromatteo, I., & Muzy, J. F. (2017). [Uncovering causality from multivariate Hawkes integrated cumulants](https://proceedings.mlr.press/v70/achab17a.html). In _Proceedings of the 34th International Conference on Machine Learning_, PMLR 70:1-10. [\[Code\]](https://github.com/achab/nphc)
- ...

## Neural Hawkes processes
- [33] Mei, H., & Eisner, J. M. (2017). [The neural Hawkes process: A neurally self-modulating multivariate point process](https://proceedings.neurips.cc/paper_files/paper/2017/hash/6463c88460bd63bbe256e495c63aa40b-Abstract.html). _Advances in Neural Information Processing Systems_, 30.
- [34] Du, N., Dai, H., Trivedi, R., Upadhyay, U., Gomez-Rodriguez, M., & Song, L. (2016). [Recurrent marked temporal point processes: Embedding event history to vector](https://doi.org/10.1145/2939672.2939875). In _Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining_ (pp. 1555-1564). [\[Code\]](https://github.com/dunan/NeuralPointProcess)
- [35] Upadhyay, U., De, A., & Gomez Rodriguez, M. (2018). Deep reinforcement learning of marked temporal point processes. _Advances in Neural Information Processing Systems_, 31. [\[Code\]](https://github.com/Networks-Learning/tpprl)
- [36] Zuo, S., Jiang, H., Li, Z., Zhao, T., & Zha, H. (2020). [Transformer Hawkes process](https://proceedings.mlr.press/v119/zuo20a.html). In _Proceedings of the 37th International Conference on Machine Learning_, PMLR 119:11692-11702. [\[Code\]](https://github.com/SimiaoZuo/Transformer-Hawkes-Process)

## Applications
In the following, we aim to highlight the general applicability of Hawkes processes to a plethora of applications. The provided references represent just a hand-selected subset of publications. In the subdirectories, we strive to provide a more comprehensive overview of the significant contributions towards adopting Hawkes processes.
- Earthquake modeling:
  - [37] Ogata, Y. (1988). [Statistical models for earthquake occurrences and residual analysis for point processes](https://doi.org/10.1080/01621459.1988.10478560). _Journal of the American Statistical Association_, 83(401), 9-27.
  - [38] Ogata, Y. (1998). [Space-time point-process models for earthquake occurrences](https://doi.org/10.1023/A:1003403601725). _Annals of the Institute of Statistical Mathematics_, 50, 379-402.
- Social media:
  - [39] Zhao, Q., Erdogdu, M. A., He, H. Y., Rajaraman, A., & Leskovec, J. (2015). [SEISMIC: A self-exciting point process model for predicting tweet popularity](https://doi.org/10.1145/2783258.2783401). In _Proceedings of the 21th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining_ (pp. 1513-1522). [\[Code\]](https://cran.r-project.org/web/packages/seismic/)
  - [40] Rizoiu, M. A., Xie, L., Sanner, S., Cebrian, M., Yu, H., & Van Hentenryck, P. (2017). [Expecting to be hip: Hawkes intensity processes for social media popularity](https://doi.org/10.1145/3038912.3052650). In _Proceedings of the 26th International Conference on World Wide Web_ (pp. 735-744).[\[Code\]](https://github.com/andrei-rizoiu/hip-popularity)
  - [41] Schneider, P. J., & Rizoiu, M. A. (2023). [The effectiveness of moderating harmful online content](https://doi.org/10.1073/pnas.2307360120). _Proceedings of the National Academy of Sciences_, 120(34), e2307360120. [\[Code\]](https://github.com/behavioral-ds/harmful-content-moderation)
- Criminology:
  - [42] Mohler, G. O., Short, M. B., Brantingham, P. J., Schoenberg, F. P., & Tita, G. E. (2011). [Self-exciting point process modeling of crime](https://doi.org/10.1198/jasa.2011.ap09546). _Journal of the American Statistical Association_, 106(493), 100-108.
- Finance:
  - [43] Aït-Sahalia, Y., Cacho-Diaz, J., & Laeven, R. J. (2015). [Modeling financial contagion using mutually exciting jump processes](https://doi.org/10.1016/j.jfineco.2015.03.002). _Journal of Financial Economics_, 117(3), 585-606.
  - [44] Rambaldi, M., Pennesi, P., & Lillo, F. (2015). [Modeling foreign exchange market activity around macroeconomic news: Hawkes-process approach](https://doi.org/10.1103/PhysRevE.91.012819). _Physical Review E_, 91(1), 012819.
  - [45] Mark, M., Sila, J., & Weber, T. A. (2022). [Quantifying endogeneity of cryptocurrency markets](https://doi.org/10.1080/1351847X.2020.1791925). _European Journal of Finance_, 28(7), 784-799.
- Epidemiology: 
  - [46] Rizoiu, M. A., Mishra, S., Kong, Q., Carman, M., & Xie, L. (2018). [SIR-Hawkes: Linking epidemic models and Hawkes processes to model diffusions in finite populations](https://doi.org/10.1145/3178876.3186108). In _Proceedings of the 2018 World Wide Web Conference_ (pp. 419-428). [\[Code\]](https://github.com/computationalmedia/sir-hawkes)
  - [47] Kim, M., Paini, D., & Jurdak, R. (2019). [Modeling stochastic processes in disease spread across a heterogeneous social system](https://doi.org/10.1073/pnas.1801429116). _Proceedings of the National Academy of Sciences_, 116(2), 401-406.
  - [48] Bertozzi, A. L., Franco, E., Mohler, G., Short, M. B., & Sledge, D. (2020). [The challenges of modeling and forecasting the spread of COVID-19](https://doi.org/10.1073/pnas.2006520117). _Proceedings of the National Academy of Sciences_, 117(29), 16732-16738. [\[Code\]](https://github.com/gomohler/pnas2020)
