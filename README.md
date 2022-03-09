# 项目描述
自己在学习python，此项目为练习Python的基础知识，主要包括:文件读写，列表，元组，字典的操作，类，函数等

> 项目在命令行中运行

模块：

```commandline
User{
    username,
    nickname,
    password,
    email,
    birthday,
    create_time,
    role,
    active,
    reset_password(),
    reset_nickname(),
    reset_email(),
    reset_birthday(),
    borrow_book(),
    return_book(),
}
```
    
```commandline
Student:继承自User
    last_borrow_time,
    borrow_history[],
    birthday_gift(),
```
    

```commandline
Admin:继承自User
    add_book(),
    delete_book(),
```

ErrorUtils：自定义异常类，包括文件读取失败异常，文件名错误异常，用户名异常等
