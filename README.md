# NFT MarketPlace BackEnd
The NFT MarketPlace BackEnd wrote by java spring boot  collecting data using csv file from [OpenSea](https://opensea.io), using PostgreSQL and TimescaleDB cloud db.

Give you a foundation for analyzing NFT trends so that you can bring some data to your purchasing decisions, or just learn about the NFT space from a data-driven perspective.

## Instructions
### Login to timescale cloud db
    pass:
    username:
###  Ways to connect to timescale cloud db
1. Using psql cmd:
    ```bash
    cd C:\Program Files\PostgreSQL\14\bin
    running following command:
    psql "postgres://tsdbadmin@mnagb5hgur.jlygpztdwe.tsdb.cloud.timescale.com:35802/tsdb?sslmode=require"
    ```
2. Using PgAdmin
    * Open PgAdmin => new connection=>read application properties

3. Using Intelij:
    * Add datasource => postgresql=>read application properties
