
## ER图
![](ER图.png)




## SQL脚本

use sbs; 

select * from maintain,maintain_consume,record where eid=1;


select * from equipemnt where to_days(now())-to_days(eremaintain)>=cycle-1;


## SOL脚本执行截图
### 查询
![](查询.png)




### 预警
![](预警.png)
