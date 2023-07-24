# Introduction

- this repository contains the Horizon product specifications

# How to contribute?

Please note that when updating product specifications that you always need to **increment the `specVersion` field** -
those specifications might be ignored otherwise by subscription vertical when being published.

## Product Spec versions

| Product                           | Product Line | File in git | Deployed Platform-INT | Deployed PROD | Deployed Product-INT |
| --------------------------------- | ------------ | ----------- | --------------------- | ------------- | -------------------- |
| Smart Parking                     | BEM          | 1           | 1                     |               | 1                    |
| Horizon Back-Office               | CBA          | 24          | 24                    | 18            | 24                   |
| Cerberus portal                   | CCA          | 37          | 37                    | 34            | 37                   |
| Building Operator                 | CLB          | 25          | 23                    | 23            | 23                   |
| Core Analytics                    | COA          | 4           | 4                     | 4             | 4                    |
| Desigo fire                       | DFR          | 31          | 31                    | 30            | 31                   |
| Edge Eco Systems                  | ECO          | 25          | 24                    | 21            | 24                   |
| Edge Digital Services             | EDS          | 15          | 15                    | 14            | 15                   |
| SI E Mobility                     | EMO          | 8           | 8                     | 7             | 8                    |
| Enlighted                         | ENL          | 2           | 2                     | 1             | 2                    |
| Fin stack                         | FIN          | 4           | 4                     | 4             | 4                    |
| Global Management Station         | GMS          | 4           | 4                     | 4             | 4                    |
| SI GSW                            | GSW          | 4           | 4                     | 3             | 4                    |
| ClimatixIC                        | ICX          | 27          | 27                    | 26            | 27                   |
| J2 Oem 01                         | J01          | 7           | 7                     | 7             | 7                    |
| J2 Oem 02                         | J02          | 7           | 7                     | 7             | 7                    |
| J2 Oem 03                         | J03          | 7           | 7                     | 7             | 7                    |
| J2 Oem 04                         | J04          | 8           | 8                     | 7             | 8                    |
| Low Complexity Automation Systems | LCS          | 3           | 3                     | 3             | 3                    |
| Desigo Remote Access              | NGA          | 10          | 10                    | 10            | 10                   |
| Desigo Optic on Cloud             | OPT          | 5           | 5                     | 5             | 5                    |
| Building X                        | SBS          | 88          | 88                    | 81            | 88                   |
| Sinteso                           | SCA          | 38          | 38                    | 37            | 38                   |
| SIMcard for data volume           | SIM          | 1           | 1                     | 1             | 1                    |
| Stencil                           | STE          | 1           | 1                     | 1             | 1                    |
| System                            | SYS          | 3           | 3                     | 3             | 3                    |

## Active features

```
sbt_cloud_access_abt
sbt_cloud_access_nga_device
sbt_cloud_access_web
sbt_cloud_account_manager_app
sbt_cloud_alarm_dashboard
sbt_cloud_api_access
sbt_cloud_asset_manager_app
sbt_cloud_ba_acvatix
sbt_cloud_ba_add-on
sbt_cloud_ba_api
sbt_cloud_ba_base
sbt_cloud_ba_inactive
sbt_cloud_ba_points_count
sbt_cloud_ba_renewable
sbt_cloud_ba_sites_count
sbt_cloud_ba_storage
sbt_cloud_ba_tunnel_count
sbt_cloud_ba_upgradable
sbt_cloud_back_base
sbt_cloud_back_inactive
sbt_cloud_support_cockpit_app
sbt_cloud_support_cockpit_base
sbt_cloud_support_cockpit_inactive
sbt_cloud_bldg_operator_app
sbt_cloud_bo_discovery_edge_app
sbt_cloud_cca_add-on
sbt_cloud_cca_api
sbt_cloud_cca_base
sbt_cloud_cca_beta_tester
sbt_cloud_cca_eds_development
sbt_cloud_cca_inactive
sbt_cloud_cca_renewable
sbt_cloud_cca_sites_count
sbt_cloud_cca_solution_test
sbt_cloud_cca_storage
sbt_cloud_cca_token_count
sbt_cloud_cca_tunnel_count
sbt_cloud_cerberus_app
sbt_cloud_climatixic_inactive
sbt_cloud_data_classifier
sbt_cloud_desigofire_app
sbt_cloud_dfr_base
sbt_cloud_dfr_beta_tester
sbt_cloud_dfr_eds_development
sbt_cloud_dfr_inactive
sbt_cloud_dfr_solution_test
sbt_cloud_dfr_token_count
sbt_cloud_edge_app_manager_app
sbt_cloud_eds_base
sbt_cloud_eds_inactive
sbt_cloud_free
sbt_cloud_ivalve_balance
sbt_cloud_nga_base
sbt_cloud_nga_device_count
sbt_cloud_nga_inactive
sbt_cloud_reno
sbt_cloud_rule_engine
sbt_cloud_sbs_core
sbt_cloud_sbs_inactive
sbt_cloud_sca_base
sbt_cloud_sca_beta_tester
sbt_cloud_sca_eds_development
sbt_cloud_sca_inactive
sbt_cloud_sca_solution_test
sbt_cloud_sca_token_count
sbt_cloud_sinteso_app
sbt_cloud_explore_base
```

## Partition id in Events

6abc4628-6c7e-4f0d-86b9-caf14a1f1020
