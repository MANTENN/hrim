# Hrim

Hrim is a serverless first JavaScript framework for building out APIs. The goal is to build out with serverless infra and overtime switch over to monolith architecture once the request rate hits a stable baseline and use a hybrid model with serverless functions to act as a temporary buffer while more virtual machine instances are provisioned to reduce p99 times where some instances may have a cold start of 2-3 minutes. 
