# CAP
Consistency
Availability
Partition tolerance

## MongoDB - CP
Здесь на первый план поставлена консистентность, поэтому при
потере связи, могут быть проблемы с доступностью, чтобы сохранить консистентность.

## MSSQL - CA
Как и все RDBMS где нужно гарантировать ACID

## Cassandra - AP
Там сделано по принципу BASE, возможна временная неконсистентность