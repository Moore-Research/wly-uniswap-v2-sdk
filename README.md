# wly-uniswap-v2-sdk
fork uniswap-v2-sdk 
用于上传至npm，保证自己的仿uniswap前端交互页面可用 
## 具体修改数据为
1. 工厂合约地址
2. INIT_CODE_HASH
3. 链id
4. WETH

```
./src/constants.ts  
    - ChainId  
    - FACTORY_ADDRESS  
    - INIT_CODE_HASH  
./src/entities/token.ts
    - WETH
```
