# Description

Function to create coupons using GravityForm plugin and insert in HubSpot by properties

## Installation

Paste this function on your function.php on your theme Wordpress. Function create_coupon_from_hs is planned to be executed each some amount of time. To allow it to install [WP Crontrol](https://github.com/johnbillion/wp-crontrol/wiki) plugin

## Wp configuration

```bash
[{
    "token": "YOURHUBSPOTTOKENAPI",
    "lifecycle_stage": "opportunity",
    "couponname": "COUPON_NUTRICION",
    "couponamounttype": "percentage",
    "couponamount": 1,
    "enddate":3,
    "usagelimit": "1",
    "isstackable": false,
    "usagecount": 0,
    "gfnumber": "ID OF FORM TO APPLY DESCOUNT -> STR",
    "limit_query": 100,
    "filter_properties": "lifecyclestage", 
    "coupon": "cupon_nutricion"
}]
```


## Suport documentation

[Hubpost](https://developers.hubspot.com/docs/api/crm/contacts)

[Coupons Feed Meta](https://docs.gravityforms.com/coupons-feed-meta/)

[WP-Plugin](https://wetopi.com/how-to-run-a-cron-job-with-wordpress/)
