# PROJECT_DataScience
Repository of Data science project. Created for the needs of DS Bootcamp.


# Project background
Automatic seismogram picking is an issue known from late 70s. During the years many different approaches to the problem have been proposed. First studies in this field given by Allen (1978) or Baer and Kradolfer (1987) was based on the comparison between the short-(STA) and the long-term average (LTA) of the signal. Another approaches to find seismic waves on digital records are using autoregressive methods (AR) (Leonard and Kennett, 1999; Leonard, 2000), high order statistics (HOS) (Küperkoch et al., 2010), Continuous Wavelet Transform (CWT) (Zhang et al., 2003) or algorithms that use neural networks (Wang and Teng, 1995).

Auto-picking algoritms are already successfully implemented in early warning systems such as ShakeAlert® given by USGS or in local systems used for seismic hazard monitoring in the vicinity of vulcanos or regions, like Chile or Japan. Furthermore auto-picking tools can be also used to process of large seismic waveforms datasets. These methods enables e.g. basic analysis like localization of seismic events or earthquake energy estimation.

Nevertheless such algorithm are still rarely used to monitor and detect induced seismic events. Because of low energy and shallow seismic source locations, the detection of seismic waves in anthropogenic seismicity is a challenging task. This project is a first step in creation of auto-picking tool for in-mine underground monitoring system. I present an auto-detection of mining induced earthquakes based on P-waves and high order statistics approach combine with convolutional neural networks (CNN). The idea of this work was inspired by research of Gentili and Michelini (2006), Ross et al. (2018) and an on-line publication *"Introduction to 1D Convolutional Neural Networks in Keras for Time Sequences* publish on https://blog.goodaudience.com/.
