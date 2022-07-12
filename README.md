# ProcessRun
goland multi script run frame

事件案例
在main.go 里面引用


```
newProcess := process.ProcessRun{
    ServiceList:[]dataService.DataService{
     //脚本
    },
    Consumer:[]consumer.consumer{
    //任务
    },
  }
newProcess.Run()
```