# redis_cleaner
clean redis keys when mysql binlog updated based on canal.
# 主要功能：
redis缓存从mysql中查询出来的数据，当数据表更新时通过canal获取修改的事件，然后将redis缓存中相关的key删除，实现redis缓存更新。
# Build
·前提：安装maven3
·cmd命令：
cd redis_cleaner
package.bat
