
# BloodBank

BloodBank smart contract is just a demo application showing how a hospital can keep the track of its blood donor using the smart contract so that the data can not be manipulated and any required person can see the data easily.


## Scope of Improvement:

You can implement some changes in the smart contract and make it more better. I am listing down few changes here, rest you can implement based on how you want to change the smart contract.

1. In `getPatientRecord` and `getAllRecords` functions you can restrict the assessibility to only hospital. Currently everyone can fetch the data but if you require that only hospital should be able to fetch the data the add that restriction. 

2. In `newPatient` function we can check if pateint is already registed or now by checking if the addhar card number already exists in the map or not. If it does then return an error from the contract. This function requires good hold of mapping concept. 

3. In `bloodTransaction` function we can check if patient type is donar the `to_address` in the args should be hospital address. If something else is passed then return error. 


