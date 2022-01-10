# Test case for the SFDX IndustriesManufacturing feature
[IndustriesManufacturing](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_scratch_orgs_def_file_config_values.htm#so_industriesmanufacturing) is listed as a supported Scratch Org Feature to enable Enables [Sales Agreements](https://help.salesforce.com/s/articleView?id=sf.retail_concept_admin_sasettings_sa.htm&type=5). 

## Testing
run the test script `./test.sh`

## Expected output
` Successfully created scratch org: 00D..............., username: test-............@example.com`

## Actual output
`ERROR running force:org:create:  IndustriesManufacturing is not a valid Features value.`