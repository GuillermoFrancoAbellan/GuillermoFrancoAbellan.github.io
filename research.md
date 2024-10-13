---
#title: Research
layout: contact
#feature_text: |
  ## <span style="color:white"> Guillermo Franco Abellán</span>
#feature_image: "https://cerncourier.com/wp-content/uploads/2022/03/CCMarApr22_CMB-hero-1024x321.jpg"
#feature_image: "https://upload.wikimedia.org/wikipedia/commons/7/73/BOSS_Great_Wall.jpg"
#feature_image: "https://wallpapers.com/images/hd/watchmen-doctor-manhattan-mars-nf6a1ao2jf8ju0vl.jpg"
#excerpt: "A demo of Markdown and HTML includes"
aside: true
---


<p style="line-height:26px; margin-left: -220px; margin-right: 220px;">
My research covers various topics, but they are all connected to theoretical and phenomenological cosmology.
<!---
The following word cloud, generated from all of my publications, gives an idea of my research themes.</p>
<p style="line-height:26px; margin-left: -170px; margin-right: 220px;">
<img width="630" src="/assets/wordcloud.png">
</p>
<p style="line-height:26px; margin-left: -220px; margin-right: 220px;">
-->
Below you can find a brief description of my main areas of research. A complete list of my publications can be found on my
<a href="https://inspirehep.net/literature?sort=mostrecent&size=25&page=1&q=f%20a%20guillermo%20franco%20abellan&ui-citation-summary=true" style="color: #6600cc;"> InspireHEP</a> profile.</p>

<p>
</p>

<p style="margin-left: -25px;"> <span style="font-size: 23px;"><b>Simulation-based inference</b></span> </p>


<p style="line-height:26px; margin-left: -220px; margin-right: 220px;">
Simulation-based inference (SBI) refers to a class of Bayesian methods which don't need an explicit evaluation of the likelihood, only to generate samples from it via a stochastic simulator. SBI methods use simulated data-parameter pairs to train neural networks that directly learn the posteriors of interest, and usually are more scalable and efficient than traditional inference methods such as Markov Chain Monte Carlo (MCMC). These modern techniques will be crucial to analyse upcoming surveys like Euclid, as this will be computationally unfeasible with standard tools.
</p>
<figure style="margin: 0; margin-left: -70px;">  
<img src="/assets/plots/Swyft.png" alt="Description of Image" style="width: 400px;">
<figcaption style="font-size: 12px; line-height: 17px; text-align: center; margin-left: -10px; margin-right: 400px; color: gray;">
Forecast constraints on the &Lambda;CDM cosmological parameters from 3x2pt Stage IV photometric probes, using both Swyft (black) and MCMC (green). Swyft is in excellent agreement with MCMC while being ~40 times faster.<br> (from <a href="https://arxiv.org/abs/2403.14750" style="color: #6600cc;"> Abellán, C. Herrera et al. 2024</a>)  
</figcaption>
</figure>
<p>
</p>
<p style="line-height:26px; margin-left: -220px; margin-right: 220px;">
I have applied a recent SBI algorithm called Marginal Neural Ratio Estimation (MNRE, implemented in the code <a href="https://github.com/undark-lab/swyft" style="color: #6600cc;"> Swyft</a>) to LSS photometric probes: weak lensing, galaxy clustering and the cross-correlation power spectra (i.e. the so-called 3x2pt analysis). Using this <a href="https://github.com/GuillermoFrancoAbellan/Swyft-LSS" style="color: #6600cc;"> code</a> and mock data for a Stage IV survey, my collaborators and I showed that we can accurately recover the cosmological parameters with a speedup factor of ~40-60 compared to classical MCMC methods.
</p>
<p>
</p>


<p style="margin-left: 40px;"> <span style="font-size: 23px;"><b>Cosmic tensions</b></span> </p>

<p style="line-height:26px; margin-left: -220px; margin-right: 220px;">
Several cosmic tensions have emerged in recent years. Namely, local measurements of the Hubble constant H<sub style="font-size: 70%;">0</sub> yield values that are 5-6&sigma; higher than the &Lambda;CDM prediction calibrated onto Planck data. Similarly, weak lensing surveys have reported values of the lumpiness of matter (as quantified by S<sub style="font-size: 70%;">8</sub>) which are consistently lower, at the 2-3&sigma; level. For this reason, there has been a growing interest in exploring different extensions featuring non-trivial dark energy (DE) or dark matter (DM) properties, which could shed light on the mysterious dark sector and possibly explain these anomalies.
</p>


<div style="display: flex; justify-content: space-around; align-items: flex-start;margin-left: -340px;">
<figure style="text-align: center;margin-left: -10px;">
<img src="/assets/plots/Geff.png" alt="Description of Image" style="width: 380px;">
<figcaption style="font-size: 12px; line-height: 17px; text-align: center; color: gray;margin-left: 120px; margin-right: 80px;">
Functional posterior for the shift in the cosmological Newton constant due to a model of early modified gravity (fit to Planck+ACT+SPT) which was proposed to explain the H<sub style="font-size: 70%;">0</sub> tension. (from <a href="https://arxiv.org/abs/2308.12345" style="color: #6600cc;">Abellán, Braglia et al. 2023</a>)
</figcaption>
</figure>

<figure style="text-align: center;margin-left: -250px;">
<img src="/assets/plots/DCDM.png" alt="Description of Image" style="width: 370px;">
<figcaption style="font-size: 12px; line-height: 17px; text-align: center; color: gray; margin-left: 240px; margin-right: 210px;">
Residuals in the linear matter power spectrum P(k) at redshifts z=0,3 for the best-fit 2-body decaying DM model to Planck+BAO+SNIa+S<sub style="font-size: 70%;">8</sub> data. The model yields a time-dependent power suppression affecting the scales to which S<sub style="font-size: 70%;">8</sub> is most sensitive. (adapted from <a href="https://arxiv.org/abs/2008.09615" style="color: #6600cc;">Abellán, Murgia et al. 2022</a>)
</figcaption>
</figure>
</div>
<p>
</p>
<p style="line-height:26px; margin-left: -220px; margin-right: 220px;">
I have studied the cosmological signatures of various &Lambda;CDM extensions, which are directly targeted at explaining the S<sub style="font-size: 70%;">8</sub> tension (2-body decaying DM), the H<sub style="font-size: 70%;">0</sub> tension (early dark energy, early modified gravity), or both tensions simultaneously (interacting stepped dark radiation). Using data from CMB, SNIa or galaxy clustering, my collaborators and I have derived state-of-the-art constraints on these scenarios, which can be applied to many different high-energy/particle physics models. To achieve this, I have extensively used and modified the Boltzmann solver <a href="https://github.com/lesgourg/class_public" style="color: #6600cc;"> CLASS</a> and the MCMC sampler <a href="https://github.com/brinckmann/montepython_public" style="color: #6600cc;"> MontePython</a>. When needed, I have also developed analytical approximations to speed up the evolution of linear perturbations (for instance, this enabled the first full analysis of the 2-body <a href="https://github.com/GuillermoFrancoAbellan/class_decays/tree/merging_with_master" style="color: #6600cc;"> decaying DM</a> model).
</p>


<p>
</p>

<p style="margin-left: 15px;"> <span style="font-size: 23px;"><b>Neutrino cosmology</b></span> </p>

<p style="line-height:26px; margin-left: -220px; margin-right: 220px;">
A key prediction of the concordance cosmological model is the presence of a relic neutrino background (C&nu;B), which leaves detectable imprints on CMB and LSS observables. This can then be used to constrain properties such as neutrino mass, whose origin still remains a mystery. Over recent years, the cosmological upper limits on the total neutrino mass have become increasingly stringent, reaching a point where they may potentially conflict with direct laboratory bounds. However, cosmological mass bounds are model-dependent, and can be significantly relaxed in scenarios such as neutrino decays.
</p>

<figure style="margin: 0; margin-left: -130px;">  
<img src="/assets/plots/decaying_nu.png" alt="Description of Image" style="width: 500px;">
<figcaption style="font-size: 12px; line-height: 17px; text-align: center; margin-left: 10px; margin-right: 350px; color: gray;">
Current constraints on decaying neutrinos in the &Gamma;<sub style="font-size: 70%;">&nu;</sub> vs. m<sub style="font-size: 70%;">&nu;</sub>  parameter space. Our analysis excludes the red (blue) region labelled Planck 2015 (Planck 2018)
based on the data Planck+BAO+SNIa.  (from <a href="https://arxiv.org/abs/2112.13862" style="color: #6600cc;"> Abellán, Chacko et al. 2022</a>)  
</figcaption>
</figure>
<p>
</p>
<p style="line-height:26px; margin-left: -220px; margin-right: 210px;">
Together with my collaborators, we have derived the most up-to-date CMB constraints on &Sum;m<sub style="font-size: 70%;">&nu;</sub> as a function of neutrino lifetime. This work showed that scenarios where neutrinos decay non-relativistically into dark radiation can relax mass bounds up to &Sum;m<sub style="font-size: 70%;">&nu;</sub>~0.4 eV. Recently, I also got interested on improving the modelling of the C&nu;B abundance and anisotropies with the help of numerical simulations and linear perturbation theory. This will be important to understand the prospects of future experiments aiming to directly detect the C&nu;B, like PTOLEMY.
</p>
<p>
</p>


<p style="margin-left: -25px;"> <span style="font-size: 23px;"><b>Exotic energy injection </b></span> </p>


<p style="line-height:26px; margin-left: -220px; margin-right: 220px;">
There are several models where DM is expected to annihilate or decay, leading to an injection of exotic energy into the intergalactic medium. These models modify the thermal history of the universe, and consequently, the CMB anisotropies or the 21cm signal. Interestingly, exotic energy injection can also be used as an indirect probe of inflation. The idea is that many inflationary scenarios predict an enhancement in the primordial power spectrum at small scales. This can trigger the early formation of ultracompact minihalos (UCMHs), which can in turn boost the DM annihilation signal.
</p>
<figure style="margin: 0; margin-left: -180px;">  
<img src="/assets/plots/UCMH.png" alt="Description of Image" style="width: 600px;">
<figcaption style="font-size: 12px; line-height: 17px; text-align: center; margin-left: 10px; margin-right: 300px; color: gray;">
Compilation of constraints on the primordial power spectrum (solid lines) and sensitivity forecasts for the next generation observatories (dashed lines). Our constraints coming from exotic energy injection in the CMB are indicated in red (for s-wave DM annihilations) and brown (for p-wave DM annihilations).<br>  (from <a href="https://arxiv.org/abs/2304.02996" style="color: #6600cc;"> Abellán and Fachinetti 2023</a>)
</figcaption>
</figure>
<p>
</p>
<p style="line-height:26px; margin-left: -220px; margin-right: 220px;">
Using an accurate analytical model of DM annihilations within UCMHs onto the CMB (<a href="https://github.com/GuillermoFrancoAbellan/ExoCLASS" style="color: #6600cc;">code</a> here), my collaborator and I have derived robust constraints on the small-scale primordial spectrum. These constraints are competitive with those coming from &gamma;-ray observations or other probes. Currently, I'm forecasting the constraining power of future 21cm surveys to the primordial spectrum, through the effect of minihalo-boosted DM annihilations.
</p>

<p>
</p>





<!---

<p style="line-height:26px;">A detailed overview of my past research is <br>
forthcoming. In the meantime, a complete <br>
list of my publications can be found on <br>
<a href="https://inspirehep.net/literature?sort=mostrecent&size=25&page=1&q=f%20a%20guillermo%20franco%20abellan&ui-citation-summary=true" > InspireHEP</a>, <a href="https://arxiv.org/search/?query=guillermo+franco+abellan&searchtype=all&abstracts=show&order=-announced_date_first&size=50" > ArXiv</a> and <a href="https://scholar.google.com/citations?user=RyfefpcAAAAJ&hl=es&oi=ao" > Google Scholar</a>.
</p>
<small><i>Under construction</i></small>

-->
