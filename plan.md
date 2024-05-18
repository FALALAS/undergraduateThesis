# Experiment Plan

## Kernel Estimation

- UFPNet kernel $19\times19$
- train DSN with DIV2K, patch size $192\times192$
  - Canon
  - DIV2K
- train SRN
  - DIV2K
  - DIV2K + Nikon

## Ablation Study

- Kernel estimation result
  - ~~KULNet~~
  - MANet
  - UFPNet
- use the best KE model. Test on RealSR.

| add blur | add data | PSNR | SSIM |
| -------- | -------- | ---- | ---- |
| -        | -        |      |      |
| -        | +        |      |      |
| +        | -        |      |      |
| +        | +        |      |      |

## Comparison

- Test UBSR-DU on DIV2K and Canon


## Other
- problem of negative loss function