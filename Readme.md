# 个人常用 ansible 脚本

## Q&A

### 如果一个 task 执行错误，如何使它继续执行下去

添加参数 `ignore_errors: true` 忽略错误

### 如何根据一个 task 的执行结果来决定是否执行其它 task

使用 `register` 来监听当前任务的执行情况，使用 `when` 设定条件。参考 []()


## ansible 注意点

+ 在使用相关 ansible 模块前请先确认是否满足 requirements
