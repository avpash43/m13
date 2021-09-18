* Add your code in `src/main/` if needed
* Test your code with `src/tests/` if needed
* Modify notebooks for your needs
* Deploy infrastructure with terraform
```
terraform init
terraform plan -out terraform.plan
terraform apply terraform.plan
....
terraform destroy
```
* Launch notebooks on Databricks cluster

## Make bronze stream from raw azure data storage with auto loader https://docs.microsoft.com/en-us/azure/databricks/spark/latest/structured-streaming/auto-loader

![Alt text](screenshots/BronzeStream.png?raw=true "Title")

## Display bronze stream

![Alt text](screenshots/BronzeDisplay.png?raw=true "Title")

## Make silver stream

![Alt text](screenshots/SilverStream.png?raw=true "Title")

## Display silver stream

![Alt text](screenshots/SilverDisplay.png?raw=true "Title")

## Make gold stream with number of distinct hotels and average/max/min temperature in the city.

![Alt text](screenshots/GoldDistinctAndTmprStream.png?raw=true "Title")

## Display gold stream

![Alt text](screenshots/GoldDistinctAndTmprDisplay.png?raw=true "Title")

## Create gold table for next query, because "Non-time-based windows are not supported on streaming DataFrames/Datasets"

![Alt text](screenshots/GoldTable.png?raw=true "Title")

## 10 biggest cities

![Alt text](screenshots/Top10.png?raw=true "Title")

## gold files in azure data storage

![Alt text](screenshots/AzureStorageGold.png?raw=true "Title")