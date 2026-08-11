# rubrik_data_analytics_project

1. Overall Backup Health

The dataset contains 50,000 backup jobs, with 3,208 failed jobs, giving an overall backup failure rate of approximately 6.42%.

Insight: Although the majority of backup jobs were successful, more than 3,000 failures indicate a significant operational area for monitoring and investigation.


2. Google Cloud Has the Highest Failure Rate
   
| Cloud Provider | Failure Rate |
| -------------- | -----------: |
| Google Cloud   |    **6.79%** |
| AWS            |        6.32% |
| Azure          |        6.15% |

Insight: Google Cloud recorded the highest backup failure rate at 6.79%, while Azure had the lowest at 6.15% among the three providers.

Be careful with wording here: this doesn't prove Google Cloud is inherently less reliable. It only means it had the highest failure rate in this dataset.


3. Enterprise Customers Have Much Larger Backups
   
| Company Size | Avg. Backup Size |
| ------------ | ---------------: |
| Small        |        175.18 GB |
| Medium       |        901.54 GB |
| Large        |      3,239.62 GB |
| Enterprise   |      8,495.13 GB |

Insight: Average backup size increases substantially with company size, with Enterprise customers generating backups roughly 48× larger than Small customers. This makes large customers particularly important for storage-capacity and cost planning.


4. Asia Pacific Has the Highest Storage Cost
   
| Region        |    Storage Cost |
| ------------- | --------------: |
| Asia Pacific  | **$853,349.47** |
| South America |     $844,417.68 |
| North America |     $839,171.12 |
| Europe        |     $791,864.99 |

Insight: Asia Pacific generated the highest total storage cost at approximately $853K, while Europe had the lowest among the analyzed regions.


5. Williams Group Is the Highest-Cost Customer

top customer by total storage cost was:

Williams Group — $16,697.87

Followed by Marshall LLC ($16,534.97) and Khan PLC ($16,474.25).

Insight: A relatively small group of customers contributes disproportionately to storage expenditure, making high-cost customers potential targets for storage optimization and capacity planning.


6. Brown Inc Has the Most Failed Backups

The highest number of failed backups was:

Brown Inc — 14 failures

Smith LLC and Brooks-Payne followed with 13 each.

Insight: Brown Inc recorded the highest number of failed backup jobs, suggesting that customer-level monitoring can help identify accounts requiring investigation or additional operational support.


7. Recovery Performance Needs Attention

| Recovery Status      | Count |
| -------------------- | ----: |
| Failed               | 1,088 |
| Partially Successful | 1,058 |
| Successful           | 1,062 |

Insight: Recovery outcomes were almost evenly distributed across Failed, Partially Successful, and Successful categories. This indicates that recovery operations deserve close monitoring alongside backup success rates.


8. Security Alerts

| Severity |  Alerts |
| -------- | ------: |
| Low      |     862 |
| Medium   |     832 |
| High     |     801 |

Insight: The dataset contains 801 high-severity security alerts, highlighting the need for continuous security monitoring alongside backup and recovery operations.
