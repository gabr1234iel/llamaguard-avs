## Llama Guard AVS



### prerequisites:
- Foundry
- ollama



### run instructions: 

1. install llamaguard and run locally
`ollama run llama-guard3:1b`

2. run local anvil chain
`anvil --chain-id 31337 --fork-url https://eth-mainnet.g.alchemy.com/v2/<YOUR ALCHEMY API KEY>`

3. replace .env-example with generated privatekeys in anvil in a `.env` file

4. open two more terminals and run `bun run createTask.ts` and `bun run respondToTask.ts`

5. you can modify the createTask.ts arrays to see different responses.

