# 欢拓云直播WEB API

## 安装

```
composer require oiuv/talkfun-sdk
```

## 使用

```php
use Oiuv\TalkFunSdk\MTCloud;

$config = [
    'openID' => '***',
    'openToken' => '***',
];

$MTCloud = new MTCloud($config);

//获取一个直播专辑
$res = $MTCloud->albumGet(123456);

//获取剪辑信息
$res = $MTCloud->clipGet(123456);

//获取剪辑列表
$res = $MTCloud->clipList();

//获取直播间地址
$res = $MTCloud->userAccessUrl(7300637,'雪风小哥哥','user',123456);


```

| [方法列表](http://open.talk-fun.com/docs/api/user.html) |
| --- |
|  setFormat()
|  userAccess()
|  userAccessPlayback()
|  userAccessUrl()
|  userAccessKey()
|  userAccessPlaybackUrl()
|  userAccessPlaybackKey()
|  userAccessPlaybackAlbum()
|  userAccessPlaybackAlbumUrl()
|  userAccessPlaybackAlbumKey()
|  userAccessPlaybackClip()
|  userAccessPlaybackClipUrl()
|  userAccessPlaybackClipKey()
|  userOnlineList()
|  roomGetInfo()
|  roomGetUrl()
|  roomCreate()
|  roomAutoCreate()
|  roomUpdate()
|  roomDrop()
|  roomList()
|  roomBindAccount()
|  roomUnbindAccount()
|  roomBroadcastSend()
|  roomOnlineTotal()
|  roomAddRobot()
|  roomNoticeRoll()
|  zhuboLogin()
|  zhuboRoomLogin()
|  zhuboGet()
|  zhuboCreate()
|  zhuboUpdateInfo()
|  zhuboUpdatePassword()
|  zhuboDel()
|  zhuboList()
|  zhuboUpdatePortrait()
|  zhuboUpdateExt()
|  zhuboGetExt()
|  scoreLiveList()
|  scoreZhuboList()
|  liveGet()
|  liveGetBatch()
|  liveGetLast()
|  liveList()
|  liveListAll()
|  liveMessageList()
|  liveFlowerList()
|  liveVoteAdd()
|  liveVoteEnd()
|  liveVoteEmit()
|  liveVoteDelete()
|  liveVoteUpdate()
|  liveStreamAddress()
|  liveQaAdd()
|  liveQaAudit()
|  liveQaDelete()
|  liveQaAnswer()
|  liveQaList()
|  liveQaTotal()
|  albumCreate()
|  albumGet()
|  albumDelete()
|  albumAdd()
|  albumRemove()
|  albumCreateCourse()
|  albumAddCourse()
|  albumRemoveCourse()
|  liveRoomGet()
|  liveRoomList()
|  liveVisitorList()
|  liveVisitorGet()
|  liveQuestionList()
|  liveAudioDownloadUrl()
|  livePlaybackVisitorList()
|  livePlaybackVisitorTimeList()
|  liveChapterList()
|  livePlaybackVideo()
|  livePlaybackLoginUrl()
|  liveVoteList()
|  liveVoteDetail()
|  liveLotteryList()
|  livePrivateChatList()
|  courseAdd()
|  courseAccess()
|  courseAccessPlayback()
|  courseAccessUrl()
|  courseAccessKey()
|  courseAccessPlaybackUrl()
|  courseGet()
|  courseBroadcastSend()
|  courseDelete()
|  courseList()
|  courseUpdate()
|  courseVoteDetail()
|  courseVoteList()
|  courseVoteEmit()
|  courseVoteDelete()
|  courseVoteUpdate()
|  courseLotteryList()
|  courseAudioDownloadUrl()
|  courseVisitorList()
|  coursePlaybackVisitorList()
|  courseVisitorListAll()
|  courseLogin()
|  courseChapterList()
|  courseQuestionList()
|  courseFlowerList()
|  courseMessageList()
|  courseDocumentUpload()
|  courseDocumentList()
|  courseDocumentDelete()
|  courseLaunch()
|  courseVideo()
|  courseConfig()
|  courseUpdateConfig()
|  courseStreamAddress()
|  courseZhuboAdd()
|  courseZhuboList()
|  courseZhuboUpdate()
|  courseZhuboBindAccount()
|  courseZhuboPortrait()
|  courseRobotSet()
|  courseNoticeRoll()
|  courseVoteAdd()
|  courseVoteEnd()
|  courseOnlineList()
|  courseOnlineAdmin()
|  courseQaAdd()
|  courseQaAudit()
|  courseQaDelete()
|  courseQaAnswer()
|  courseQaList()
|  courseQaTotal()
|  coursePrivateChatList()
|  clipAdd()
|  clipUpdate()
|  clipDelete()
|  clipGet()
|  clipList()
|  clipListByCid()
|  clipAddByCid()
|  documentUpload()
|  documentDownload()
|  documentList()
|  documentGet()
|  documentDelete()
|  departmentCreate()
|  departmentUpdate()
|  departmentDelete()
|  departmentGet()
|  departmentGetBatch()
|  videoGetUploadUrl()
|  videoGet()
|  videoGetBatch()
|  videoDelete()
|  videoUpload()
|  audioGetUploadUrl()
|  audioGet()
|  audioGetBatch()
|  audioDelete()
|  moduleSet()
|  commentAdd()
|  commentDelete()
|  commentList()
|  uploadFileData()
|  utilsShortUrl()
|  statsPeakCourse()
|  statsPeakLive()
|  consoleAutoLogin()
|  registerCallbackHandler()
|  callbackService()
|  response()
|  generateSign()
|  call()
|  generateGuestId()
|  base64UrlEncode()

> 接口文档：[欢拓云直播接入指南](https://open.talk-fun.com/docs/getstart/index.html)
