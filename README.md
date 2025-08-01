This a Test for Integrate and Deploy snowflake objects with Jenkins. Follow this url for the quickstar -> https://quickstarts.snowflake.com/guide/devops_dcm_schemachange_azure_devops/index.html?index=..%2F..index#0

Me funcionó con este comando:  schemachange -f migrations --connection-name Connection_1 -c DEMO_DB.SCHEMACHANGE.CHANGE_HISTORY --create-change-history-table.