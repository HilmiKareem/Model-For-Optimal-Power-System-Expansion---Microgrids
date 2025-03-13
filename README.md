# Model-For-Optimal-Power-System-Expansion---Microgrids with Interconnections

## Aim 
This model is aimed to allow for the analysis of the financial impact of investing in interconnection between two microgrids in Uganda. 

## Decription

The model uses Julia JuMP with linear solver to optimally decide on the total capacity of solar panels and BESS to build depending on the chosen amount of transmission capacity between the two microgrids. 

The default setting assume that Node 1 is a residential area and Node 2 is an agriculture site. This is reflected on the default load profiles that is being used. 

The parameters are chosen accordingly and explained in the report. 

Feel free to choose your own parameters and model your own specific scenarios !! 

Note on Excel File :

demand_node 1/2 = Specify the hourly demand for 1 year at the individual node (MW)

RES_profilesnode1/2 = Specify the normalized irradiance of the coordinated, taken from Renewable Ninja

Storage_Node1/2 = Specify the specification of the storage characteristic : [Technology;	Pmax(MW);	SOCmax(MWh);	charge_eff(%);	discharge_eff(%)]
