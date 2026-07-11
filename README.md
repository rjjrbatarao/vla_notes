# vla_notes
Vision Language Action AI Models

## Introduction
Robot has predictable movement than in Humans. But humans dexterity outperforms robot from doing memorized actions.

## TODO
Investigate Fear and Pain with dynamic weights for action completion.
Fear and Pain retrains the model for efficient actions for survival training. This should be different than reinforced training like the following.

# Dynamic retraining workflow
Dynamic learning/retraining shall be incorporated only on the actions it is suppose to do.
```
Robot only know path A to go to the Finish, Robot randomly try other path and successfully found path B.
Memory - Path A
Memory - Path A,B
Robot weighs this paths and all succession of successful efficient path traversal is prioritized, Path B is still kept in memory as alternate option when path A is not possible anymore.
```

## References
```
https://medium.com/correll-lab/how-to-finetune-huggingfaces-smolvlm-dcbefc631a16
https://medium.com/@mrshahzebkhoso/i-built-and-tested-visual-language-action-from-scratch-a-beginner-friendly-guide-48c04e7c6c2a
https://medium.com/@georges.casassovici/how-to-build-a-vision-language-action-ai-model-that-controls-robots-6561c29fbeea
```
