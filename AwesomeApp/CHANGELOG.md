### 2023-12-02 20:30:00

> 2、pod init

pod init 报错如下：

```
 pod init
/Library/Ruby/Gems/2.6.0/gems/cocoapods-1.11.3/lib/cocoapods/user_interface/error_report.rb:34:in `force_encoding': can't modify frozen String (FrozenError)
    from /Library/Ruby/Gems/2.6.0/gems/cocoapods-1.11.3/lib/cocoapods/user_interface/error_report.rb:34:in `report'
    from /Library/Ruby/Gems/2.6.0/gems/cocoapods-1.11.3/lib/cocoapods/command.rb:66:in `report_error'
    from /Library/Ruby/Gems/2.6.0/gems/claide-1.0.3/lib/claide/command.rb:396:in `handle_exception'
    from /Library/Ruby/Gems/2.6.0/gems/claide-1.0.3/lib/claide/command.rb:337:in `rescue in run'
    from /Library/Ruby/Gems/2.6.0/gems/claide-1.0.3/lib/claide/command.rb:324:in `run'
    from /Library/Ruby/Gems/2.6.0/gems/cocoapods-1.11.3/lib/cocoapods/command.rb:52:in `run'
    from /Library/Ruby/Gems/2.6.0/gems/cocoapods-1.11.3/bin/pod:55:in `<top (required)>'
    from /usr/local/bin/pod:23:in `load'
    from /usr/local/bin/pod:23:in `<main>'
/Library/Ruby/Gems/2.6.0/gems/xcodeproj-1.21.0/lib/xcodeproj/project.rb:228:in `initialize_from_file': [Xcodeproj] Unknown object version (56). (RuntimeError)
    from /Library/Ruby/Gems/2.6.0/gems/xcodeproj-1.21.0/lib/xcodeproj/project.rb:113:in `open'
    from /Library/Ruby/Gems/2.6.0/gems/cocoapods-1.11.3/lib/cocoapods/command/init.rb:41:in `validate!'
    from /Library/Ruby/Gems/2.6.0/gems/claide-1.0.3/lib/claide/command.rb:333:in `run'
    from /Library/Ruby/Gems/2.6.0/gems/cocoapods-1.11.3/lib/cocoapods/command.rb:52:in `run'
    from /Library/Ruby/Gems/2.6.0/gems/cocoapods-1.11.3/bin/pod:55:in `<top (required)>'
    from /usr/local/bin/pod:23:in `load'
    from /usr/local/bin/pod:23:in `<main>'
```

```
解决方案：
CHANGELOGASSETS/2023-12-02/pod init 报错.pdf
```

> 1、项目初始化

Xcode14.2
