# ET-RPG-DEMO
仅供学习交流.  
目标是在ET框架的基础上,做一个支持多人对战的ARPG的DEMO.   
借以学习服务器端开发.和了解服务器/客户端交互细节.  
## 目前编译须知  
暂时没处理二进制文件的打包问题.寻路的graph.bytes (Assets文件下)编译后需要加入到ET_Data中才能运行.   

## 项目特点   
1.同步方式为状态同步(似乎有点像混合同步? 反正刚接触服务器开发,不太了解这块的区别)   
2.双端Bullet物理(3D物理)  
3.ARPG,支持多人对战

# 目前目标和进度的说明   
## 已完成
1.导入一套动作资源,创建基本Animator     
2.创建一套UI框架,规范UI这边的工作流    
3.实现简单的移动同步(目前是一秒同步5次)    
4.初步实现了服务器/客户端 逻辑帧框架,以及完善了移动同步    
5.移动同步更改为45度俯视角   

## 进行中   
6.加入技能系统. (进行中)   

## 进度展示(视频连接,占位)




