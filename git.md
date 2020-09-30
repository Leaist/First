# Git 
1、是一个开源分布式版本控制系统 SVN集中式的版本控制系统
2、Git的版本库可以在每一个Git用户上,SVN的版本是在中央服务器


        git操作具体步骤
            1、cd路径 进入当前目录
            2、配置git基本操作
                【注】没有消息就是好消息

            3、git init 在本地进行初始化(建立暂存区).git文件存储当前项目所有版本信息

            4、工作群 =>暂存区
                git add 文件名
                git add * 提交所有文件
                git commit -m *提交所有文件

            5、查看当前工作区的状态
                git status

            6、从暂存区恢复文件到工作区
                git checkout 文件名

            7、查看工作区和暂存区版本的区别
                git diff

            8、clear 清屏操作

            9、查看历史提交版本
            git log
            git reflog

            10、git reset --hard HEAD^/commitID恢复上一次版本

            11、git restore 文件路径

            12、rm删除

            刘儿子冲冲冲冲冲！
