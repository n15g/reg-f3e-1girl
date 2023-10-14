# Regularization Images - Forge - Female Subject

Stable Diffusion training regularization images. Used during LoRA training to reinforce the underlying model and
reduce overfitting.

|             |                                                  |
|-------------|--------------------------------------------------|
| Model       | [f3e - Forge](https://civitai.com/models/160315) |
| Class Tag   | `1girl`                                          |
| Cardinality | 2019 images                                      |
| VAE         | Built-in from f3e v1.0                           |

## Usage
In the Kohya_SS GUI, select this project directory as the `Regularisation folder` during training.

**Note**: Only use these regularization images if training against the f3e model. Training with regularization images
from a different model will heavily bake that style into the result.
