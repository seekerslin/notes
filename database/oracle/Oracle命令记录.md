# Oracle命令记录

Oracle 11g导出空表

```sql
select 'alter table ' ||table_name ||' allocate extent;' from user_tables where segment_created='NO';
```

