# PR 步骤

为确保项目格式与内容的一致性，请各位能参考以下步骤进行经验贴的分享和 PR  :wink:

### Step 1

首先在本地 clone 此项目，然后创建相应的分支

> git checkout -b [YourName]  
> **将 [YourName] 替换成具体内容**，如 git checkout -b CaiZeSen

随后在 夏令营 或 预推免 对应的目录中撰写经验贴。

**如果您已经在其他平台发布相关经验贴，可以直接在 README 添加相关 URL，以减少您的工作量**

### Step 2

如果在本地撰写经验贴，那么请先创建一个文件夹，文件夹名称可任意(如：czs)，但请勿低俗或过度整活 :cold_sweat: 

经验贴模板可以参考[模板](./Template.md)，也可以自行设计

撰写经验贴过程中所使用到的图片或其他文件，直接放在对应的文件夹中即可

### Step 3

完成经验贴的撰写后，通过以下命令来提交，以便后续审核

> git add .
>  
> git commit -m "message" 
> 
> git push origin [YourName]

### Step 4

随后会审阅提交的内容，确认无误后将合并到 main 分支，并删除创建的 [YourName] 分支，下次如果要修改的话，请先切换到 main 分支并 pull 更新分支里的内容，然后修改后根据以上流程重新创建分支并提交