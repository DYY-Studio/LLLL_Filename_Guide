# Link! Like! LoveLive! UnityFS 文件名指南
## @dummy后缀：预定追加 目前用别的图顶替的

## 编号索引
### 与卡面相关
*image_deck_frame_chara、icon_prof_sticker等也遵循该索引*

例：**image_card_full_10435020**

| 位 | 例 | 解读 | 意义 |
| :--: | :--: | :-- | :-- |
| 1-3 | 【104】35020 | 104期 | 入学年度 |
| 4 | 104【3】5020 | Mira-Cra Park!<br>（安养寺姬芽） | 所属组合 |
| 5 | 1043【5】020 | UR | 稀有度 |
| 6-7 | 10435【02】0 | 卡序号 | ~ |
| 8 | 1043502【0】 | 未突破 | 突破等级 |

**特殊：第1位 = 8**

*似乎只出现在image_card_middle_vertical*

指的是特殊卡（如舞会乃的松狮犬、吟子的服装卡）

#### 第4位：所属组合
| 数 | 所属组合 |
| :--: | :--: |
| 1 | Cerise Bouquet |
| 2 | DOLLCHESTRA |
| 3 | Mira-Cra Park! |

**特殊：1011XXXXX = 莲之空101期生（大贺美沙知）**

例：1031XXXXX = 日野下花帆（103期 Cerise Bouquet）

#### 第5位：稀有度
| R | SR | UR | DR | BR |
| :--: | :--: | :--: | :--: | :--: | 
| 3 | 4 | 5 | 8 | 9 |

#### 第8位：突破等级
| 0 | + | ++ |
| :--: | :--: | :--: |
| 0 | 1 | 2 |

### 与技能相关
例：**icon_skill_10213010**

| 位 | 例 | 解读 | 意义 |
| :--: | :--: | :-- | :-- |
| 1 | 【1】0213010 | SP技能 | 技能类型 |
| 2-3 | 1【02】13010 | 102期 | 入学年度 |
| 1 | 102【1】3010 | Cerise Bouquet<br>（乙宗梢） | 所属组合 |
| 1 | 1021【3】010 | UR | 稀有度 |
| 6-7 | 10213【01】0 | 卡序号 | ~ |
| 1 | 1021301【0】 | 未突破 | 突破情况 |

#### 第1位：技能类型
| SP | 一般 | 特性 |
| :--: | :--: | :--: |
| 1 | 2 | 3

### 与歌曲相关
例：**bgm_live_10310101@dream_believers_bpm162_4ver**、**icon_prof_sticker_40103101**

| 位 | 例 | 解读 | 意义 |
| :--: | :--: | :-- | :-- |
| 1 | 【1】0310101 | ？ | ？ |
| 2 | 1【03】10101 | 103期 | 发布年度 |
| 1 | 103【1】0101 | 原创曲 | 曲目类型 |
| 2 | 1031【01】01 | 序号01 | 序号 |
| 2 | 103101【01】 | 统一后缀 | 占位？ |

#### 第4位：曲目类型
| 原创 | Cover（其他） | Cover（LoveLive!） |
| :--: | :--: | :--: |
| 1 | 2 | 3

## image前缀：图像
### card次前缀：卡面相关
| 前缀 | 类型 | 其他 |
| :----------------------- | :---- | :---- |
| image_card_frame | 卡面外框 | 290x394 |
| image_card_frame_small | 卡面外框(小) | 192x264<br>59x115 |
| image_card_full | 完整卡面 | 1728x1120 |
| image_card_specialappeal | ? | |
| image_card_middle_vertical | 卡面中间部分(竖)<br>Live时显示的卡面 | |
| image_card_noget | 未获得DR卡时<br>DR界面的DR卡图标 | |
| image_card_sell_chara_frame | 角色名 | |
### comic次前缀：四格漫画
| 前缀 | 类型 | 其他 |
| :----------------------- | :---- | :---- |
| image_comic | 四格漫画 | |
| image_comic_thumbnail | 四格漫画封面 | |
### deck_frame次前缀：Live准备界面
| 前缀 | 类型 | 其他 |
| :----------------------- | :---- | :---- |
| image_deck_frame_icon | Live准备界面角色图标 | |
| image_deck_frame_main | Live准备界面的MAIN标识 | |
| image_deck_frame_side | Live准备界面的SIDE标识 | |
| image_deck_frame_name | Live准备界面的角色名标识 | |
| image_deck_frame_chara | Live准备界面小人 | |

### gacha次前缀：卡池相关
| 前缀 | 类型 | 其他 |
| :----------------------- | :---- | :---- |
| image_gacha_card_back | 卡背 | |
| image_gacha_card_info | 抽到后显示的卡信息条<br>【稀有度 角色名】 | |
| image_gacha_banner | 卡池界面的卡池图标 | |
| image_gacha_effect_bg | 抽卡时的背景图像 | |
| image_gacha_pack_full | 完整卡包图像 | |
| image_gacha_pack_01 | 撕完后的卡包 | |
| image_gacha_pack_turn | 卡包撕开那条边 | |
| image_gacha_pop | 特殊信息说明<br>如【SR以上一枚確定】 | |
| image_gacha_top | 卡池封面 | 1440x2020 |
| image_gacha_unit_logo | 抽到后显示的小组logo | |

### grade_live次前缀：Grade Live相关
| 前缀 | 类型 | 其他 |
| :----------------------- | :---- | :---- |
| image_grade_live_area | 已解锁Area图标 | 585x228 |
| image_grade_live_area_lock | 未解锁Area图标 | 585x228 |
| image_grade_live_background | 背景图 | 1680x2048 |
| image_grade_live_dot | 连结 | 30x25 |
| image_grade_live_pin | 指针 |  |
| image_grade_live_square | 节点 | 168x120 |
| image_grade_live_stage | 已解锁Stage图标 | 585x228 |
| image_grade_live_stage_lock | 未解锁Stage图标 | 585x228 |

### prof次前缀：个人档案相关
| 前缀 | 类型 | 其他 |
| :----------------------- | :---- | :---- |
| image_prof_custom | 编辑个人档案时<br>动态卡面的卡面缩略图 | 360x640 |
| image_prof_data_chara | 个人档案图Member Fan Lv.图标 | 1024x1024 |
| image_prof_data_chara_season | 个人档案图Season Fan Lv.图标 | 1024x1024 |
| image_prof_data_quest | Quest Live进行情况<br>（游戏内未实装） | 1024x1024 |
| image_prof_etc | 「其他」页的可选图像 | |

### quest次前缀：Quest Live 相关
| 前缀 | 类型 | 其他 |
| :----------------------- | :---- | :---- |
| image_quest_bg | Quest Live 背景图 | 1024x2048 |
| image_quest_live_area_button_lock | 未解锁Area | 585x230 |
| image_quest_live_area_button_normal | 已解锁Area | 585x230 |
| image_quest_live_area_button_select | ? | 585x230 |
| image_quest_live_area_select | ? | 236x154 |
| image_quest_live_stage_icon_off | 未解锁Live Stage | 140x108 | 
| image_quest_live_stage_icon_on | 已解锁Live Stage | 140x108 | 
| image_quest_live_stage_select | Live Stage选择指针 | 86x112 | 
| image_quest_live_stage_way | 连结 Live Stage 的点 | 30x26 | 


### record_monthly次前缀：每月活动记录相关
| 前缀 | 类型 | 其他 |
| :----------------------- | :---- | :---- |
| image_record_monthly | 活动记录每话封面 | 657x1115 |
| image_record_monthly_part | 活动记录每PART封面 | 828x238 |

### selectticket次前缀：自选券
| 前缀 | 类型 | 其他 |
| :----------------------- | :---- | :---- |
| image_selectticket_banner | 自选页图标 | 480x168 |
| image_selectticket_top | 自选页封面 | 1440x2020 |

### 其余
| 前缀 | 类型 | 其他 |
| :----------------------- | :---- | :---- |
| image_cchannel_banner | 学园偶像连结各频道头图 | |
| image_chara_stand | 角色介绍立绘 | |
| image_collection_schoolidol_bg | Collection中的<br>School Idol所用的背景图像 | 2000x2000 |
| image_download_os | 加载时的广告 | 800x800 |
| image_login_bonus | 登入奖励背景 | |
| image_mini_banner_pop | 卡池界面的卡池图标<br>右上角用的小POP | |
| image_music_thumbnail | 曲目封面 | |
| image_unit_logo | 各小组logo | |
| image_sticker | 全分辨率贴纸 | 600x600 | 
| image_grand_prix_logo | Grand Prix 图标 |  |
| image_help | 帮助 / 教程 | 1080x1920<br>1152x2048 |
| image_item_source_icon_daily_quest | 每日任务 | 100x100 |
| image_item_source_icon_standard_quest | 道具来源图标 | 100x100 |
| image_limited_paid_gacha_button | 有偿限定10连 | 280x280 |
| image_season_banner | (未实装) | |
| image_shop_banner | 商店头图 | 1600x380 |

## icon前缀：图标
| 前缀 | 类型 | 分辨率 |
| :----------------------- | :---- | :--: |
| icon_item_store_item | 商店物品图标 | |
| icon_cchannel | 学园偶像连结<br>各小组频道小图标 | 200x200 |
| icon_emoji_category | Emoji分类图标 | |
| icon_face | 头像 | |
| icon_face_sd | 小头像 | |
| icon_item | 道具图标 | |
| icon_itemframe_emoji | Emoji后的矩形 | |
| icon_itemframe_item | 道具图标后的圆圈 | |
| icon_membership_item | 会员卡(月卡)图标 | |
| icon_mood | Mood图标 | |
| icon_music_mastery_skill | Learning Live 效果图标 | |
| icon_payment_item | 氪金内容图标 | |
| icon_prof_sticker | 贴纸缩略图 | |
| icon_prof_card | 卡面缩略图 | 380x248 |
| icon_skill | 技能图标 | 284x284<br>284x293(SP) |
| icon_song_type | 歌曲Mood图标 | 120x120 |
| icon_style_type | 卡类型图标 | 120x120 |

## stage前缀：Live Stage 内容
| 前缀 | 类型 |
| :------- | :---- |
| stage_idol_model | Live Stage 小人的各部件 |

## card_view_num_card_ap/num_card_ap前缀：AP数字
| Num | Mood |
| :--: | :---- |
| 1 | Happy　ハッピー |
| 2 | Neutral　ニュートラル |
| 3 | Mellow　メロウ |

## grade前缀：Grade Live 相关
| 前缀 | 类型 |
| :------- | :---- |
| grade_rank | Grade Rank 对应图像 |
| grade_trophy | Grade Rank 对应奖杯 |
| grade_trophy_icon | 奖杯图标 |

## live前缀：Live 界面
| 前缀 | 类型 | 分辨率 |
| :----------------------- | :---- | :--: |
| live_stage_image | Live舞台(背景)图像 | 980x594 |
| live_stage_image_short | Live舞台(背景)图像(短) | 980x344 |
| live_top_button_fanlv_filter | Fan Lv.不足时显示的禁止条 | 816x147 |
| live_top_button_formation | 「编成」按键 | 474x288 |
| live_top_button_training | 「育成」按键 | 478x288 |

## picture前缀：外部视频封面图
| 前缀 | 类型 | 分辨率 |
| :----------------------- | :---- | :--: |
| picture_introduction_thumbnail | 角色自我介绍视频封面 | 640x360 |
| picture_schoolidolstage_tutorial_thumbnail | 学园偶像舞台教程视频封面 | 960x540 |
| picture_story_digest_thumbnail | 故事概要视频封面 | 960x540 |

## quest_live前缀：Quest Live 相关
| 前缀 | 类型 |
| :----------------------- | :---- |
| quest_live_num_stage_lv_off | 未解锁Quest Live上标注的Lv. |
| quest_live_num_stage_lv_on | 已解锁Quest Live上标注的Lv. |

## raid_event前缀：Link to Us Link with yours 活动相关
| 前缀 | 类型 |
| :----------------------- | :---- |
| raid_event_banner | 活动标题图像 |
| raid_event_button | 活动入口 |
| raid_event_grid | ? |
| raid_event_particle | ? |
| raid_event_tank | 流量容器 |
| raid_event_top_bg | 活动背景 |
| raid_event_top_llmobile | LL Mobile 图标 |

## story前缀：活动记录相关
| 前缀 | 类型 | 分辨率 |
| :----------------------- | :---- | :--: |
| story_thumbnail | 活动记录封面 | |
| story_bg_image | 活动记录背景 | |
| story_thumbnail | 活动记录播放结束后下一话缩略图 | 960x540 |

## top前缀：学园偶像舞台界面相关
| 前缀 | 类型 |
| :----------------------- | :---- |
| top_background | 背景图 | 
| top_daily | 每日任务 |
| top_dream | Dream Live |
| top_quest | Quest Live |

## campaign前缀：各种 Live Stage 活动
## beginner_mission前缀：新手教程
## deck_edit_back_ground_stage：编组编辑界面
## face前缀：Emoji表情

## ui前缀：我懒得写了()

## 杂项
| 前缀 | 类型 |
| :------- | :---- |
| launcher | 菜单界面元素 |
| audience | 观众的贴图 |
| Audience_Penlight | 观众荧光棒贴图 |
| Container: sc_emoji_sprite | Emoji |
| learning_member_name | Learning Live 所用的成员名称 |
| limited_type | 限定类型 |
| outgame_chara_sd_spine | SD小人部件 |
| penlight | 荧光棒图标 |
| SCSch | 模型贴图 |
| tex | 贴图 |
| spriteasset_image_prof_data_chara | 个人档案Fan Lv.所用数字 |
