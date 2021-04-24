# Graftorio - OFSM

visualize metrics from your factorio game in grafana

![](https://mods-data.factorio.com/assets/89653f5de75cdb227b5140805d632faf41459eee.png)

## What is this?

All the credit goes to: [Graftorio](https://github.com/TheVirtualCrew/graftorio) and [OFSM](https://github.com/OpenFactorioServerManager/factorio-server-manager).
I put both of these projects together to make it easy to deploy and monitor factorio servers. I personnally use this to play with my friends, and I host this on GCP.

## Installation

1. `cd` into the directory
2. `docker-compose up`
3. aaaaaaaaaaaaaaand you're done


## Grafana

The makers of this repo have included some dashboards copied from [stats.nilaus.tv](https://stats.nilaus.tv) in the dashboards directory.
Keep in mind that when the server is paused grafana doesn't get any info. If you have an always on server this should reflect nicely what is happening in the base.