# Setup
## Data
The published dataset BeDOI are currently available at Baidu Cloud, you can download it via (waiting update...) and the extraction code: ((waiting update...).

## Dataset Format
![DirectoryStructure](https://github.com/WHUHaoZhan/BeDOI/blob/main/DirectoryStructure.png)
## File Description
  | FilePath | Description |
  |    :----:   | --- |
  | ImageData/CombinedData | -Images from all datasets combined. |
  | ImageData/[name] | -Images from separated dataset, <br>-[name] represents the name of the separated dataset. |
  |`ImageData/CombinedData/num1_num2_[name]_xxxx.jpg` | -'num1' represents the index of the image in the CombinedData, <br>-[name] represents the name of the separated dataset where the image is located, <br>-'num2' represents the index of the image in the separated dataset. |
  | `ImageData/[name]/num1_[name]_xxxx.jpg` | -'num1' represents the index of the image in the separated dataset, <br>-[name] represents the name of this dataset. |
  | `StandardMatchingResult/[name]/[name]_MatchResultSorted.txt` | -Standard matching result of the separated dataset, <br>-[name] is the name of this dataset. |
  | `StandardMatchingResult/[name]/[name]_MatchResultSortedPicture` | -Image overlap diagram of the separated dataset, <br>-[name] is the name of this dataset. |
