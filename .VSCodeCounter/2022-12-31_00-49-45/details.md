# Details

Date : 2022-12-31 00:49:45

Directory d:\\project\\python\\JoJoGAN

Total : 76 files,  8626 codes, 250 comments, 1372 blanks, all 10248 lines

[Summary](results.md) / Details / [Diff Summary](diff.md) / [Diff Details](diff-details.md)

## Files
| filename | language | code | comment | blank | total |
| :--- | :--- | ---: | ---: | ---: | ---: |
| [README.md](/README.md) | Markdown | 38 | 0 | 16 | 54 |
| [cog.yaml](/cog.yaml) | YAML | 21 | 0 | 0 | 21 |
| [e4e/README.md](/e4e/README.md) | Markdown | 122 | 0 | 21 | 143 |
| [e4e/configs/__init__.py](/e4e/configs/__init__.py) | Python | 0 | 0 | 1 | 1 |
| [e4e/configs/data_configs.py](/e4e/configs/data_configs.py) | Python | 39 | 0 | 3 | 42 |
| [e4e/configs/paths_config.py](/e4e/configs/paths_config.py) | Python | 18 | 5 | 6 | 29 |
| [e4e/configs/transforms_config.py](/e4e/configs/transforms_config.py) | Python | 50 | 0 | 13 | 63 |
| [e4e/criteria/__init__.py](/e4e/criteria/__init__.py) | Python | 0 | 0 | 1 | 1 |
| [e4e/criteria/id_loss.py](/e4e/criteria/id_loss.py) | Python | 42 | 0 | 6 | 48 |
| [e4e/criteria/lpips/__init__.py](/e4e/criteria/lpips/__init__.py) | Python | 0 | 0 | 1 | 1 |
| [e4e/criteria/lpips/lpips.py](/e4e/criteria/lpips/lpips.py) | Python | 17 | 8 | 11 | 36 |
| [e4e/criteria/lpips/networks.py](/e4e/criteria/lpips/networks.py) | Python | 68 | 1 | 27 | 96 |
| [e4e/criteria/lpips/utils.py](/e4e/criteria/lpips/utils.py) | Python | 19 | 3 | 9 | 31 |
| [e4e/criteria/moco_loss.py](/e4e/criteria/moco_loss.py) | Python | 57 | 6 | 9 | 72 |
| [e4e/criteria/w_norm.py](/e4e/criteria/w_norm.py) | Python | 10 | 0 | 5 | 15 |
| [e4e/datasets/__init__.py](/e4e/datasets/__init__.py) | Python | 0 | 0 | 1 | 1 |
| [e4e/datasets/gt_res_dataset.py](/e4e/datasets/gt_res_dataset.py) | Python | 24 | 2 | 7 | 33 |
| [e4e/datasets/images_dataset.py](/e4e/datasets/images_dataset.py) | Python | 25 | 0 | 9 | 34 |
| [e4e/datasets/inference_dataset.py](/e4e/datasets/inference_dataset.py) | Python | 20 | 0 | 6 | 26 |
| [e4e/editings/ganspace.py](/e4e/editings/ganspace.py) | Python | 17 | 1 | 5 | 23 |
| [e4e/editings/ganspace_pca/cars_pca.pt](/e4e/editings/ganspace_pca/cars_pca.pt) | XML | 1,083 | 0 | 4 | 1,087 |
| [e4e/editings/ganspace_pca/ffhq_pca.pt](/e4e/editings/ganspace_pca/ffhq_pca.pt) | XML | 1,101 | 0 | 4 | 1,105 |
| [e4e/editings/interfacegan_directions/age.pt](/e4e/editings/interfacegan_directions/age.pt) | XML | 30 | 0 | 0 | 30 |
| [e4e/editings/interfacegan_directions/pose.pt](/e4e/editings/interfacegan_directions/pose.pt) | XML | 297 | 0 | 0 | 297 |
| [e4e/editings/interfacegan_directions/smile.pt](/e4e/editings/interfacegan_directions/smile.pt) | XML | 22 | 0 | 0 | 22 |
| [e4e/editings/latent_editor.py](/e4e/editings/latent_editor.py) | Python | 34 | 4 | 8 | 46 |
| [e4e/editings/sefa.py](/e4e/editings/sefa.py) | Python | 35 | 1 | 11 | 47 |
| [e4e/environment/e4e_env.yaml](/e4e/environment/e4e_env.yaml) | YAML | 72 | 0 | 2 | 74 |
| [e4e/metrics/LEC.py](/e4e/metrics/LEC.py) | Python | 81 | 27 | 27 | 135 |
| [e4e/models/__init__.py](/e4e/models/__init__.py) | Python | 0 | 0 | 1 | 1 |
| [e4e/models/discriminator.py](/e4e/models/discriminator.py) | Python | 15 | 0 | 6 | 21 |
| [e4e/models/encoders/__init__.py](/e4e/models/encoders/__init__.py) | Python | 0 | 0 | 1 | 1 |
| [e4e/models/encoders/helpers.py](/e4e/models/encoders/helpers.py) | Python | 99 | 19 | 23 | 141 |
| [e4e/models/encoders/model_irse.py](/e4e/models/encoders/model_irse.py) | Python | 58 | 9 | 18 | 85 |
| [e4e/models/encoders/psp_encoders.py](/e4e/models/encoders/psp_encoders.py) | Python | 173 | 1 | 27 | 201 |
| [e4e/models/latent_codes_pool.py](/e4e/models/latent_codes_pool.py) | Python | 33 | 17 | 6 | 56 |
| [e4e/models/psp.py](/e4e/models/psp.py) | Python | 82 | 3 | 15 | 100 |
| [e4e/models/stylegan2/__init__.py](/e4e/models/stylegan2/__init__.py) | Python | 0 | 0 | 1 | 1 |
| [e4e/models/stylegan2/model.py](/e4e/models/stylegan2/model.py) | Python | 497 | 3 | 179 | 679 |
| [e4e/models/stylegan2/op/__init__.py](/e4e/models/stylegan2/op/__init__.py) | Python | 0 | 0 | 1 | 1 |
| [e4e/models/stylegan2/op/fused_act.py](/e4e/models/stylegan2/op/fused_act.py) | Python | 61 | 0 | 25 | 86 |
| [e4e/models/stylegan2/op/fused_bias_act.cpp](/e4e/models/stylegan2/op/fused_bias_act.cpp) | C++ | 15 | 0 | 6 | 21 |
| [e4e/models/stylegan2/op/fused_bias_act_kernel.cu](/e4e/models/stylegan2/op/fused_bias_act_kernel.cu) | CUDA C++ | 71 | 5 | 23 | 99 |
| [e4e/models/stylegan2/op/upfirdn2d.cpp](/e4e/models/stylegan2/op/upfirdn2d.cpp) | C++ | 17 | 0 | 6 | 23 |
| [e4e/models/stylegan2/op/upfirdn2d.py](/e4e/models/stylegan2/op/upfirdn2d.py) | Python | 145 | 2 | 38 | 185 |
| [e4e/models/stylegan2/op/upfirdn2d_kernel.cu](/e4e/models/stylegan2/op/upfirdn2d_kernel.cu) | CUDA C++ | 208 | 5 | 59 | 272 |
| [e4e/notebooks/inference_playground.ipynb](/e4e/notebooks/inference_playground.ipynb) | JSON | 588 | 0 | 0 | 588 |
| [e4e/options/__init__.py](/e4e/options/__init__.py) | Python | 0 | 0 | 1 | 1 |
| [e4e/options/train_options.py](/e4e/options/train_options.py) | Python | 66 | 4 | 15 | 85 |
| [e4e/scripts/calc_losses_on_images.py](/e4e/scripts/calc_losses_on_images.py) | Python | 72 | 0 | 16 | 88 |
| [e4e/scripts/inference.py](/e4e/scripts/inference.py) | Python | 106 | 1 | 27 | 134 |
| [e4e/scripts/train.py](/e4e/scripts/train.py) | Python | 66 | 3 | 20 | 89 |
| [e4e/training/__init__.py](/e4e/training/__init__.py) | Python | 0 | 0 | 1 | 1 |
| [e4e/training/coach.py](/e4e/training/coach.py) | Python | 359 | 15 | 64 | 438 |
| [e4e/training/ranger.py](/e4e/training/ranger.py) | Python | 84 | 41 | 39 | 164 |
| [e4e/utils/__init__.py](/e4e/utils/__init__.py) | Python | 0 | 0 | 1 | 1 |
| [e4e/utils/alignment.py](/e4e/utils/alignment.py) | Python | 82 | 15 | 19 | 116 |
| [e4e/utils/common.py](/e4e/utils/common.py) | Python | 43 | 2 | 11 | 56 |
| [e4e/utils/data_utils.py](/e4e/utils/data_utils.py) | Python | 16 | 4 | 6 | 26 |
| [e4e/utils/model_utils.py](/e4e/utils/model_utils.py) | Python | 27 | 0 | 9 | 36 |
| [e4e/utils/train_utils.py](/e4e/utils/train_utils.py) | Python | 12 | 0 | 2 | 14 |
| [e4e_projection.py](/e4e_projection.py) | Python | 31 | 0 | 5 | 36 |
| [model.py](/model.py) | Python | 496 | 3 | 172 | 671 |
| [op/__init__.py](/op/__init__.py) | Python | 0 | 0 | 1 | 1 |
| [op/conv2d_gradfix.py](/op/conv2d_gradfix.py) | Python | 182 | 0 | 46 | 228 |
| [op/fused_act.py](/op/fused_act.py) | Python | 93 | 0 | 35 | 128 |
| [op/fused_act_cpu.py](/op/fused_act_cpu.py) | Python | 30 | 0 | 12 | 42 |
| [op/fused_bias_act.cpp](/op/fused_bias_act.cpp) | C++ | 15 | 0 | 6 | 21 |
| [op/fused_bias_act_kernel.cu](/op/fused_bias_act_kernel.cu) | CUDA C++ | 71 | 5 | 23 | 99 |
| [op/upfirdn2d.cpp](/op/upfirdn2d.cpp) | C++ | 17 | 0 | 6 | 23 |
| [op/upfirdn2d.py](/op/upfirdn2d.py) | Python | 145 | 2 | 41 | 188 |
| [op/upfirdn2d_cpu.py](/op/upfirdn2d_cpu.py) | Python | 46 | 0 | 15 | 61 |
| [op/upfirdn2d_kernel.cu](/op/upfirdn2d_kernel.cu) | CUDA C++ | 208 | 5 | 59 | 272 |
| [predict.py](/predict.py) | Python | 160 | 11 | 40 | 211 |
| [stylize.ipynb](/stylize.ipynb) | JSON | 628 | 0 | 0 | 628 |
| [util.py](/util.py) | Python | 167 | 17 | 32 | 216 |

[Summary](results.md) / Details / [Diff Summary](diff.md) / [Diff Details](diff-details.md)