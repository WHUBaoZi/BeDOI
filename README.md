# Setup
## Data
The published dataset BeDOI are currently available at Baidu Cloud, you can download it via (waiting update...) and the extraction code: ((waiting update...).

## Dataset Format
![DirectoryStructure](https://github.com/WHUHaoZhan/BeDOI/blob/main/DirectoryStructure.png)
## File Description
  | FilePath | Description |
  |    :----:   | --- |
  | ImageData/CombinedData | -Images from all datasets combined. |
  | ImageData/[names] | -Images from separated dataset, <br>-[names] represents the name of the separated dataset. |
  | ImageData/CombinedData/num1_num2_name_xxxx.jpg | -'num1' represents the index of the image in the CombinedData, <br>-'name' represents the name of the separated dataset where the image is located, <br>-'num2' represents the index of the image in the separated dataset. |
  | ImageData/[names]/num1_name_xxxx.jpg | -'num1' represents the index of the image in the separated dataset, <br>-[names] & 'name' represents the name of this dataset. |
