## Start bootnode:

    bootnode -nodekey bootnodekey -verbosity 9 -addr ":30300"


## Start 4 node    
   
    gev --datadir node1/data --syncmode full --networkid 18 --mine \
    --bootnodes "enode://8eac9c8edc1681a1cc93b01efc39315f7e5db4704703e086d9f18378ef1bb85c433f8bd89ab846d1eb76bdc3af7183f4a590ad58db174300dc885a7bf6249021@127.0.0.1:0?discport=30300" \
    --gcmode archive \
    --rpc --rpcaddr 0.0.0.0 --rpccorsdomain "*" --rpcvhosts "*" --rpcport 22001 --port 30301 \
    --rpcapi admin,db,eth,evr,debug,miner,net,shh,txpool,personal,web3
    
    gev --datadir node2/data --syncmode full --networkid 18 --mine \
    --bootnodes "enode://8eac9c8edc1681a1cc93b01efc39315f7e5db4704703e086d9f18378ef1bb85c433f8bd89ab846d1eb76bdc3af7183f4a590ad58db174300dc885a7bf6249021@127.0.0.1:0?discport=30300" \
    --gcmode archive \
    --rpc --rpcaddr 0.0.0.0 --rpccorsdomain "*" --rpcvhosts "*" --rpcport 22002 --port 30302 \
    --rpcapi admin,db,eth,evr,debug,miner,net,shh,txpool,personal,web3
    
    gev --datadir node3/data --syncmode full --networkid 18 --mine \
    --bootnodes "enode://8eac9c8edc1681a1cc93b01efc39315f7e5db4704703e086d9f18378ef1bb85c433f8bd89ab846d1eb76bdc3af7183f4a590ad58db174300dc885a7bf6249021@127.0.0.1:0?discport=30300" \
    --gcmode archive \
    --rpc --rpcaddr 0.0.0.0 --rpccorsdomain "*" --rpcvhosts "*" --rpcport 22003 --port 30303 \
    --rpcapi admin,db,eth,evr,debug,miner,net,shh,txpool,personal,web3
    
    gev --datadir node4/data --syncmode full --networkid 18 --mine \
    --bootnodes "enode://8eac9c8edc1681a1cc93b01efc39315f7e5db4704703e086d9f18378ef1bb85c433f8bd89ab846d1eb76bdc3af7183f4a590ad58db174300dc885a7bf6249021@127.0.0.1:0?discport=30300" \
    --gcmode archive \
    --rpc --rpcaddr 0.0.0.0 --rpccorsdomain "*" --rpcvhosts "*" --rpcport 22004 --port 30304 \
    --rpcapi admin,db,eth,evr,debug,miner,net,shh,txpool,personal,web3
    
