# storage_request_pass2_data

This is for pass2 11 years cascade data. We are going to process data from 2010 to 2020.

We start from cascade level3 data. The path for level3 data are:
* /data/ana/Cscd/IC[79,86]-20*/level3pass2/exp/* for year 2010-2016
* /data/ana/Cscd/IC86-20*/level3/exp/* for year 2017-2020

We are going to process them through **cascade finallevel filters**, the output files will be stored at:

/data/ana/analyses/diffuse/cascades/pass2/data/IC*/[burn,blind]/final_[cascade,hybrid,muon]/

We would like to permenantly keep this files.

# pass2 MC dataset

As for pass2 MC dataset, we would also like to request 5 TB to store them permanently. 

We use nugen dataset [21217-21219] as baseline dataset and 
* numu 218[13-14],21938
* nutau 218[67,68], 21939
* nue 218[70,71], 21940
as systematic dataset.

We will process them to cascade finallevel and the target path will be like:
/data/ana/analyses/diffuse/cascades/pass2/sim/${datasetid}/*



