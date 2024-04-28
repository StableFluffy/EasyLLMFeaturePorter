# EasyLLMFeaturePorter

1-Click is all you need.

## Methodology
1. Get diff between base model and context expanded model.
2. Get diff between base model and finetuned model(model to expand context). Then use this diff to calculate activation ratio.
3. Add diff * activation ratio to finetuned model.

Done !

### Explanation
[Korean](https://arca.live/b/alpaca/104827551)

### Special Thanks

Thanks to kuotient for letting me know issue on initial commit. [Huggingface](https://huggingface.co/kuotient)

Thanks to [Sionic Ai](https://sionic.ai/) for providing A100 cluster.
