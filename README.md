Please download [summary.xlsx](summary.xlsx) to view the most recent results. 
 ```
[2024-10-04 16:34:42,724 submission_checker1.py:2936 INFO] Results=5, NoResults=0, Power Results=0
[2024-10-04 16:34:42,724 submission_checker1.py:2943 INFO] ---
[2024-10-04 16:34:42,724 submission_checker1.py:2944 INFO] Closed Results=0, Closed Power Results=0

[2024-10-04 16:34:42,724 submission_checker1.py:2949 INFO] Open Results=5, Open Power Results=0

[2024-10-04 16:34:42,725 submission_checker1.py:2954 INFO] Network Results=0, Network Power Results=0

[2024-10-04 16:34:42,725 submission_checker1.py:2959 INFO] ---
[2024-10-04 16:34:42,725 submission_checker1.py:2961 INFO] Systems=5, Power Systems=0
[2024-10-04 16:34:42,725 submission_checker1.py:2962 INFO] Closed Systems=0, Closed Power Systems=0
[2024-10-04 16:34:42,725 submission_checker1.py:2967 INFO] Open Systems=5, Open Power Systems=0
[2024-10-04 16:34:42,725 submission_checker1.py:2972 INFO] Network Systems=0, Network Power Systems=0
[2024-10-04 16:34:42,725 submission_checker1.py:2977 INFO] ---
[2024-10-04 16:34:42,725 submission_checker1.py:2982 INFO] SUMMARY: submission looks OK
INFO:root:       ! call "postprocess" from /home/runner/CM/repos/mlcommons@cm4mlops/script/run-mlperf-inference-submission-checker/customize.py

```

|    | Organization   | Availability   | Division   | SystemType   | SystemName           | Platform                                                              | Model               | MlperfModel         | Scenario   |    Result | Accuracy                                                     |   number_of_nodes | host_processor_model_name       |   host_processors_per_node |   host_processor_core_count | accelerator_model_name   |   accelerators_per_node | Location                                                                                                      | framework           | operating_system                                | notes                             |   compliance |   errors | version   |   inferred | has_power   | Units     | weight_data_types   |
|---:|:---------------|:---------------|:-----------|:-------------|:---------------------|:----------------------------------------------------------------------|:--------------------|:--------------------|:-----------|----------:|:-------------------------------------------------------------|------------------:|:--------------------------------|---------------------------:|----------------------------:|:-------------------------|------------------------:|:--------------------------------------------------------------------------------------------------------------|:--------------------|:------------------------------------------------|:----------------------------------|-------------:|---------:|:----------|-----------:|:------------|:----------|:--------------------|
|  0 | MLCommons      | available      | open       | edge         | gh_ubuntu-latest_x86 | gh_ubuntu-latest_x86-reference-cpu-tf_v2.17.0-default_config          | resnet50            | resnet              | Offline    | 20.8882   | acc: 76.000                                                  |                 1 | AMD EPYC 7763 64-Core Processor |                          1 |                           2 | nan                      |                       0 | open/MLCommons/results/gh_ubuntu-latest_x86-reference-cpu-tf_v2.17.0-default_config/resnet50/offline          | tf v2.17.0          | Ubuntu 22.04 (linux-6.8.0-1014-azure-glibc2.35) | Automated by MLCommons CM v2.3.9. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
|  1 | MLCommons      | available      | open       | edge         | gh_ubuntu-latest_x86 | gh_ubuntu-latest_x86-reference-cpu-onnxruntime_v1.19.2-default_config | resnet50            | resnet              | Offline    | 22.9955   | acc: 76.000                                                  |                 1 | AMD EPYC 7763 64-Core Processor |                          1 |                           2 | nan                      |                       0 | open/MLCommons/results/gh_ubuntu-latest_x86-reference-cpu-onnxruntime_v1.19.2-default_config/resnet50/offline | onnxruntime v1.19.2 | Ubuntu 22.04 (linux-6.8.0-1014-azure-glibc2.35) | Automated by MLCommons CM v2.3.9. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
|  2 | MLCommons      | available      | open       | edge         | gh_ubuntu-latest_x86 | gh_ubuntu-latest_x86-mlcommons_cpp-cpu-onnxruntime-default_config     | resnet50            | resnet              | Offline    | 23.0395   | acc: 76.000                                                  |                 1 | AMD EPYC 7763 64-Core Processor |                          1 |                           2 | nan                      |                       0 | open/MLCommons/results/gh_ubuntu-latest_x86-mlcommons_cpp-cpu-onnxruntime-default_config/resnet50/offline     | onnxruntime         | Ubuntu 22.04 (linux-6.8.0-1014-azure-glibc2.35) | Automated by MLCommons CM v2.3.9. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
|  3 | MLCommons      | available      | open       | datacenter   | 3b07702db56d         | 3b07702db56d-reference-gpu-pytorch_v2.4.1-scc24-base                  | stable-diffusion-xl | stable-diffusion-xl | Offline    |  0.374837 | CLIP_SCORE: 15.18544016778469  FID_SCORE: 235.69504308101006 |                 1 | Intel(R) Xeon(R) w7-2495X       |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/3b07702db56d-reference-gpu-pytorch_v2.4.1-scc24-base/stable-diffusion-xl/offline       | pytorch v2.4.1      | Ubuntu 22.04 (linux-6.2.0-39-generic-glibc2.35) | Automated by MLCommons CM v2.3.9. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |
|  4 | MLCommons      | available      | open       | edge         | gh_macos-latest_x86  | gh_macos-latest_x86-mlcommons_cpp-cpu-onnxruntime-default_config      | resnet50            | resnet              | Offline    |  9.20093  | acc: 76.000                                                  |                 1 | undefined                       |                          1 |                           3 | nan                      |                       0 | open/MLCommons/results/gh_macos-latest_x86-mlcommons_cpp-cpu-onnxruntime-default_config/resnet50/offline      | onnxruntime         | (darwin-23.6.0)                                 | Automated by MLCommons CM v2.3.9. |            1 |        0 | v4.1      |          0 | False       | Samples/s | fp32                |