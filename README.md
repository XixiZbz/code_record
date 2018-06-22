### sqlalchemy
##### 批量更新
	. session.query(News).filter(News.tid==0).update({News.tid:100})
	. session.commit()

### git 
#### 分支合并
    #从远程的origin仓库的master分支下载到本地,并新建一个***分支
    . git fetch origin master:*** 
    #查看与本地分支的不同
    . git diff ***
    #合并
    . git merge *** 