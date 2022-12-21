# Helm - ConfigMaps 

This template will show you how you can create configmaps direct from **files** & also from **Values.yaml**


## Prerequisites

1. Helm v3 installed
2. Basic knowledge of go-templates


## Usage

### 1. Just place files in `file/tmp/` directory 

![image](https://user-images.githubusercontent.com/86958474/208981968-2142354a-83ee-4e95-95ce-37c107ef6ade.png)

**Optionally**

Place file contents in `values.yaml` file

![image](https://user-images.githubusercontent.com/86958474/208982021-5d6079d9-9651-4922-afbb-3dd1a69b7f3f.png)

### 2. Check Helm template

```
helm template demo file
```
![image](https://user-images.githubusercontent.com/86958474/208982127-7b8df3a8-48ae-466d-a5d8-0ef7f6aafd20.png)
