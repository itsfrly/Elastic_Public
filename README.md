# Elastic_Public

es_bulk_rollover is a simple command line tool to rollover indices in bulk using the elasticsearch python plugin. 

## Usage

1. Launch the script using python3 es_bulk_rollover
2. The script will prompt for elasticsearch endpoint. This should look like the following example: https://dummy-elastic-prod-server123456789.es.us-east-1.aws.elastic-cloud.com:9243 
3. The script will prompt for username and password
4. Answer the index pattern prompt with your preferred index pattern (* wildcards are accepted)
5. The minimum age prompt will prompt for a minimum age to rollover. This must be an integer or the script will fail
6. Confirm the list of indices to rollover is correct and respond with "y" to proceed with rollover. "n" will abort the operation  

## Requirements

es_bulk_rollover requires the elasticsearch python client. More information about this client can be found here: https://elasticsearch-py.readthedocs.io/en/v8.2.0/
