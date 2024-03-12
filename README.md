# phi

candle-phi: 1.3b and 2.7b LLM with state of the art performance for &lt;10b models.

```sh
 cargo run -- --model 2  --prompt "A skier slides down a frictionless slope of height 40m and length 80m. What's the skier speed at the bottom?"
```

## Cuda

Compute Capability.
bfloat16 kernels should be available from 8.0, float16 kernels from 5.3, older versions might work but you would have to give it a try.
