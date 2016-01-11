# Deployment of Web Applications Course
##### _Week 2 Assignment: Your Portfolio, Live to the World!_
Jessica J. Hernandez

Full Sail University

Professor Chris Chapman

201601-01 Online

## Single-Tier Server Architecture Requirements
* Linux Ubuntu v12.04.5 LTS
* Git v1.7.9.5 
* Apache v2.4.16
* PHP v5.5.30
* MySQL v5.5.46
* Laravel Framework v5.1.25 LTS (where needed)
... Composer v1.0 needed for Laravel
... Documentation found at: [https://laravel.com/docs/5.1](https://laravel.com/docs/5.1)

## Version Numbering
* When releasing new versions the pattern to follow is Release Version (dot) Production Release ++ (dot) Staged Release ++. (v##.##.##)
* Each time a new feature is promoted to the staging server increment the Staged Release value by one.
* Each time a Production promotion occurs increment the Production Release Value by one.
* Additionally on Production Promotions reset the Staged Release value to zero.

