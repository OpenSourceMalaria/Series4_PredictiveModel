# Abstract

The discovery of new antimalarial medicines with novel mechanisms of action is key to combating the increasing reports of resistance to our frontline treatments. The Open Source Malaria (OSM) consortium have been developing compounds ("Series 4") which possess potent activity against _Plasmodium falciparum_ _in vitro_ and _in vivo_ and have been suggested to act through the inhibition of PfATP4, an essential ion pump in the parasite membrane that regulates intracellular Na+ and H+ concentrations. This pump has not yet been crystallised, so in the absence of structural information about this target, a public competition was created to develop a model that would allow us to predict when compounds in Series 4 are likely to be active.

In the first round in 2016, six participants used the open data collated by OSM to develop moderately predictive models using diverse methods. Notably all submitted models were available to all other participants in real time. Since then further bioactivity data have been acquired and machine learning methods have rapidly developed, so a second round of the competition is now underway. The best-performing models from this second round will be used to predict novel analogs in Series 4 that will be synthesised and evaluated against the parasite. As such the project will openly demonstrate the abilities of new machine learning algorithms in the prediction of active compounds where there is no confirmed target, frequently the central problem in phenotypic drug discovery. 

# Detailed Abstract: Can we Predict Active Compounds in OSM Series 4?

The [Series 4 triazolopyrazines](https://github.com/OpenSourceMalaria/Series4/wiki) are a promising series of compounds that originate from a HTS at Pfizer. Compounds in the series have been shown to possess high potency (down to 16 nM). Additionally, two compounds have show efficacy _in vivo_. [Inherited information](http://malaria.ourexperiment.org/biological_data/7934/) for Series 4 and [follow-up studies](https://github.com/OpenSourceMalaria/Series4/wiki/Mechanism-of-Action%3A-Possible-PfATP4-Activity-Deduced-from-Parasite-Ion-Regulation-Assays), implicate the mechanism of action for Series 4 is _via_ inhibition of the malaria parasites ability to regulate its intracellular Na<sup>+</sup> concentration using a P-type Na<sup>+</sup>-ATPase transporter ([<I>Pf</I>ATP4](https://github.com/OpenSourceMalaria/Series4_PredictiveModel/wiki/PfATP4-and-Series-4)). There is correlation between _in vitro_ potency and <I>Pf</I>ATP4 activity.

We need to develop ways to predict new and potent Series 4 compounds in the absence of structural information of <I>Pf</I>ATP4. [Initial attempts](https://github.com/OpenSourceMalaria/Series4_PredictiveModel/wiki/Creating-a-Predictive-Model) were made by Murray Robertson in 2015, and a follow-up competition was [launched in 2016](https://github.com/OpenSourceMalaria/Series4_PredictiveModel/wiki/Round-1). This competition was designed to involve and utilise the expertise of the scientific community. There were 6 submissions by the end of the competition, and two equally well-performing models (created by Ho-Leung Ng and James McCulloch) were awarded prizes.

A subsequent round is [currently on-going](https://github.com/OpenSourceMalaria/Series4_PredictiveModel/wiki/Round-2) with the aim of involving companies and individuals specialising in AI and machine learning.

**Round 2 has now concluded. Thanks to all involved. The judging is underway and the results will be announced in the coming weeks**

# What is currently needed for the paper?

The paper is being written up in the GoogleDoc [here](https://docs.google.com/document/d/1aD29GjC8RjqrSDcWcEUptS04Z2v10deReRp0eB3kcp4/edit?usp=sharing). Please edit accordingly.

- Abstract is as above. Edits discussed [here](https://github.com/OpenSourceMalaria/Series4_PredictiveModel/issues/6)
- The basis for the introduction has been written up but still needs expanding in some areas.
- A very brief description of Round 1 is there but more information is required about the details of each of the original submitted models.
- A graphical summary of the judging and results of the Round 1 submissions needs to be created.
- The easiest thing is to be writing up anything that's happening in Round 2 as we go. If you have been participating in this round, it would be great if you could add anything relevant to the paper that describe your models/methods.
- Conclusions need writing.
