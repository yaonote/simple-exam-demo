# simple-exam-demo
根据json数据渲染试题并且保存答案的demo


#用node开了一个临时服务器，主要的逻辑在  /views/index.html文件里面

#json 也是瞎写的
#用template 模板渲染出试卷结构，然后用on 来绑定渲染出的元素的事件，然后就是把题号当成是键，答案为键值，存储到对象中，
这样可以达到试题答案的实时更新的效果。


###可以用 npm run start 来运行，监听3000端口

######样式没有写，主要就是整理一下逻辑
