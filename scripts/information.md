Bronze Bucket Name - youtube-data-pipeline-2026-bronze-us-east-1
Silver Bucket Name - youtube-data-pipeline-2026-silver-us-east-1
Gold Bucket Name - youtube-data-pipeline-2026-gold-us-east-1

Script Bucket Name - youtube-data-pipeline-2026-script-us-east-1

SNS ARN - arn:aws:sns:us-east-1:YOUR_ACCOUNT_ID:youtube-data-pipeline-alerts:aae4efaa-f900-4a30-b487-8067b1a66b4c

GLUE Bronze - youtube-data-pipeline-bronze
GLUE Silver - youtube-data-pipeline-silver
GLUE Gold - youtube-data-pipeline-gold


--bronze_database youtube-data-pipeline-bronze 
--bronze_table raw_statistics 
--silver_bucket youtube-data-pipeline-2026-silver-us-east-1
--silver_database youtube-data-pipeline-silver 
--silver_table clean_statistics

--silver_database youtube-data-pipeline-silver 
--gold_bucket youtube-data-pipeline-2026-gold-us-east-1
--gold_database youtube-data-pipeline-gold
