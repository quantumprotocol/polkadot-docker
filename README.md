docker run -d -p 39333:30333 -p 39933:9933 -p 39944:9944 -v /root/mylocalchaindata:/chaindata parity/polkadot:latest --chain kusama --base-path /chaindata --rpc-methods Safe --ws-external --rpc-external --rpc-cors all --name "RunOnFlux"