## Magento cron redis cache flush

Plugin made by this instructions: https://www.atwix.com/magento/scheduled-redis-cache-clean-up/

It runs redis flush-all every 3 days at 2 AM. Magento cron have to bo enabled and working!

## Instructions

If you wanna change the flush execution time, edit config.xml file and change 

```
<cron_expr>0 2 */3 * *</cron_expr>
```
corresponding to your needs.