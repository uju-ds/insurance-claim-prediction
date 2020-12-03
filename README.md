# insurance-claim-prediction
my work
# DESCRIPTION
Recently, there has been an increase in the number of building collapse in Lagos and major cities in Nigeria. Olusola Insurance Company offers a building insurance policy that protects buildings against damages that could be caused by a fire or vandalism, by a flood or storm. Here is a predictive model to determine if a building will have an insurance claim during a certain period or not,and have to predict the probability of having at least one claim over the insured period of the building. The model will be based on the building characteristics. The target variable, Claim, is a:

1 if the building has at least a claim over the insured period.
0 if the building doesn’t have a claim over the insured period.

# Variable Description
Customer Id-Identification number for the Policy holder.
YearOfObservation-year of observation for the insured policy.
Insured_Period-duration of insurance policy in Olusola Insurance.(Ex: Full year insurance,Policy Duration = 1; 6 months = 0.5). Residential-is the building a residential building or not.
Building_Painted-is the building painted or not (N-Painted, V-Not Painted).
Building_Fenced-is the building fence or not (N-Fenced, V-Not Fenced).
Garden-building has garden or not (V-has garden; O-no garden).
Settlement-Area where the building is located. (R- rural area; U- urban area).
Building Dimension-Size of the insured building in m2.
Building_Type-The type of building (Type 1, 2, 3, 4).
Date_of_Occupancy-date building was first occupied.
NumberOfWindows-number of windows in the building.
Geo Code-Geographical Code of the Insured building.
Claim-target variable. (0: no claim, 1: at least one claim over insured period).
