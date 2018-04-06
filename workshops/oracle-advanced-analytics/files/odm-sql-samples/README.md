# Example Oracle Data Miner Scripts
Samples taken downloaded http://www.oracle.com/technetwork/database/options/advanced-analytics/odm/odm-samples-194497.html 

## About 
Oracle Advanced Analytics has 

### Getting Started 
**Install the Oracle Data Miner repository!** See the directions documentation, here https://docs.oracle.com/cd/E55747_01/doc.41/e58244/GUID-B6792DA2-CECB-4692-9927-2C6D11CCE8D5.htm#DMRIG160 
this means either installing through the GUI in SQL Developer or running the `@installodmr USERS TEMP` script 

**Install the SH Sample Schema!** This is as simple as running `sqlplus` as `sys` and then running the following scripts 
```sql
@?/demo/schema/human_resources/hr_main.sql;
@?/demo/schema/order_entry/oe_main.sql;
@?/demo/schema/product_media/pm_main.sql;
@?/demo/schema/info_exchange/ix_main.sql;
@?/demo/schema/sales_history/sh_main.sql;
```
, see https://docs.oracle.com/database/121/COMSC/installation.htm#COMSC001 

The sample shcemas are also available at [github.com/oracle/db-sample-schemas](https://github.com/oracle/db-sample-schemas)

## List of Scripts

- [dmaidemo.sql]()
- [dmardemo.sql]()
- [dmdtdemo.sql]()
- [dmdtxvlddemo.sql]()
- [dmemdemo.sql]()
- [dmglcdem.sql]()
- [dmglrdem.sql]()
- [dmkmdemo.sql]()
- [dmnbdemo.sql]()
- [dmnmdemo.sql]()
- [dmocdemo.sql]()
- [dmpartdemo.sql]()
- [dmraidemo.sql]()
- [dmrardemo.sql]()
- [dmrdtdemo.sql]()
- [dmrglmdemo.sql]()
- [dmrkmdemo.sql]()
- [dmrnndemo.sql]()
- [dmrpcademo.sql]()
- [dmrrfdemo.sql]()
- [dmstardemo.sql]()
- [dmsvcdem.sql]()
- [dmsvddemo.sql]()
- [dmsvodem.sql]()
- [dmsvrdem.sql]()