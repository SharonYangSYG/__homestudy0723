# __homestudy0723
##建立_postgres
###上課準備事項

# Github
##帳號SharonYangSYG  

##密碼Sharon1217!@#$%^&  


#建立容器
##Docker desktop download  

#打開termianl輸入docker run --name my-postgres -e POSTGRES_PASSWORD=raspberry -p 5432:5432 -d postgres


**參數說明:**

--name my-postgres: 容器名稱  

-e POSTGRES_PASSWORD=yourpassword: 設定 PostgreSQL 使用者 postgres 的密碼  

-p 5432:5432: 將容器內的 5432 端口映射到本機 5432 端口  

-d postgres: 背景執行並使用 postgres 映像檔  

預設使用者帳號: postgres  


##Docker安裝python_conda_git開發環境
###步驟2 建立Python容器
docker run -it --name python-postgres continuumio/miniconda3
##方法二(虛擬環境)
docker run --platform linux/amd64 -it --name python-postgres -d roberthsu2003/conda_uv_npx
檢查
nv --version
**git設定**
git config --global user.name "SharonYangSYG"  

git config --global user.email "tingtingdondon@gmail.com"  

git config --global pull.rebase false  


##安裝visual studio code
**在vscode:**
安裝lang中文繁體  

安裝Dev Container  

安裝container tools  

在左下角齒輪/設定/Auto SAVE/選after delay,關閉即儲存  

左上角檔案總管:CLONE repositories/選GITHUB,點選Github資料夾,按...選擇home為儲存位址,測試連線.左下角有到容器...miniconda3 python-postgres再按finish

**DBeaver 官網下載 - 通用資料庫管理工具**
選擇新資料庫, 選postgres大象, 密碼填raspberry  

更名:local_postgres  

置表格群,匯入csv  


**文字**

<img width="911" height="924" alt="image" src="https://github.com/user-attachments/assets/4ad8261d-36ed-456e-b491-aea6fb243189" />

<img width="1913" height="773" alt="image" src="https://github.com/user-attachments/assets/1d1356e3-c270-40d1-8df5-34d860236825" />

python下執行的檔.
<img width="583" height="425" alt="image" src="https://github.com/user-attachments/assets/127428df-d03b-4954-a060-11a6ff8cc464" />
進入Python執行
![Uploading image.png…]()

