# WEUSEDTO-Data
**W**ater **E**nd **USE** **D**ataset and **TO**ols: an open water end use consumption dataset and data analytics tools

This repository contains the dataset of raw water end-use consumption time series collected in a single apartment used as case study for the WEUSEDTO software available at: https://github.com/Water-End-Use-Dataset-Tools/WEUSEDTO

Water end-uses were monitored using different IoT systems set up for all the fixtures in the apartment as reported in  [*Di Mauro, A., Di Nardo, A., Santonastaso, G. F., & Venticinque, S. (2019). An IoT system for monitoring and data collection of residential water end-use consumption. In Proc. - Int. Conf. Comput. Commun. Networks, ICCCN. Vol. 2019-July*](https://www.researchgate.net/publication/334957395_An_IoT_System_for_Monitoring_and_Data_Collection_of_Residential_Water_End-Use_Consumption) 

WEUSEDTO refers to 1 year of monitoring between 2019 and 2020 (March to November 2019 and July to October 2020). The residential apartment monitored, sited in Naples (Italy), is made up of 7 water fixtures and is inhabited by 1 person. Data are gathered with 1s resolution at fixture level and 10s time sampling at household level. Data at fixture level are collected for the entire period of monitoring while aggregate water consumption data are available for two months (September-October 2020).


The dataset contains:
* Water end use time series disaggregate for each fixture:
   * Washbasin
   * Bidet
   * Kitchen faucet
   * Shower
   * Washinmachine
   * Dishwasher (2 time series: cycle 30min and cycle 50eco)
   * Toilet
* Water end use time series aggregate for the whole apartment:
   * Whole house consumption

Related Publication: A. Di Mauro, S. Venticinque, G.F. Santonastaso, A. Di Nardo. *WEUSEDTO-Water End USE Dataset and TOols: an open water end use consumption dataset and data analytics tools*
