This GitHub repository is a complementary material for the paper **"A Zero-Inflated Latent Position Cluster Model" (ZIP-LPCM)** to provide the 3-dimensional interactive visualization of the synthetic networks and the real networks therein. 

The paper mainly works on the ZIP-LPCM incorporated with the **mixture-of-finite-mixtures (MFM)** clustering prior.
The inference is based on a novel **partially collapsed Metropolis-within-Gibbs (PCMwG)** sampler with a newly proposed **truncated absorb-eject (TAE)** move embedded inside.
A supervised version of the method is also provided.
One key aspect of the paper is that we illustrate our results on 3-dimensional latent spaces.
We refer to the paper for more details, and we refer to another repository: [https://github.com/Chaoyi-Lu/ZIP-LPCM](https://github.com/Chaoyi-Lu/ZIP-LPCM) for the details of the coding and implementations.

1. The 3-d interactive plot of the **Simulation study 1 scenario 1** reference latent positions $`\boldsymbol{U}^*`$ and referernce clustering $`\boldsymbol{z}^*`$ shown as **Figure 1** of the **ZIP-LPCM** paper is available at: [https://chaoyi-lu.github.io/ZIP_LPCM_3_Dimensional_Visualization/SS1_Scenario1_InteractivePlot.html](https://chaoyi-lu.github.io/ZIP_LPCM_3_Dimensional_Visualization/SS1_Scenario1_InteractivePlot.html).
2. The 3-d interactive plot of the **Simulation study 1 scenario 2** reference latent positions $`\boldsymbol{U}^*`$ and referernce clustering $`\boldsymbol{z}^*`$ shown as **Figure 1** of the paper is available at: [https://chaoyi-lu.github.io/ZIP_LPCM_3_Dimensional_Visualization/SS1_Scenario2_InteractivePlot.html](https://chaoyi-lu.github.io/ZIP_LPCM_3_Dimensional_Visualization/SS1_Scenario2_InteractivePlot.html).

3. The 3-d interactive plot of the **Simulation study 2 scenario 1** summarized latent positions $`\hat{\boldsymbol{U}}`$ and summarized clustering $`\hat{\boldsymbol{z}}`$ shown as the 1st row plots of **Figure 5** in the paper is available at: [https://chaoyi-lu.github.io/ZIP_LPCM_3_Dimensional_Visualization/SS2_Scenario1_InteractivePlot.html](https://chaoyi-lu.github.io/ZIP_LPCM_3_Dimensional_Visualization/SS2_Scenario1_InteractivePlot.html).

4. The 3-d interactive plot of the **Simulation study 2 scenario 2** summarized latent positions $`\hat{\boldsymbol{U}}`$ and summarized clustering $`\hat{\boldsymbol{z}}`$ shown as the 2nd row plots of **Figure 5** in the paper is available at: [https://chaoyi-lu.github.io/ZIP_LPCM_3_Dimensional_Visualization/SS2_Scenario2_InteractivePlot.html](https://chaoyi-lu.github.io/ZIP_LPCM_3_Dimensional_Visualization/SS2_Scenario2_InteractivePlot.html).

5. The 3-d interactive plot of the **Sampson Monks** directed real network summarized latent positions $`\hat{\boldsymbol{U}}`$ and summarized clustering $`\hat{\boldsymbol{z}}`$ shown as **Figure 8** of the paper is available at: [https://chaoyi-lu.github.io/ZIP_LPCM_3_Dimensional_Visualization/RDA_SampsonMonks_InteractivePlot.html](https://chaoyi-lu.github.io/ZIP_LPCM_3_Dimensional_Visualization/RDA_SampsonMonks_InteractivePlot.html).

6. The 3-d interactive plot of the **Windsurfers** undirected real network summarized latent positions $`\hat{\boldsymbol{U}}`$ and summarized clustering $`\hat{\boldsymbol{z}}`$ shown as **Figure 9** of the paper is available at: [https://chaoyi-lu.github.io/ZIP_LPCM_3_Dimensional_Visualization/RDA_Windsurfers_InteractivePlot.html](https://chaoyi-lu.github.io/ZIP_LPCM_3_Dimensional_Visualization/RDA_Windsurfers_InteractivePlot.html).

7. The 3-d interactive plot of the **Train Bombing** undirected real network summarized latent positions $`\hat{\boldsymbol{U}}`$ and summarized clustering $`\hat{\boldsymbol{z}}`$ shown as **Figure 11** of the paper is available at: [https://chaoyi-lu.github.io/ZIP_LPCM_3_Dimensional_Visualization/RDA_TrainBombing_InteractivePlot.html](https://chaoyi-lu.github.io/ZIP_LPCM_3_Dimensional_Visualization/RDA_TrainBombing_InteractivePlot.html).

8. The 3-d interactive plot of the **Summit Co-attendance Criminality** undirected real network summarized latent positions $`\hat{\boldsymbol{U}}`$ and reference clustering $`\boldsymbol{z}^*`$ shown as the 1st row plots in **Figure 13** of the paper is available at: [https://chaoyi-lu.github.io/ZIP_LPCM_3_Dimensional_Visualization/RDA_CriminalSummit_InteractivePlot_Ref_z.html](https://chaoyi-lu.github.io/ZIP_LPCM_3_Dimensional_Visualization/RDA_CriminalSummit_InteractivePlot_Ref_z.html).

9. The 3-d interactive plot of the **Summit Co-attendance Criminality** undirected real network summarized latent positions $`\hat{\boldsymbol{U}}`$ and summarized clustering $`\hat{\boldsymbol{z}}`$ shown as the 2nd row plots in **Figure 13** of the paper is available at: [https://chaoyi-lu.github.io/ZIP_LPCM_3_Dimensional_Visualization/RDA_CriminalSummit_InteractivePlot_Hat_z.html](https://chaoyi-lu.github.io/ZIP_LPCM_3_Dimensional_Visualization/RDA_CriminalSummit_InteractivePlot_Hat_z.html).

Within each 3-d interactive plot, the readers are free to rotate, zoom in or zoom out the plot.
There is also an operation panel placed on top-right of the 3-d interactive plot for readers to play with.
More details can be found in [https://plotly.com/r/3d-charts/](https://plotly.com/r/3d-charts/).

If the readers put the mouse pointer on each node of the 3-d interactive plot, a comment bracket would appear within which some basic information about the corresponding node/individual is included: (i) the coordinate of the node, (ii) the node number (e.g. node 1, node 2, ...).
Depending on different network data, some extra information might also be included, for example, the reference clustering we ednote as $\boldsymbol{z}^*$, the exogenous node attributes $\boldsymbol{c}$ and so on.

If the readers put the mouse pointer on each edge of the 3-d interactive plot, the comment bracket would show (i) either the start coordinate or the end coordinate of the interaction vector, (ii) the interaction weight.
If the network is directed, the comment bracket would also show a variable `UpperDiag?` which is a `TRUE` or `FALSE` variable indicating whether or not the corresponding $y_{ij}$ is placed at the upper-diagonal part of the adjacency matrix $\boldsymbol{Y}$ for each edge, so that the directions the edges are known.






