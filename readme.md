curl -X DELETE "localhost/machine-api/api/v1/housekeeping/timeseries/clearOldData" -d "dayLimit=30"-d "sizeLimit=50000"

curl -X DELETE http://localhost/machine-api/api/v1/housekeeping/timeseries/clearOldData?dayLimit=30&sizeLimit=50000"

curl --location --request DELETE "http://localhost/machine-api/api/v1/housekeeping/timeseries/clearOldData?dayLimit=30&sizeLimit=5000"

curl --location --request DELETE "http://localhost/machine-api/api/v1/housekeeping/timeseries/clearOldData?dayLimit=30&sizeLimit=100000"