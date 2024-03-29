# 1 元购智能合约项目

## 业务逻辑

1. 管理员/用户发起一个“一元购”
2. 用户支付 1 元加入一元购
3. 金额达标后自动进入采购
4. 后续发货等流程

## 如何开始

```bash
# 安装依赖
pnpm i

# 启用本地测试网
pnpm local-network

# 编译合约
pnpm compile

# 测试合约
pnpm test

# 部署合约到本地测试网
pnpm deploy-local
```

```shell
npx hardhat help
# Test (npx hardhat test)
pnpm test
REPORT_GAS=true npx hardhat test
npx hardhat node

# Deploy contract
npx hardhat run scripts/deploy.ts
```
