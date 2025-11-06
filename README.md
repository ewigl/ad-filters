# AD Filters
> My ad filters.

```
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! 视频网站

! Bilibili
! 首页
! 桌面端下载提示
bilibili.com##.desktop-download-tip
! 下载客户端按钮
bilibili.com##.download-client-trigger.download-entry
! 开启通知提示
bilibili.com##.request-permission
! 海报
bilibili.com##.recommended-swipe
! 动态
! 右侧 新闻、话题
t.bilibili.com##.right
! 左侧 个人信息
! t.bilibili.com##.left
! 顶部发布框...
! t.bilibili.com##.bili-dyn-publishing
t.bilibili.com##main > section:has(> .bili-dyn-publishing)
! t.bilibili.com##.bili-dyn-home--member main > section:first-of-type

! YouTube
! 片尾视频卡片、卡片隐藏按钮
youtube.com##.ytp-ce-element
youtube.com##.ytp-ce-hide-button-container
! 会员专属视频 - 频道视频列表
youtube.com##ytd-rich-item-renderer:has(.badge-style-type-members-only)
! 会员专属视频 - 频道首页推荐
youtube.com##ytd-grid-video-renderer:has(.badge-style-type-members-only)
! 会员专属视频 - 播放列表内
! youtube.com##ytd-playlist-video-renderer:has(.badge-style-type-members-only)

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! 新闻媒体

! IT之家
! 右下角推广
ithome.com###down
ithome.com###side_func

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! 邮箱服务

! 163邮箱
! 页面背景广告、header、footer
mail.163.com##.main-inner-wrap

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! 社交媒体

! Reddit
! 游戏栏
reddit.com##faceplate-tracker[noun="games_drawer"]
reddit.com##faceplate-tracker[noun="games_drawer"] + hr

! 雪球
! 首页发帖区域
xueqiu.com##.editor-container
! 时间线官方账户广告
xueqiu.com##.timeline__item:has(.user-name[href="/1493325944"])
xueqiu.com##.timeline__item:has(.user-name[href="/6748279279"])

```
