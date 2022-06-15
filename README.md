# Multi-modal Recipe Representation Learning with Graph Neural Networks
This is the official repo for the paper "Multi-modal Recipe Representation Learning with Graph Neural Networks", accepted at IJCAI 2022.

## Data
Please first [download the data](https://drive.google.com/drive/folders/1n-ednzpdi_xgPDwXW-xmcChBotOqpTbb?usp=sharing), then put them under the folder 'data/'.

For the mappings between the nodes in Large-RG (the recipe graph) and the recipe text (recipes.json), please check the following code block:
```
recipeID2nodeID_dict, nodeID2recipeID_dict = torch.load('../data/recipeID2nodeID_and_nodeID2recipeID.pt')
ingreID2nodeID_dict, nodeID2ingreID_dict = torch.load('../data/ingre2nodeID_and_nodeID2ingre.pt')
```

## Code
All codes have been put into a jupyter notebook for easy reading and executing. We further log the results in the notebook for demonstration purposes. 


## Citing Recipe2vec
If you find Recipe2vec useful, please cite our paper.
```
@inproceedings{Recipe2Vec,
  author = {Tian, Yijun and Zhang, Chuxu and Guo, Zhichun and Ma, Yihong and Metoyer, Ronald and Chawla, Nitesh V.},
  title = {Recipe2Vec: Multi-modal Recipe Representation Learning with Graph Neural Networks},
  booktitle = {IJCAI},
  year = {2022}
}
```
