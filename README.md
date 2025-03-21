# An Automated Cell Line Authentication Method for AstraZeneca Global Cell Bank

This is the official public Pytorch implementation for our paper (https://www.nature.com/articles/s41598-022-12099-3).


For any issue and question, please email [lt228@leicester.ac.uk]


## Dependencies

- Python (>=3.6)
- Pytorch (>=1.9.0)
- opencv-python
- matplotlib
- scikit-learn (>=0.24.2)
- numpy
- scikit-image
- torchvision (>=0.10.0)

## Dataset

Part of example images are put in the './data'.

<img src="./figures/Fig. 4.jpeg" alt="centered image" width="893" height="860">

## Training CLCNet

```bash
cd ./networks/classification
python cell_classification.py --bs 20 --arch Xception 
```

## Testing CLCNet
Use JupyterLab to open 'model_evaluation.ipynb' and run code blocks.

## Training/Testing CLRNet or with tranfer learning 
Use JupyterLab to open 'model_evaluation.ipynb' and run all code blocks.

## License
This code is made available under the GPLv3 License and is available for non-commercial academic purposes.

## Acknowledgement
The authors gratefully acknowledge financial support from University of Leicester, AstraZeneca UK, China Scholarship Council.

------
If you find that is useful in your research, please consider citing:
```
@article{tong2022automated,
  title={An automated cell line authentication method for AstraZeneca global cell bank using deep neural networks on brightfield images},
  author={Tong, Lei and Corrigan, Adam and Kumar, Navin Rathna and Hallbrook, Kerry and Orme, Jonathan and Wang, Yinhai and Zhou, Huiyu},
  journal={Scientific Reports},
  volume={12},
  number={1},
  pages={1--11},
  year={2022},
  publisher={Nature Publishing Group}
}
```
