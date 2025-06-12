

curl -vvv http://localhost:8000/v1/completions \
    -H "Content-Type: application/json" \
    -d '{
    "model": "ibm-granite/granite-3.3-2b-base",
    "prompt": "Hello, "
}'

curl -vvv http://localhost:8000/v1/completions \
    -H "Content-Type: application/json" \
    -H "x-model-name: ibm-granite/granite-3.3-2b-base" \
    -d '{
    "model": "ibm-granite/granite-3.3-2b-base",
    "prompt": "Hello, "
}'


--- 


curl -vvv http://localhost:8000/v1/completions \
    -H "Content-Type: application/json" \
    -d '{
    "model": "facebook/opt-125m",
    "prompt": "Hello, "
}'

curl -vvv http://localhost:8000/v1/completions \
    -H "Content-Type: application/json" \
    -H "x-model-name: facebook/opt-125m" \
    -d '{
    "model": "ibm-granite/granite-3.3-2b-base",
    "prompt": "Hello, "
}'


--- 
curl -vvv http://localhost:8000/v1/completions \
    -H "Content-Type: application/json" \
    -H "x-model-name: ibm-granite/granite-3.3-2b-instruct" \
    -d '{
    "model": "ibm-granite/granite-3.3-2b-instruct",
    "prompt": "Hello, "
}'


curl -vvv http://localhost:8000/v1/completions \
    -H "Content-Type: application/json" \
    -H "x-model-name: ibm-granite/granite-3.3-2b-base" \
    -d '{
    "model": "ibm-granite/granite-3.3-2b-base",
    "prompt": "Hello, "
}'