# Samples

CheckPostgresReplicationStatus OK: replication delayed by 244.94459533691406MB :: master:9B9/D3A82348 slave:9B9/E2F74058 m_segbytes:16777216

## Metrics

cduong13-MacBook-Pro.local.postgres.replication_lag -357456 1470996842

bin/metric-postgres-locks.rb    
cduong13-MacBook-Pro.local.postgresql.locks.postgres.accesssharelock 1 1470997202

bin/metric-postgres-statsbgwriter.rb
cduong13-MacBook-Pro.local.postgresql.bgwriter.checkpoints_timed 862 1470997272
cduong13-MacBook-Pro.local.postgresql.bgwriter.checkpoints_req 43 1470997272
cduong13-MacBook-Pro.local.postgresql.bgwriter.buffers_checkpoint 45559343 1470997272
cduong13-MacBook-Pro.local.postgresql.bgwriter.buffers_clean 12873752 1470997272
cduong13-MacBook-Pro.local.postgresql.bgwriter.maxwritten_clean 114462 1470997272
cduong13-MacBook-Pro.local.postgresql.bgwriter.buffers_backend 29874842 1470997272
cduong13-MacBook-Pro.local.postgresql.bgwriter.buffers_alloc 107005135 1470997272

bin/metric-postgres-statsdb.rb
cduong13-MacBook-Pro.local.postgresql.statsdb.postgres.xact_commit 126 1470997739
cduong13-MacBook-Pro.local.postgresql.statsdb.postgres.xact_rollback 0 1470997739
cduong13-MacBook-Pro.local.postgresql.statsdb.postgres.blks_read 820 1470997739
cduong13-MacBook-Pro.local.postgresql.statsdb.postgres.blks_hit 3627 1470997739
cduong13-MacBook-Pro.local.postgresql.statsdb.postgres.tup_returned 5279 1470997739
cduong13-MacBook-Pro.local.postgresql.statsdb.postgres.tup_fetched 2656 1470997739
cduong13-MacBook-Pro.local.postgresql.statsdb.postgres.tup_inserted 0 1470997739
cduong13-MacBook-Pro.local.postgresql.statsdb.postgres.tup_updated 0 1470997739
cduong13-MacBook-Pro.local.postgresql.statsdb.postgres.tup_deleted 0 1470997739

bin/metric-postgres-statsio.rb
cduong13-MacBook-Pro.local.postgresql.statsio.postgres.heap_blks_read
cduong13-MacBook-Pro.local.postgresql.statsio.postgres.heap_blks_hit
cduong13-MacBook-Pro.local.postgresql.statsio.postgres.idx_blks_read
cduong13-MacBook-Pro.local.postgresql.statsio.postgres.idx_blks_hit
cduong13-MacBook-Pro.local.postgresql.statsio.postgres.toast_blks_read
cduong13-MacBook-Pro.local.postgresql.statsio.postgres.toast_blks_hit
cduong13-MacBook-Pro.local.postgresql.statsio.postgres.tidx_blks_read
cduong13-MacBook-Pro.local.postgresql.statsio.postgres.tidx_blks_hit
