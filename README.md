Project Page for the EUSIPCO 2022 paper: 
# Recovery of Missing Sensor Data by Reconstructing Time-varying Graph Signals
Authors: [Anindya Mondal](https://sites.google.com/view/anindyamondal), [Mayukhmali Das](), [Aditi Chatterjee](), and [P. Venkateswaran]()

- - - -
![Pipeline](https://raw.githubusercontent.com/anindya2001/EUSIPCO_22_Sobolev/main/schematic.png)
- - - -
**Abstract**: Wireless sensor networks are among the most promising technologies of the current era because of their small size, lower cost, and ease of deployment. With the increasing number of wireless sensors, the probability of generating missing data also rises. This incomplete data could lead to disastrous consequences if used for decision-making. There is rich literature dealing with this problem. However, most approaches show performance degradation when a sizable amount of data is lost. Inspired by the emerging field of graph signal processing, this paper performs a new study of a Sobolev reconstruction algorithm in wireless sensor networks. Experimental comparisons on several publicly available datasets demonstrate that the algorithm surpasses multiple state-of-the-art techniques by a maximum margin of 54\%. We further show that this algorithm consistently retrieves the missing data even during massive data loss situations.

[Preprint](https://eurasip.org/Proceedings/Eusipco/Eusipco2022/pdfs/0002181.pdf) | [Presentation](https://mondalanindya.github.io/assets/presentations/EUSIPCO_2022_Presentation.pdf) | [Poster](https://mondalanindya.github.io/assets/posters/EUSIPCO_22_Poster.pdf)

Download the Intel Lab Dataset from [here](http://db.csail.mit.edu/labdata/labdata.html) and the Mol'ene dataset from [here](https://github.com/bgirault-usc/Molene-Dataset).

If you find our work useful, please consider citing as: 
- - - -
## Citation

        @article{mondal2022recovery,
        title={Recovery of Missing Sensor Data by Reconstructing Time-varying Graph Signals},
        author={Mondal, Anindya and Das, Mayukhmali and Chatterjee, Aditi and Venkateswaran, Palaniandavar},
        journal={arXiv preprint arXiv:2203.00418},
        year={2022}
        }
        
        @inproceedings{mondal2022recovery,
        title={Recovery of Missing Sensor Data by Reconstructing Time-varying Graph Signals},
        author={Mondal, Anindya and Das, Mayukhmali and Chatterjee, Aditi and Venkateswaran, Palaniandavar},
        booktitle={2022 30th European Signal Processing Conference (EUSIPCO)},
        pages={2181--2185},
        year={2022},
        organization={IEEE}
        }
        
- - - -

## References

This work builds upon the code from [GraphTRSS](https://github.com/jhonygiraldo/GraphTRSS), [Sobolev_COVID19](https://github.com/jhonygiraldo/Sobolev_COVID19) and [gspbox](https://github.com/epfl-lts2/gspbox) and from the papers: 

- Giraldo, Jhony H., Arif Mahmood, Belmar Garcia-Garcia, Dorina Thanou, and Thierry Bouwmans. "Reconstruction of Time-Varying Graph Signals via Sobolev Smoothness." IEEE Transactions on Signal and Information Processing over Networks 8 (2022): 201-214.
- Giraldo, Jhony H., and Thierry Bouwmans. "On the minimization of Sobolev norms of time-varying graph signals: Estimation of new coronavirus disease 2019 cases." In 2020 IEEE 30th International Workshop on Machine Learning for Signal Processing (MLSP), pp. 1-6. IEEE, 2020.
- Qiu, K., Mao, X., Shen, X., Wang, X., Li, T., & Gu, Y. (2017). Time-varying graph signal reconstruction. IEEE Journal of Selected Topics in Signal Processing, 11(6), 870-88.
- Perraudin, N., Paratte, J., Shuman, D., Martin, L., Kalofolias, V., Vandergheynst, P., & Hammond, D. K. (2014). GSPBOX: A toolbox for signal processing on graphs. arXiv preprint arXiv:1408.5781.

Please consider citing these too. 
