# weky-v14: Discord Mini-Games for discord.js v14

**weky-v14** brings the popular **weky** mini-games to **discord.js v14**: Snake, Trivia, Fast Type, Would You Rather, Rock Paper Scissors and more, ready to drop into any Discord bot. Package name: `@drix10/weky-v14`.

![discord.js](https://img.shields.io/badge/discord.js-v14-5865F2?logo=discord&logoColor=white)

## Games

Calculator · Chaos Words · Fast Type · Fight · Guess The Number · Guess The Pokémon · Lie Swatter · Never Have I Ever · Quick Click · Quick Find · Rock Paper Scissors · Shuffle Guess · Snake · Sudo · Trivia · Will You Press The Button · Would You Rather

The package picks the discord.js v12 or v14 implementation automatically from your bot's `discord.js` version.

## Example

```js
const { Snake } = require('@drix10/weky-v14');

await Snake({
  message: message,
  embed: {
    title: 'Snake',
    description: 'GG, you scored **{{score}}** points!',
    color: '#5865F2',
    timestamp: true,
  },
  emojis: { empty: '⬛', snakeBody: '🟩', food: '🍎', up: '⬆️', down: '⬇️', left: '⬅️', right: '➡️' },
  othersMessage: 'Only <@{{author}}> can use the buttons!',
  buttonText: 'Cancel',
});
```

Every game has a full example in [`Examples/`](Examples/).

## Credits

Based on the original **weky** package by its authors (Face, Sujal Goel and rayz), updated for discord.js v14 by [Drix10](https://github.com/Drix10).


<!-- drix10-footer -->
---

<div align="center">

**Built by [Drishtant Ghosh (Drix10)](https://drix10.com)** · AI systems engineer and 1x acquired founder, Bengaluru

[Portfolio](https://drix10.com) · [LinkedIn](https://www.linkedin.com/in/drix10) · [X](https://x.com/DrishtantGhosh) · [Blog](https://blogs.drix10.com) · [All projects](https://github.com/Drix10)

<sub>More from Drix10: [Agent Flow](https://github.com/Drix10/agent-flow) (guardrails for AI coding agents) · [MiroHedge](https://github.com/Drix10/hypothesis-arena) (AI-assisted systematic fund) · [Guardian](https://github.com/Drix10/guardian-gpt) (UPI scam interceptor) · [Sentinel](https://github.com/Drix10/sentinal) (AI security CLI) · [Keystroke-LLM](https://github.com/Drix10/keystroke-llm) (NumPy transformer on a keyboard) · [AI Resources](https://github.com/Drix10/ai-resources) (daily AI knowledge base)</sub>

</div>
