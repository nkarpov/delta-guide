# Introduction

|Category   |Feature          |Standalone|Spark|Rust|Python|Go |
|-----------|-----------------|----------|-----|----|------|---|
|API        |Actions          | Y | N |Y   |I     |I  |
|API        |Metadata         | Y | N |Y   |I     |I  |
|API        |Files            | Y | N |Y   |Y     |?  |
|API        |Snapshot         | Y | N |Y   | N    |?  |
|API        |Transaction      | Y | N |Y   | N    |?  |
|API        |Table            | Y | Y |Y   |Y     |?  |
|API        |Scan             | Y | N |?   |?     |?  |
|Storage    |ADL              | Y | Y |Y   |Y     |?  |
|Storage    |GCP              | Y | Y |Y   |Y     |?  |
|Storage    |S3               | X | X |X   |X     |X  |
|Execution  |Distributed      | N | Y |?   |?     | N |
|DML        |CREATE           | N | Y |?   |?     |?  |
|DML        |INSERT           | N | Y |?   |?     | N |
|DML        |UPDATE           | N | Y | N  | N    | N |
|DML        |DELETE           | N | Y | N  | N    | N |
|DML        |MERGE            | N | Y | N  | N    | N |
|Maintenace |VACUUM           | N | Y | N  | N    | N |
|Maintenace |HISTORY          | N | Y | N  | N    | N |
|Maintenace |DETAIL           | N | Y | N  | N    | N |
|Maintenace |OPTIMIZE         | N | Y | Y   |?     | N |
|Maintenace |ZORDER           | N | Y | N  | N    | N |
|Feature    |CDF              | N | Y | N  | N    | N |
|Feature    |Generated Columns| N | Y | N  | N    | N |