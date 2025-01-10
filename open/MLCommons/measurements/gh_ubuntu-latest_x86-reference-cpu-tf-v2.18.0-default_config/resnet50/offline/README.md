This experiment is generated using the [MLCommons Collective Mind automation framework (CM)](https://github.com/mlcommons/cm4mlops).

*Check [CM MLPerf docs](https://docs.mlcommons.org/inference) for more details.*

## Host platform

* OS version: Linux-6.8.0-48-generic-x86_64-with-glibc2.39
* CPU version: x86_64
* Python version: 3.12.3 (main, Nov  6 2024, 18:32:19) [GCC 13.2.0]
* MLCommons CM version: 3.4.1

## CM Run Command

See [CM installation guide](https://docs.mlcommons.org/inference/install/).

```bash
pip install -U cmind

cm rm cache -f

cm pull repo gateoverflow@cm4mlops --checkout=d63d6b560994f51a9a794073effaee741785af95

cm run script \
	--tags=run-mlperf,inference,_submission,_short \
	--submitter=MLCommons \
	--hw_name=gh_ubuntu-latest_x86 \
	--model=resnet50 \
	--implementation=python \
	--backend=tf \
	--device=cpu \
	--scenario=Offline \
	--test_query_count=500 \
	--target_qps=1 \
	-v \
	--quiet \
	--clean
```
*Note that if you want to use the [latest automation recipes](https://docs.mlcommons.org/inference) for MLPerf (CM scripts),
 you should simply reload gateoverflow@cm4mlops without checkout and clean CM cache as follows:*

```bash
cm rm repo gateoverflow@cm4mlops
cm pull repo gateoverflow@cm4mlops
cm rm cache -f

```

## Results

Platform: gh_ubuntu-latest_x86-reference-cpu-tf-v2.18.0-default_config

Model Precision: fp32

### Accuracy Results 
`acc`: `76.0`, Required accuracy for closed division `>= 75.6954`

### Performance Results 
`Samples per second`: `209.113`
