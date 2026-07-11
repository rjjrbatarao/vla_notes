# vla_notes
Vision Language Action AI Models

## Introduction
Robot has predictable movement than in Humans. But humans dexterity outperforms robot from doing memorized actions.

## TODO
Investigate Fear and Pain with dynamic weights for action completion.
Fear and Pain retrains the model for efficient actions for survival training. This should be different than reinforced training like the following.
```
Models will incorporate concept of Death meaning final retrained model if actions unsuccessfull will all fall to unactionable output or nothingness.
```
## Dynamic retraining workflow without Fear and Pain
Dynamic learning/retraining shall be incorporated only on the actions it is suppose to do.
```
Robot only know path A to go to the Finish, Robot randomly try other path and successfully found path B.
Memory - Path A
Memory - Path A,B
Robot weighs this paths and all succession of successful efficient path traversal is prioritized, Path B is still kept in memory as alternate option when path A is not possible anymore.
```

## Dynamic retraining workflow with Fear and Pain
Dynamic learning/retraining shall be incorporated only on the actions it is suppose to do.
```
Robot only know path A to go to the Finish, Robot randomly try other path and successfully found path B. (Predators, dangerous paths and warning signs will be incorporated).
Memory - Path A
Memory - Path A,B
Robot weighs this paths(efficiency, fear and pain levels) and all succession of successful path traversal based on the 3 weights are prioritized, Path B is still kept in memory as alternate option when path A is not possible anymore.
```

## Experiments
```
Make robot escape from a maze(with time difficulty).
Handcuffed robot arm (how to unhandcuf).
Unstuck autonomous rover from gravel etc.
```

## References
```
https://medium.com/correll-lab/how-to-finetune-huggingfaces-smolvlm-dcbefc631a16
https://medium.com/@mrshahzebkhoso/i-built-and-tested-visual-language-action-from-scratch-a-beginner-friendly-guide-48c04e7c6c2a
https://medium.com/@georges.casassovici/how-to-build-a-vision-language-action-ai-model-that-controls-robots-6561c29fbeea
```
