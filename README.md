## ElizaOS + Hedera plugin Test environment

### Quickstart
1. clone repository `git clone https://github.com/mateuszm-arianelabs/eliza-hedera-testing.git`
2. copy env variables `cp .env.example .env` and fill this values
```
HEDERA_ACCOUNT_ID=
HEDERA_PRIVATE_KEY=
HEDERA_PUBLIC_KEY=
HEDERA_NETWORK_TYPE=
HEDERA_KEY_TYPE=
OPENAI_API_KEY=
```
3. run with `pnpm run` and enjoy

### Troubleshooting
- If `eliza-starter` does not start, use `pnpm approve-builds`, select `better-sqlite3` and `hedera-plugin`, then type `Y` to rebuild these packages. If you dont see these packages, delete `pnpm-lock` and `node_modules`.