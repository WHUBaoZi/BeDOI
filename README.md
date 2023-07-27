# Setup
## Data
The published dataset BeDOI are currently available at Baidu Cloud, you can download it via https://pan.baidu.com/s/1CKUTUKACjpb_OsAOkTM35A and the extraction code: 2eov.

## Dataset Format
![DirectoryStructure](https://github.com/WHUHaoZhan/BeDOI/blob/main/DirectoryStructure.png)
## File Description
  | FilePath | Description |
  |    :----:   | --- |
  | `GSW2023_DATA/AllData` | -Images from all datasets combined. |
  | `GSW2023_DATA/[name]` | -Images from separated dataset, <br>-[name] represents the name of the separated dataset. |
  |`GSW2023_DATA/AllData/num1_num2_[name]_xxxx.jpg` | -'num1' represents the index of the image in the CombinedData, <br>-[name] represents the name of the separated dataset where the image is located, <br>-'num2' represents the index of the image in the separated dataset. |
  | `GSW2023_DATA/[name]/num1_[name]_xxxx.jpg` | -'num1' represents the index of the image in the separated dataset, <br>-[name] represents the name of this dataset. |
  | `GSW2023_DATA/MatchResult/[name]/[name]_MatchResult.txt` | -Standard matching result of the separated dataset, <br>-[name] is the name of this dataset. |
  | `GSW2023_DATA/MatchResult/[name]/[name]_MatchResultSorted.txt` | -Sorted standard matching result of the separated dataset, <br>-[name] is the name of this dataset. |
  | `GSW2023_DATA/MatchResult/[name]/[name]_MatchResultSortedPicture.png` | -Image overlap diagram of the separated dataset, <br>-[name] is the name of this dataset. |
