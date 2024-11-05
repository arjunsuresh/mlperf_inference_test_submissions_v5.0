Please download [summary.xlsx](summary.xlsx) to view the most recent results. 
 ```
[2024-11-05 19:30:28,490 submission_checker1.py:3108 INFO] Results=32, NoResults=0, Power Results=0
[2024-11-05 19:30:28,490 submission_checker1.py:3115 INFO] ---
[2024-11-05 19:30:28,491 submission_checker1.py:3116 INFO] Closed Results=2, Closed Power Results=0

[2024-11-05 19:30:28,491 submission_checker1.py:3121 INFO] Open Results=30, Open Power Results=0

[2024-11-05 19:30:28,491 submission_checker1.py:3126 INFO] Network Results=0, Network Power Results=0

[2024-11-05 19:30:28,491 submission_checker1.py:3131 INFO] ---
[2024-11-05 19:30:28,491 submission_checker1.py:3133 INFO] Systems=25, Power Systems=0
[2024-11-05 19:30:28,491 submission_checker1.py:3137 INFO] Closed Systems=1, Closed Power Systems=0
[2024-11-05 19:30:28,491 submission_checker1.py:3142 INFO] Open Systems=25, Open Power Systems=0
[2024-11-05 19:30:28,491 submission_checker1.py:3147 INFO] Network Systems=0, Network Power Systems=0
[2024-11-05 19:30:28,491 submission_checker1.py:3152 INFO] ---
[2024-11-05 19:30:28,491 submission_checker1.py:3157 INFO] SUMMARY: submission looks OK
INFO:root:       ! call "postprocess" from /home/runner/CM/repos/mlcommons@cm4mlops/script/run-mlperf-inference-submission-checker/customize.py

```

|    | Organization   | Availability   | Division   | SystemType   | SystemName            | Platform                                                               | Model               | MlperfModel         | Scenario   |       Result | Accuracy                                                       |   number_of_nodes | host_processor_model_name       |   host_processors_per_node |   host_processor_core_count | accelerator_model_name   |   accelerators_per_node | Location                                                                                                       | framework           | operating_system                                | notes                             |   compliance |   errors | version   |   inferred | has_power   | Units     | weight_data_types   |
|---:|:---------------|:---------------|:-----------|:-------------|:----------------------|:-----------------------------------------------------------------------|:--------------------|:--------------------|:-----------|-------------:|:---------------------------------------------------------------|------------------:|:--------------------------------|---------------------------:|----------------------------:|:-------------------------|------------------------:|:---------------------------------------------------------------------------------------------------------------|:--------------------|:------------------------------------------------|:----------------------------------|-------------:|---------:|:----------|-----------:|:------------|:----------|:--------------------|
|  0 | MLCommons      | available      | open       | edge         | gh_macos-latest_x86   | gh_macos-latest_x86-reference-cpu-pytorch_v2.4.1-default_config        | retinanet           | retinanet           | Offline    |     0.350957 | mAP: 76.951                                                    |                 1 | undefined                       |                          1 |                           3 | nan                      |                       0 | open/MLCommons/results/gh_macos-latest_x86-reference-cpu-pytorch_v2.4.1-default_config/retinanet/offline       | pytorch v2.4.1      | (darwin-23.6.0)                                 | Automated by MLCommons CM v3.2.3. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
|  1 | MLCommons      | available      | open       | edge         | gh_windows-latest     | gh_windows-latest-reference-cpu-onnxruntime_v1.19.2-default_config     | retinanet           | retinanet           | Offline    |     0.349311 | mAP: 76.951                                                    |                 1 | undefined                       |                          1 |                           1 | nan                      |                       0 | open/MLCommons/results/gh_windows-latest-reference-cpu-onnxruntime_v1.19.2-default_config/retinanet/offline    | onnxruntime v1.19.2 | Windows-2022Server-10.0.20348-SP0               | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
|  2 | MLCommons      | available      | open       | edge         | gh_ubuntu-latest_x86  | gh_ubuntu-latest_x86-reference-cpu-onnxruntime_v1.19.2-default_config  | resnet50            | resnet              | Offline    |    23.227    | acc: 76.000                                                    |                 1 | AMD EPYC 7763 64-Core Processor |                          1 |                           2 | nan                      |                       0 | open/MLCommons/results/gh_ubuntu-latest_x86-reference-cpu-onnxruntime_v1.19.2-default_config/resnet50/offline  | onnxruntime v1.19.2 | Ubuntu 22.04 (linux-6.5.0-1025-azure-glibc2.35) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
|  3 | MLCommons      | available      | open       | edge         | gh_ubuntu-latest_x86  | gh_ubuntu-latest_x86-reference-cpu-onnxruntime_v1.19.2-default_config  | retinanet           | retinanet           | Offline    |     0.433265 | mAP: 76.951                                                    |                 1 | AMD EPYC 7763 64-Core Processor |                          1 |                           2 | nan                      |                       0 | open/MLCommons/results/gh_ubuntu-latest_x86-reference-cpu-onnxruntime_v1.19.2-default_config/retinanet/offline | onnxruntime v1.19.2 | Ubuntu 22.04 (linux-6.5.0-1025-azure-glibc2.35) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
|  4 | MLCommons      | available      | open       | edge         | gh_action             | gh_action-reference-gpu-pytorch_v2.4.1-default_config                  | gptj-99             | gptj-99             | Offline    |    50.3446   | ROUGE1: 32.2581  ROUGE2: 6.6667  ROUGEL: 22.5806  GEN_LEN: 264 |                 1 | Intel(R) Xeon(R) w7-2495X       |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/gh_action-reference-gpu-pytorch_v2.4.1-default_config/gptj-99/offline                   | pytorch v2.4.1      | Ubuntu 22.04 (linux-6.2.0-39-generic-glibc2.35) | Automated by MLCommons CM v2.3.4. |            1 |        0 | v4.1      |          0 | False       | Tokens/s  | fp32                |
|  5 | MLCommons      | available      | open       | edge         | gh_windows            | gh_windows-reference-cpu-tf_v2.17.0-default_config                     | resnet50            | resnet              | Offline    |    21.8155   | acc: 76.000                                                    |                 1 | undefined                       |                          1 |                           1 | nan                      |                       0 | open/MLCommons/results/gh_windows-reference-cpu-tf_v2.17.0-default_config/resnet50/offline                     | tf v2.17.0          | Windows-2022Server-10.0.20348-SP0               | Automated by MLCommons CM v2.4.0. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
|  6 | MLCommons      | available      | open       | datacenter   | gh_ubuntu_x86         | gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config                       | resnet50            | resnet              | Server     | 75016.1      | acc: 76.078                                                    |                 1 | Intel(R) Xeon(R) w7-2495X       |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config/resnet50/server                        | TensorRT            | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.4. |            1 |        0 | v4.1      |          0 | False       | Queries/s | int8                |
|  7 | MLCommons      | available      | open       | datacenter   | gh_ubuntu_x86         | gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config                       | resnet50            | resnet              | Offline    | 80229.7      | acc: 76.078                                                    |                 1 | Intel(R) Xeon(R) w7-2495X       |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config/resnet50/offline                       | TensorRT            | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.4. |            1 |        0 | v4.1      |          0 | False       | Samples/s | int8                |
|  8 | MLCommons      | available      | open       | edge         | gh_ubuntu-latest_x86  | gh_ubuntu-latest_x86-reference-cpu-pytorch_v2.5.0-default_config       | retinanet           | retinanet           | Offline    |     0.412839 | mAP: 76.951                                                    |                 1 | AMD EPYC 7763 64-Core Processor |                          1 |                           2 | nan                      |                       0 | open/MLCommons/results/gh_ubuntu-latest_x86-reference-cpu-pytorch_v2.5.0-default_config/retinanet/offline      | pytorch v2.5.0      | Ubuntu 22.04 (linux-6.5.0-1025-azure-glibc2.35) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
|  9 | MLCommons      | available      | open       | edge         | gh_ubuntu-latest_x86  | gh_ubuntu-latest_x86-reference-cpu-deepsparse_v1.8.0-default_config    | bert-99             | bert-99             | Offline    |     6.37052  | F1: 80.0                                                       |                 1 | AMD EPYC 7763 64-Core Processor |                          1 |                           2 | nan                      |                       0 | open/MLCommons/results/gh_ubuntu-latest_x86-reference-cpu-deepsparse_v1.8.0-default_config/bert-99/offline     | deepsparse v1.8.0   | Ubuntu 22.04 (linux-6.5.0-1025-azure-glibc2.35) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
| 10 | MLCommons      | available      | open       | edge         | gh_action             | gh_action-reference-gpu-pytorch_v2.5.0-cu124                           | gptj-99             | gptj-99             | Offline    |    42.4133   | ROUGE1: 32.2581  ROUGE2: 6.6667  ROUGEL: 22.5806  GEN_LEN: 264 |                 1 | Intel(R) Xeon(R) w7-2495X       |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/gh_action-reference-gpu-pytorch_v2.5.0-cu124/gptj-99/offline                            | pytorch v2.5.0      | Ubuntu 22.04 (linux-6.2.0-39-generic-glibc2.35) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Tokens/s  | fp32                |
| 11 | MLCommons      | available      | open       | edge         | gh_ubuntu-latest_x86  | gh_ubuntu-latest_x86-reference-cpu-tf_v2.17.0-default_config           | resnet50            | resnet              | Offline    |    21.0188   | acc: 76.000                                                    |                 1 | AMD EPYC 7763 64-Core Processor |                          1 |                           2 | nan                      |                       0 | open/MLCommons/results/gh_ubuntu-latest_x86-reference-cpu-tf_v2.17.0-default_config/resnet50/offline           | tf v2.17.0          | Ubuntu 22.04 (linux-6.5.0-1025-azure-glibc2.35) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
| 12 | MLCommons      | available      | open       | edge         | gh_windows            | gh_windows-reference-cpu-onnxruntime_v1.19.2-default_config            | resnet50            | resnet              | Offline    |    17.8036   | acc: 76.000                                                    |                 1 | undefined                       |                          1 |                           1 | nan                      |                       0 | open/MLCommons/results/gh_windows-reference-cpu-onnxruntime_v1.19.2-default_config/resnet50/offline            | onnxruntime v1.19.2 | Windows-2022Server-10.0.20348-SP0               | Automated by MLCommons CM v2.4.0. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
| 13 | MLCommons      | available      | open       | edge         | gh_ubuntu-latest_x86  | gh_ubuntu-latest_x86-reference-cpu-pytorch_v2.4.1-default_config       | retinanet           | retinanet           | Offline    |     0.409818 | mAP: 76.951                                                    |                 1 | AMD EPYC 7763 64-Core Processor |                          1 |                           2 | nan                      |                       0 | open/MLCommons/results/gh_ubuntu-latest_x86-reference-cpu-pytorch_v2.4.1-default_config/retinanet/offline      | pytorch v2.4.1      | Ubuntu 22.04 (linux-6.5.0-1025-azure-glibc2.35) | Automated by MLCommons CM v3.2.3. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
| 14 | MLCommons      | available      | open       | edge         | gh_macos-latest_x86   | gh_macos-latest_x86-reference-cpu-onnxruntime_v1.19.2-default_config   | resnet50            | resnet              | Offline    |    20.9527   | acc: 76.000                                                    |                 1 | undefined                       |                          1 |                           3 | nan                      |                       0 | open/MLCommons/results/gh_macos-latest_x86-reference-cpu-onnxruntime_v1.19.2-default_config/resnet50/offline   | onnxruntime v1.19.2 | (darwin-23.6.0)                                 | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
| 15 | MLCommons      | available      | open       | edge         | gh_macos-latest_x86   | gh_macos-latest_x86-reference-cpu-onnxruntime_v1.19.2-default_config   | retinanet           | retinanet           | Offline    |     0.323181 | mAP: 76.951                                                    |                 1 | undefined                       |                          1 |                           3 | nan                      |                       0 | open/MLCommons/results/gh_macos-latest_x86-reference-cpu-onnxruntime_v1.19.2-default_config/retinanet/offline  | onnxruntime v1.19.2 | (darwin-23.6.0)                                 | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
| 16 | MLCommons      | available      | open       | edge         | gh_action             | gh_action-reference-gpu-pytorch-v2.5.0-cu124                           | gptj-99             | gptj-99             | Offline    |    47.0771   | ROUGE1: 32.2581  ROUGE2: 6.6667  ROUGEL: 22.5806  GEN_LEN: 264 |                 1 | Intel(R) Xeon(R) w7-2495X       |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/gh_action-reference-gpu-pytorch-v2.5.0-cu124/gptj-99/offline                            | pytorch v2.5.0      | Ubuntu 22.04 (linux-6.2.0-39-generic-glibc2.35) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Tokens/s  | fp32                |
| 17 | MLCommons      | available      | open       | edge         | gh_macos-latest_x86   | gh_macos-latest_x86-reference-cpu-deepsparse_v1.8.0-default_config     | bert-99             | bert-99             | Offline    |     4.26497  | F1: 80.0                                                       |                 1 | undefined                       |                          1 |                           3 | nan                      |                       0 | open/MLCommons/results/gh_macos-latest_x86-reference-cpu-deepsparse_v1.8.0-default_config/bert-99/offline      | deepsparse v1.8.0   | (darwin-23.6.0)                                 | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
| 18 | MLCommons      | available      | open       | edge         | gh_ubuntu-latest_x86  | gh_ubuntu-latest_x86-mlcommons_cpp-cpu-onnxruntime-default_config      | resnet50            | resnet              | Offline    |    23.2405   | acc: 76.000                                                    |                 1 | AMD EPYC 7763 64-Core Processor |                          1 |                           2 | nan                      |                       0 | open/MLCommons/results/gh_ubuntu-latest_x86-mlcommons_cpp-cpu-onnxruntime-default_config/resnet50/offline      | onnxruntime         | Ubuntu 22.04 (linux-6.5.0-1025-azure-glibc2.35) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
| 19 | MLCommons      | available      | open       | edge         | gh_ubuntu-latest_x86  | gh_ubuntu-latest_x86-mlcommons_cpp-cpu-onnxruntime-default_config      | retinanet           | retinanet           | Offline    |     0.430537 | mAP: 76.951                                                    |                 1 | AMD EPYC 7763 64-Core Processor |                          1 |                           2 | nan                      |                       0 | open/MLCommons/results/gh_ubuntu-latest_x86-mlcommons_cpp-cpu-onnxruntime-default_config/retinanet/offline     | onnxruntime         | Ubuntu 22.04 (linux-6.5.0-1025-azure-glibc2.35) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
| 20 | MLCommons      | available      | open       | edge         | gh_windows-latest     | gh_windows-latest-reference-cpu-pytorch_v2.5.0-default_config          | retinanet           | retinanet           | Offline    |     0.329647 | mAP: 76.951                                                    |                 1 | undefined                       |                          1 |                           1 | nan                      |                       0 | open/MLCommons/results/gh_windows-latest-reference-cpu-pytorch_v2.5.0-default_config/retinanet/offline         | pytorch v2.5.0      | Windows-2022Server-10.0.20348-SP0               | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
| 21 | MLCommons      | available      | open       | edge         | gh_action             | gh_action-reference-gpu-pytorch-v2.5.1-cu124                           | gptj-99             | gptj-99             | Offline    |    49.5356   | GEN_LEN: 264                                                   |                 1 | Intel(R) Xeon(R) w7-2495X       |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/gh_action-reference-gpu-pytorch-v2.5.1-cu124/gptj-99/offline                            | pytorch v2.5.1      | Ubuntu 22.04 (linux-6.2.0-39-generic-glibc2.35) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Tokens/s  | fp32                |
| 22 | MLCommons      | available      | open       | edge         | gh_windows-latest     | gh_windows-latest-reference-cpu-pytorch_v2.4.1-default_config          | retinanet           | retinanet           | Offline    |     0.327316 | mAP: 76.951                                                    |                 1 | undefined                       |                          1 |                           1 | nan                      |                       0 | open/MLCommons/results/gh_windows-latest-reference-cpu-pytorch_v2.4.1-default_config/retinanet/offline         | pytorch v2.4.1      | Windows-2022Server-10.0.20348-SP0               | Automated by MLCommons CM v3.2.3. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
| 23 | MLCommons      | available      | open       | edge         | gh_macos-latest_x86   | gh_macos-latest_x86-reference-cpu-pytorch_v2.5.0-default_config        | retinanet           | retinanet           | Offline    |     0.277839 | mAP: 76.951                                                    |                 1 | undefined                       |                          1 |                           3 | nan                      |                       0 | open/MLCommons/results/gh_macos-latest_x86-reference-cpu-pytorch_v2.5.0-default_config/retinanet/offline       | pytorch v2.5.0      | (darwin-23.6.0)                                 | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
| 24 | MLCommons      | available      | open       | edge         | gh_macos-latest_x86   | gh_macos-latest_x86-mlcommons_cpp-cpu-onnxruntime-default_config       | resnet50            | resnet              | Offline    |     9.37676  | acc: 76.000                                                    |                 1 | undefined                       |                          1 |                           3 | nan                      |                       0 | open/MLCommons/results/gh_macos-latest_x86-mlcommons_cpp-cpu-onnxruntime-default_config/resnet50/offline       | onnxruntime         | (darwin-23.6.0)                                 | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
| 25 | MLCommons      | available      | open       | datacenter   | 3b07702db56d          | 3b07702db56d-reference-gpu-pytorch_v2.4.1-scc24-base                   | stable-diffusion-xl | stable-diffusion-xl | Offline    |     0.374837 | CLIP_SCORE: 15.18544016778469  FID_SCORE: 235.69504308101006   |                 1 | Intel(R) Xeon(R) w7-2495X       |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/3b07702db56d-reference-gpu-pytorch_v2.4.1-scc24-base/stable-diffusion-xl/offline        | pytorch v2.4.1      | Ubuntu 22.04 (linux-6.2.0-39-generic-glibc2.35) | Automated by MLCommons CM v2.3.9. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
| 26 | MLCommons      | available      | open       | edge         | gh_windows-latest_x86 | gh_windows-latest_x86-reference-cpu-onnxruntime_v1.19.2-default_config | resnet50            | resnet              | Offline    |    17.596    | acc: 76.000                                                    |                 1 | undefined                       |                          1 |                           1 | nan                      |                       0 | open/MLCommons/results/gh_windows-latest_x86-reference-cpu-onnxruntime_v1.19.2-default_config/resnet50/offline | onnxruntime v1.19.2 | Windows-2022Server-10.0.20348-SP0               | Automated by MLCommons CM v3.2.4. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
| 27 | MLCommons      | available      | open       | edge         | gh_windows-latest_x86 | gh_windows-latest_x86-reference-cpu-tf_v2.17.0-default_config          | resnet50            | resnet              | Offline    |    21.7501   | acc: 76.000                                                    |                 1 | undefined                       |                          1 |                           1 | nan                      |                       0 | open/MLCommons/results/gh_windows-latest_x86-reference-cpu-tf_v2.17.0-default_config/resnet50/offline          | tf v2.17.0          | Windows-2022Server-10.0.20348-SP0               | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
| 28 | MLCommons      | available      | open       | edge         | gh_action             | gh_action-reference-gpu-pytorch_v2.4.1-cu124                           | stable-diffusion-xl | stable-diffusion-xl | Offline    |     0.346565 | CLIP_SCORE: 15.18544016778469  FID_SCORE: 235.69504308101006   |                 1 | Intel(R) Xeon(R) w7-2495X       |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/gh_action-reference-gpu-pytorch_v2.4.1-cu124/stable-diffusion-xl/offline                | pytorch v2.4.1      | Ubuntu 22.04 (linux-6.2.0-39-generic-glibc2.35) | Automated by MLCommons CM v2.3.9. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
| 29 | MLCommons      | available      | open       | edge         | gh_action             | gh_action-reference-gpu-pytorch_v2.4.1-cu124                           | gptj-99             | gptj-99             | Offline    |    46.0817   | ROUGE1: 32.2581  ROUGE2: 6.6667  ROUGEL: 22.5806  GEN_LEN: 264 |                 1 | Intel(R) Xeon(R) w7-2495X       |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/gh_action-reference-gpu-pytorch_v2.4.1-cu124/gptj-99/offline                            | pytorch v2.4.1      | Ubuntu 22.04 (linux-6.2.0-39-generic-glibc2.35) | Automated by MLCommons CM v2.3.9. |            1 |        0 | v4.1      |          0 | False       | Tokens/s  | fp32                |
| 30 | MLCommons      | available      | closed     | datacenter   | gh_ubuntu_x86         | gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config                       | resnet50            | resnet              | Server     | 73015.3      | acc: 76.078                                                    |                 1 | Intel(R) Xeon(R) w7-2495X       |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config/resnet50/server                      | TensorRT            | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.5. |            1 |        0 | v4.1      |          0 | False       | Queries/s | int8                |
| 31 | MLCommons      | available      | closed     | datacenter   | gh_ubuntu_x86         | gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config                       | resnet50            | resnet              | Offline    | 80458.4      | acc: 76.078                                                    |                 1 | Intel(R) Xeon(R) w7-2495X       |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config/resnet50/offline                     | TensorRT            | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.5. |            1 |        0 | v4.1      |          0 | False       | Samples/s | int8                |