docker run -d --name aerospike \
  -p 3000:3000 -p 3001:3001 -p 3002:3002 -p 3003:3003 \
  -v $(pwd)/aerospike.conf:/etc/aerospike/aerospike.conf:ro \
  aerospike/aerospike-server
