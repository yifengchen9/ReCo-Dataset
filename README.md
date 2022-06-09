## ReCo-Dataset
This is the offical repository for **Re**sidential **Co**mmunity Layout Planning (**ReCo**) Dataset

Our dataset is under the [CC BY-NC-SA license](https://creativecommons.org/licenses/by-nc-sa/4.0/).

### Generating 2D image data from ReCo Dataset
1. Please download the dataset from https://www.kaggle.com/fdudsde/reco-dataset and put the JSON file under the main directory.
2. Please make sure that the JSON file is named as ReCo_json.json
3. You can plot one of example of the data by using "_id" as index through plot_2d_from_json.py.
4. make_image_data.py can help you to build an image dataset from ReCo_json.json file.

### Experiments
We redeveloped the code at https://github.com/eriklindernoren/PyTorch-GAN and used DCGAN as the backbone networks.

We used an Nvidia Tesla V100 to train the model for 2k epochs with a batch size of 128 per sub-experiment.

The training details of our demonstrated experiments are shown in `experiments` codes. \
We used the same hyperparameters in our four sub-experiments.

## Dataset DOI
10.34740/kaggle/dsv/3689702

## Dataset Citation
 @misc{xi chen_yun xiong_siqi wang_haofen wang_tao sheng_yao zhang_yu ye_2022,  \
 title={ReCo:Residential Community Layout Planning Dataset}, \
 url={https://www.kaggle.com/dsv/3689702}, \
 DOI={10.34740/KAGGLE/DSV/3689702}, \
 publisher={Kaggle}, \
 author={Xi Chen and Yun Xiong and Siqi Wang and Haofen Wang and Tao Sheng and Yao Zhang and Yu Ye}, \
 year={2022} \
 }

## Acknowledgments
This work is funded in part by the National Natural Science Foundation of China Projects No. U1936213, No.62176185. This work is also partially supported by the Shanghai Science and Technology Development Fund No. 2021SHZDZX0100, 19DZ1200802, the Fundamental Research Funds for the Central Universities.
