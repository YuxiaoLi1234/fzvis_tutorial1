### Tutorial
## Prerequisites

1.  docker
2.  docker-compose

### Project setup
```
git clone https://github.com/YuxiaoLi1234/fzvis_tutorial1.git
cd fzvis_tutorial1
run `docker-compose up`
```

## Set up 

```
input http://localhost:8080/ in your web browser.
```

```
The dashboard should look like this figure.
```
<img width="1489" alt="Screenshot 2024-02-10 at 4 14 16 PM" src="https://github.com/YuxiaoLi1234/fzvis_tutorial1/assets/143280350/ab82e01c-e783-4b06-8197-49c7e03f9170">



### Workflow


## run compressor:
  enter the configuration and also upload your input data (only .npy is supported now, you can use the example data: inputdata1000.npy/inputdata500.npy). After you have configured all the options, press submit.
 <img width="409" alt="image" src="https://github.com/YuxiaoLi1234/fzvis_tutorial1/assets/143280350/378d80ab-f7af-4c61-8963-f1da0f2d0e5c">

  ```
  compresoor_id: Please enter the type of compressor that is supported by libpressio.
  ```

  ```
  fileloader: Upload you input data, only '.npy' is supported now, you can use the example data: inputdata1000.npy/inputdata500.npy
  ```
  ```
  early config: If you are going to include a path in your configuration, please make sure you entered the absolute path.
  ```
  ```
  compressor_config: Configuration of the compressor.
  ```
  
  ```
  compressor_name: The name for this configuration of compressor.
  ```
  - After running all the compressors you need for visualization, click draw on module D.
  - The reuslt in module D should be like the figure below:
  
<img width="1038" alt="image" src="https://github.com/YuxiaoLi1234/fzvis/assets/143280350/4e6f1403-e7be-4e2f-97d8-ffbc21801ae3">

- You can add a new compressor by enter the configuration in module A, remember to click the button Draw in module D to get the new result.

### Interaction usage:
## Compare Matrics among Compressors.
1. After running all compressors, you need to click on the name of the compressors you want to compare:
<img width="850" alt="image" src="https://github.com/YuxiaoLi1234/fzvis/assets/143280350/be90256f-ad14-4e28-a7d6-9383e85b5734">

2. Click on the compressor_compare button, the result shoule be like the figure below:
<img width="1028" alt="image" src="https://github.com/YuxiaoLi1234/fzvis/assets/143280350/9b62cdaa-fe26-43c6-ac68-f71e1f615407">

(click on the all_compressor button to return to the visualization of barcharts of all of the compressors)
3. Then you could interactively select the parameter and compressor you want in module B.
<img width="591" alt="image" src="https://github.com/YuxiaoLi1234/fzvis_tutorial1/assets/143280350/9ab108ac-6f5b-450b-bf9b-18ce5237fc72">

## Input Data Vis:
- After running the compressors, you can visualize the slice of your input data in module C.
- Make sure that you input your slice_id, format of your inputdata.
- Click on the DataVis button to visualize your data.
- There is a defaultcolormap selector on the top left. You can also add control points by clicking on the colormap for the colormap (under the mode of "add_points")/ drag the existing control points (under the mode of "use current control points").

<img width="341" alt="image" src="https://github.com/YuxiaoLi1234/fzvis_tutorial1/assets/143280350/9f36e096-cf8b-43be-b1eb-8c8932251ba0">









