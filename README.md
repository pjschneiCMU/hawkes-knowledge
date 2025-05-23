# Hawkes-Knowledge: Exploring the Dynamics of Hawkes Processes

This repository provides an overview of papers on Hawkes processes, tailored primarily for researchers. Our aim is to categorize papers into different applications, provide links to official and unofficial code resources, and explore the general properties of Hawkes processes.

A Hawkes process falls under the umbrella term of temporal point processes, which generally model events occurring randomly over time. While the simplest form of these processes is arguably the homogeneous Poisson process, the Hawkes process distinguishes itself due to its main property of self-excitation. This unique feature enables the process to effectively incorporate the influence of past events, thereby giving it a memory of recent activities. This memory is captured in the conditional intensity function, which adjusts the expected rate of future events based on the occurrence of past events. Originally, this led to the process being referred to as a self-exciting point process.

If this sounds Greek to you, don't worry—we will provide you with some resources to learn more!

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
  - [9] Laub, P. J., Lee, Y., Pollett, P. K., & Taimre, T. (2025). [Hawkes models and their applications](https://doi.org/10.1146/annurev-statistics-112723-034304). _Annual Review of Statistics and Its Application_, 12, 233-258.
- Review with a focus on spatio-temporal processes:
  - [10] Reinhart, A. (2018). [A review of self-exciting spatio-temporal point processes and their applications](https://doi.org/10.1214/17-STS629). _Statistical Science_, 33(3), 299-318.
- Reviews with a focus on financial applications:
  - [11] Bacry, E., Mastromatteo, I., & Muzy, J. F. (2015). [Hawkes processes in finance](https://doi.org/10.1142/S2382626615500057). _Market Microstructure and Liquidity_, 1(01), 1550005.
  - [12] Hawkes, A. G. (2018). [Hawkes processes and their applications to finance: A review](https://doi.org/10.1080/14697688.2017.1403131). _Quantitative Finance_, 18(2), 193-198.
  - [13] Hawkes, A. G. (2022). [Hawkes jump-diffusions and finance: A brief history and review](https://doi.org/10.1080/1351847X.2020.1755712). _European Journal of Finance_, 28(7), 627-641.
- Review on neural Hawkes processes:
  - [14] Shchur, O., T ̈urkmen, A. C., Januschowski, T., & G ̈unnemann, S. (2021). [Neural temporal point processes: A review](https://doi.org/10.24963/ijcai.2021/623). In _Proceedings of the 30th International Joint Conference on Artificial Intelligence_ (pp. 4585–4593).

## Theoretical Properties
- [15] Oakes, D. (1975). [The Markovian self-exciting process](https://doi.org/10.2307/3212408). _Journal of Applied Probability_, 12(1), 69-77.
- [16] Brémaud, P., & Massoulié, L. (1996). [Stability of nonlinear Hawkes processes](https://doi.org/10.1214/aop/1065725193). _Annals of Probability_, 24(3), 1563-1588.
- [17] Brémaud, P., Nappo, G., & Torrisi, G. L. (2002). [Rate of convergence to equilibrium of marked Hawkes processes](https://doi.org/10.1239/jap/1019737993). _Journal of Applied Probability_, 39(1), 123-136.
- [18] Zhu, L. (2013). [Central limit theorem for nonlinear Hawkes processes](https://doi.org/10.1239/jap/1378401234). _Journal of Applied Probability_, 50(3), 760-771.
- [19] Jovanović, S., Hertz, J., & Rotter, S. (2015). [Cumulants of Hawkes point processes](https://doi.org/10.1103/PhysRevE.91.042802). _Physical Review E_, 91(4), 042802.
- [20] Cui, L., Hawkes, A., & Yi, H. (2020). [An elementary derivation of moments of Hawkes processes](https://doi.org/10.1017/apr.2019.53). _Advances in Applied Probability_, 52(1), 102-137.
- [21] Daw, A. (2024). [Conditional uniformity and Hawkes processes](https://doi.org/10.1287/moor.2022.1348). _Mathematics of Operations Research_, 49(1), 40-57.

Properties relevant for queueing theory:
- [22] Daw, A., & Pender, J. (2018). [Queues driven by Hawkes processes](https://doi.org/10.1287/stsy.2018.0014). _Stochastic Systems_, 8(3), 192-229.
- [23] Koops, D. T., Saxena, M., Boxma, O. J., & Mandjes, M. (2018). [Infinite-server queues with Hawkes input](https://doi.org/10.1017/jpr.2018.58). _Journal of Applied Probability_, 55(3), 920-943.
- [24] Chen, X. (2021). [Perfect sampling of Hawkes processes and queues with Hawkes arrivals](https://doi.org/10.1287/stsy.2021.0070). _Stochastic Systems_, 11(13), 264-283.

## Libraries
As previously mentioned, the book by Laub et al. [4] contains code snippets, and there are code implementations available in the Python package `hawkesbook`, which serves as an accompanying library to the book. Additionally, notable libraries include `tick`, a Python library mainly focusing on the fast simulation and estimation of Hawkes processes, and the `EasyTPP` library, which serves as a benchmarking tool, particularly for "neural" temporal point processes.
- [25] Bacry, E., Bompaire, M., Deegan, P., Gaïffas, S., & Poulsen, S. V. (2018). [tick: a Python library for statistical learning, with an emphasis on Hawkes processes and time-dependent models](). _Journal of Machine Learning Research_, 18(214), 1-5. [\[Code\]](https://github.com/X-DataInitiative/tick)
- [26] Xue, S., Shi, X., Chu, Z., Wang, Y., Zhou, F., Hao, H., ... & Mei, H. (2024). [EasyTPP: Towards open benchmarking temporal point processes](https://arxiv.org/abs/2307.08097). In _International Conference on Learning Representations_. [\[Code\]](https://github.com/ant-research/EasyTemporalPointProcess)

## Simulation
- [27] Ogata, Y. (1981). [On Lewis' simulation method for point processes](https://doi.org/10.1109/TIT.1981.1056305). _IEEE Transactions on Information Theory_, 27(1), 23-31.
- [28] Dassios, A., & Zhao, H. (2013). [Exact simulation of Hawkes process with exponentially decaying intensity](https://doi.org/10.1214/ECP.v18-2717). _Electron. Commun. Probab._, 18, 1-13

## Statistical Inference
Fitting Hawkes processes is a notoriously difficult task. The selection of a statistical inference method should always depend on the amount of data at hand, the specific application domain, and the task to be accomplished. General statistical inference methods include the following:
- Maximimum-likelihood estimation (MLE)
  - [29] Ogata, Y. (1978). [The asymptotic behaviour of maximum likelihood estimators for stationary point processes](https://doi.org/10.1007/BF02480216). _Annals of the Institute of Statistical Mathematics_, 30, 243-261
  - [30] Ozaki, T. (1979). [Maximum likelihood estimation of Hawkes' self-exciting point processes](https://doi.org/10.1007/BF02480272). _Annals of the Institute of Statistical Mathematics_, 31, 145-155.
- Expectation maximization (EM)
  - [31] Veen, A., & Schoenberg, F. P. (2008). [Estimation of space–time branching process models in seismology using an EM–type algorithm](https://doi.org/10.1198/016214508000000148). _Journal of the American Statistical Association_, 103(482), 614-624. 
  - [32] Salehi, F., Trouleau, W., Grossglauser, M., & Thiran, P. (2019). [Learning Hawkes processes from a handful of events](https://papers.neurips.cc/paper_files/paper/2019/hash/8767bccb1ff4231a9962e3914f4f1f8f-Abstract.html). _Advances in Neural Information Processing Systems_, 32.
  - [33] Mark, M., & Weber, T. A. (2020). [Robust identification of controlled Hawkes processes](https://doi.org/10.1103/PhysRevE.101.043305). _Physical Review E_, 101(4), 043305.
- Bayesian
  - [34] Rasmussen, J. G. (2013). [Bayesian inference for Hawkes processes](https://doi.org/10.1007/s11009-011-9272-5). _Methodology and Computing in Applied Probability_, 15, 623-642.
- Non-parametric:
  - [35] Lewis, E., & Mohler, G. (2011). [A nonparametric EM algorithm for multiscale Hawkes processes](https://www.georgemohler.com/_files/ugd/9226cc_89f6c24da28f4fa385b52d52eaffecc1.pdf). Technical Report.
  - [36] Bacry, E., & Muzy, J. F. (2016). [First-and second-order statistics characterization of Hawkes processes and non-parametric estimation](https://doi.org/10.1109/TIT.2016.2533397). _IEEE Transactions on Information Theory_, 62(4), 2184-2202.
  - [37] Kirchner, M. (2017). [An estimation procedure for the Hawkes process](https://doi.org/10.1080/14697688.2016.1211312). _Quantitative Finance_, 17(4), 571-595.
  - [38] Achab, M., Bacry, E., Gaïffas, S., Mastromatteo, I., & Muzy, J. F. (2017). [Uncovering causality from multivariate Hawkes integrated cumulants](https://proceedings.mlr.press/v70/achab17a.html). In _Proceedings of the 34th International Conference on Machine Learning_, PMLR 70:1-10. [\[Code\]](https://github.com/achab/nphc)
  - [39] Donnet, S., Rivoirard, V., & Rousseau, J. (2020). [Nonparametric Bayesian estimation for multivariate Hawkes processes](https://doi.org/10.1214/19-AOS1903). _Annals of Statistics_, 48(5), 2698-2727. 
- Estimation from time-censored information
  - [40] Shlomovich, L., Cohen, E. A., Adams, N., & Patel, L. (2022). [Parameter estimation of binned Hawkes processes](https://doi.org/10.1080/10618600.2022.2050247). _Journal of Computational and Graphical Statistics_, 31(4), 990-1000. [\[Code\]](https://github.com/lshlomovich/MCEM-Univariate-Hawkes)
  - [41] Rizoiu, M. A., Soen, A., Li, S., Calderon, P., Dong, L. J., Menon, A. K., & Xie, L. (2022). [Interval-censored Hawkes processes](https://www.jmlr.org/papers/v23/21-0917.html). _Journal of Machine Learning Research_, 23(338), 1-84.
  - [42] Cheysson, F., & Lang, G. (2022). [Spectral estimation of Hawkes processes from count data](https://doi.org/10.1214/22-AOS2173). _Annals of Statistics_, 50(3), 1722-1746. [\[Code\]](https://github.com/fcheysson/hawkesbow)
  - [43] Schneider, P. J., & Weber, T. A. (2023). [Estimation of self-exciting point processes from time-censored data](https://doi.org/10.1103/PhysRevE.108.015303). _Physical Review E_, 108(1), 015303.

## Neural Hawkes processes
There are several limitations to modeling temporal point processes for extremely high-dimensional data, such as large networks, where each dimension typically represents the activity of an individual, using parametric models following the general Hawkes process paradigm. Consequently, several scholars have demonstrated how to utilize various neural network architectures to overcome the computational challenges faced when adapting these processes.
- [44] Mei, H., & Eisner, J. M. (2017). [The neural Hawkes process: A neurally self-modulating multivariate point process](https://proceedings.neurips.cc/paper_files/paper/2017/hash/6463c88460bd63bbe256e495c63aa40b-Abstract.html). _Advances in Neural Information Processing Systems_, 30.
- [45] Du, N., Dai, H., Trivedi, R., Upadhyay, U., Gomez-Rodriguez, M., & Song, L. (2016). [Recurrent marked temporal point processes: Embedding event history to vector](https://doi.org/10.1145/2939672.2939875). In _Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining_ (pp. 1555-1564). [\[Code\]](https://github.com/dunan/NeuralPointProcess)
- [46] Upadhyay, U., De, A., & Gomez Rodriguez, M. (2018). [Deep reinforcement learning of marked temporal point processes](https://papers.nips.cc/paper_files/paper/2018/hash/71a58e8cb75904f24cde464161c3e766-Abstract.html). _Advances in Neural Information Processing Systems_, 31. [\[Code\]](https://github.com/Networks-Learning/tpprl)
- [47] Zuo, S., Jiang, H., Li, Z., Zhao, T., & Zha, H. (2020). [Transformer Hawkes process](https://proceedings.mlr.press/v119/zuo20a.html). In _Proceedings of the 37th International Conference on Machine Learning_, PMLR 119:11692-11702. [\[Code\]](https://github.com/SimiaoZuo/Transformer-Hawkes-Process)
- [48] Zhang, Q., Lipani, A., Kirnap, O., & Yilmaz, E. (2020). [Self-attentive Hawkes process](https://proceedings.mlr.press/v119/zhang20q.html). In _Proceedings of the 37th International Conference on Machine Learning_, PMLR 119:11183-11193. [\[Code\]](https://github.com/QiangAIResearcher/sahp_repo)
- [49] Mei, H., Yang, C., & Eisner, J. (2022). [Transformer embeddings of irregularly spaced events and their participants](https://openreview.net/forum?id=Rty5g9imm7H). In _International Conference on Learning Representations_. [\[Code\]](https://github.com/yangalan123/anhp-andtt)
- [50] Zhang, S., Zhou, C., Liu, Y. A., Zhang, P., Lin, X., & Ma, Z. M. (2024). [Neural jump-diffusion temporal point processes](https://proceedings.mlr.press/v235/zhang24cm.html). In _Proceedings of the 41st International Conference on Machine Learning_, PMLR 235:60541-60557.[\[Code\]](https://github.com/Zh-Shuai/NJDTPP)

## Extensions of Hawkes processes
- Renewal Hawkes process
  - [51] Wheatley, S., Filimonov, V., & Sornette, D. (2016). [The Hawkes process with renewal immigration & its estimation with an EM algorithm](https://doi.org/10.1016/j.csda.2015.08.007). _Computational Statistics & Data Analysis_, 94, 120-135.
  - [52] Chen, F., & Stindl, T. (2018). [Direct likelihood evaluation for the renewal Hawkes process](https://doi.org/10.1080/10618600.2017.1341324). _Journal of Computational and Graphical Statistics_, 27(1), 119-131.
- Discrete-time Hawkes process
  - [53] Browning, R., Sulem, D., Mengersen, K., Rivoirard, V., & Rousseau, J. (2021). [Simple discrete-time self-exciting models can describe complex dynamic processes: A case study of COVID-19](https://doi.org/10.1371/journal.pone.0250015). _PLOS One_, 16(4), e0250015.
  - [54] Wang, H. (2022). [Limit theorems for a discrete-time marked Hawkes process](https://doi.org/10.1016/j.spl.2022.109368). _Statistics & Probability Letters_, 184, 109368.
  - [55] Wang, H. (2023). [Large and moderate deviations for a discrete-time marked Hawkes process](https://doi.org/10.1080/03610926.2021.2024236). _Communications in Statistics-Theory and Methods_, 52(17), 6037-6062.
- Recursive extension of Hawkes process
  - [56] Schoenberg, F. P., Hoffmann, M., & Harrigan, R. J. (2019). [A recursive point process model for infectious diseases](https://doi.org/10.1007/s10463-018-0690-9). _Annals of the Institute of Statistical Mathematics_, 71, 1271-1287.
- Quadratic Hawkes process
  - [57] Blanc, P., Donier, J., & Bouchaud, J. P. (2017). [Quadratic Hawkes processes for financial prices](https://doi.org/10.1080/14697688.2016.1193215). _Quantitative Finance_, 17(2), 171-188.
  - [58] Aubrun, C., Benzaquen, M., & Bouchaud, J. P. (2023). [Multivariate quadratic Hawkes processes—part I: theoretical analysis](https://doi.org/10.1080/14697688.2023.2178322). _Quantitative Finance_, 23(5), 741-758.
- Ephemerally Hawkes process
  - [59] Daw, A., & Pender, J. (2022). [An ephemerally self-exciting point process](https://doi.org/10.1017/apr.2021.35). _Advances in Applied Probability_, 54(2), 340-403.
  
## Applications
In the following, we aim to highlight the general applicability of Hawkes processes to a plethora of applications. The provided references represent just a hand-selected subset of publications. In the subdirectories, we strive to provide a more comprehensive overview of the significant contributions towards adopting Hawkes processes.
- Earthquake modeling:
  - [60] Ogata, Y. (1988). [Statistical models for earthquake occurrences and residual analysis for point processes](https://doi.org/10.1080/01621459.1988.10478560). _Journal of the American Statistical Association_, 83(401), 9-27.
  - [61] Ogata, Y. (1998). [Space-time point-process models for earthquake occurrences](https://doi.org/10.1023/A:1003403601725). _Annals of the Institute of Statistical Mathematics_, 50, 379-402.
- Social media:
  - [62] Zhao, Q., Erdogdu, M. A., He, H. Y., Rajaraman, A., & Leskovec, J. (2015). [SEISMIC: A self-exciting point process model for predicting tweet popularity](https://doi.org/10.1145/2783258.2783401). In _Proceedings of the 21th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining_ (pp. 1513-1522). [\[Code\]](https://cran.r-project.org/web/packages/seismic/)
  - [63] Rizoiu, M. A., Xie, L., Sanner, S., Cebrian, M., Yu, H., & Van Hentenryck, P. (2017). [Expecting to be hip: Hawkes intensity processes for social media popularity](https://doi.org/10.1145/3038912.3052650). In _Proceedings of the 26th International Conference on World Wide Web_ (pp. 735-744).[\[Code\]](https://github.com/andrei-rizoiu/hip-popularity)
  - [64] Schneider, P. J., & Rizoiu, M. A. (2023). [The effectiveness of moderating harmful online content](https://doi.org/10.1073/pnas.2307360120). _Proceedings of the National Academy of Sciences_, 120(34), e2307360120. [\[Code\]](https://github.com/behavioral-ds/harmful-content-moderation)
- Criminology:
  - [65] Mohler, G. O., Short, M. B., Brantingham, P. J., Schoenberg, F. P., & Tita, G. E. (2011). [Self-exciting point process modeling of crime](https://doi.org/10.1198/jasa.2011.ap09546). _Journal of the American Statistical Association_, 106(493), 100-108.
- Finance:
  - [66] Aït-Sahalia, Y., Cacho-Diaz, J., & Laeven, R. J. (2015). [Modeling financial contagion using mutually exciting jump processes](https://doi.org/10.1016/j.jfineco.2015.03.002). _Journal of Financial Economics_, 117(3), 585-606.
  - [67] Rambaldi, M., Pennesi, P., & Lillo, F. (2015). [Modeling foreign exchange market activity around macroeconomic news: Hawkes-process approach](https://doi.org/10.1103/PhysRevE.91.012819). _Physical Review E_, 91(1), 012819.
  - [68] Mark, M., Sila, J., & Weber, T. A. (2022). [Quantifying endogeneity of cryptocurrency markets](https://doi.org/10.1080/1351847X.2020.1791925). _European Journal of Finance_, 28(7), 784-799.
- Epidemiology: 
  - [69] Rizoiu, M. A., Mishra, S., Kong, Q., Carman, M., & Xie, L. (2018). [SIR-Hawkes: Linking epidemic models and Hawkes processes to model diffusions in finite populations](https://doi.org/10.1145/3178876.3186108). In _Proceedings of the 2018 World Wide Web Conference_ (pp. 419-428). [\[Code\]](https://github.com/computationalmedia/sir-hawkes)
  - [70] Kim, M., Paini, D., & Jurdak, R. (2019). [Modeling stochastic processes in disease spread across a heterogeneous social system](https://doi.org/10.1073/pnas.1801429116). _Proceedings of the National Academy of Sciences_, 116(2), 401-406.
  - [71] Bertozzi, A. L., Franco, E., Mohler, G., Short, M. B., & Sledge, D. (2020). [The challenges of modeling and forecasting the spread of COVID-19](https://doi.org/10.1073/pnas.2006520117). _Proceedings of the National Academy of Sciences_, 117(29), 16732-16738. [\[Code\]](https://github.com/gomohler/pnas2020)
- Cyber insurance:
  - [72] Bessy-Roland, Y., Boumezoued, A., & Hillairet, C. (2021). [Multivariate Hawkes process for cyber insurance](https://doi.org/10.1017/S1748499520000093). _Annals of Actuarial Science_, 15(1), 14-39.
- Advertising:
  - [73] Xu, L., Duan, J. A., & Whinston, A. (2014). [Path to purchase: A mutually exciting point process model for online advertising and conversion](https://doi.org/10.1287/mnsc.2014.1952). _Management Science_, 60(6), 1392-1412.
 
## PhD Theses on Hawkes processes
There have been a couple of entire PhD theses, or at least chapters, focused on Hawkes processes and their extensions.
- Liniger, T. (2009). [Multivariate Hawkes processes](https://doi.org/10.3929/ethz-a-006037599) \[Doctoral dissertation, ETH Zurich (Switzerland)\].
- Chehrazi, N. (2013). [Identification and optimization of stochastic systems](http://purl.stanford.edu/zx541yn0318) \[Doctoral dissertation, Stanford University (USA)\].
- Zhu, L. (2013). [Nonlinear Hawkes processes](https://arxiv.org/pdf/1304.7531) \[Doctoral dissertation, New York University (USA)\].
- Kirchner, M. (2017). [Perspectives on Hawkes processes](https://doi.org/10.3929/ethz-b-000161487) \[Doctoral dissertation, ETH Zurich (Switzerland)\].
- Achab, M. (2017). [Learning from sequences with point processes](https://pastel.hal.science/tel-01775239) \[Doctoral dissertation, Université Paris Saclay (France)\].
- Stindl, T. (2019). [Statistical inference for renewal Hawkes self-exciting point processes](https://doi.org/10.26190/unsworks/21588) \[Doctoral dissertation, UNSW Sydney (Australia)\].
- Daw, A. M. (2020). [Batches, bursts, and service systems](https://doi.org/10.7298/sdfc-kg15) \[Doctoral dissertation, Cornell University (USA)\].
- Trouleau, W. (2021). [Learning self-exciting temporal point processes under noisy observations](https://doi.org/10.5075/epfl-thesis-7143) (Publication No. 7143). \[Doctoral dissertation, EPFL (Switzerland)\].
- Kong, Q. (2022). [Linking epidemic models and self-exciting processes for online and offline event diffusions](https://doi.org/10.25911/WJSH-XN56) [Doctoral dissertation, Australian National University (Australia)].
- Mark, M. (2022). [Self-exciting point processes: Identification and control](https://doi.org/10.5075/epfl-thesis-10991) (Publication No. 10991). \[Doctoral dissertation, EPFL (Switzerland)\].
- Browning, R. (2023). [Bayesian approaches for modelling discrete-time self-exciting processes and their applications](https://doi.org/10.5204/thesis.eprints.240350) \[Doctoral dissertation, Queensland University of Technology (Australia)\].
- Kwan, J. (2023). [Asymptotic analysis and ergodicity of the Hawkes process and its extensions](https://doi.org/10.26190/unsworks/24854) \[Doctoral dissertation, UNSW Sydney (Australia)\].
