# Splunk Queries Used

## Search by Source IP
src_ip=10.20.2.17

## Correlate Destination IP
src_ip=10.20.2.17 dest_ip=67.199.248.11

## Time-based investigation
src_ip=10.20.2.17 earliest=-30m latest=now

## URL investigation
url="*bit.ly*"
