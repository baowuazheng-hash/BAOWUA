# 福利汇总

> 以下内容默认你自己完成益世界账号

## 一、微信汇总

### 1. 疯狂水世界活动站

#### 1.1. 进入方法

微信直接搜索 <NText type="primary" tag="b">疯狂水世界活动站</NText> <NButton @click="copyText('疯狂水世界活动站')" size="small" type="info">复制</NButton>

<NImage src="/crazy-water-world/image/福利/疯狂水世界活动站.png" alt="疯狂水世界" style="width: 150px;" />

#### 1.2. 礼包内容

- 企业好友专属见面礼（需要添加企业微信）
- 水世界月度福利限时领（需要添加企业微信）

### 2. 游戏圈

#### 2.1. 进入方法

- 加圈有礼（荒岛冒险头像框）
- 在线礼包（每天必拿）
- 每日抽奖（每天必拿）

<div class="flex-container">
    <NImage src="/crazy-water-world/image/福利/发现游戏.png" alt="疯狂水世界" style="width: 100px;" />
    <NImage src="/crazy-water-world/image/福利/圈子水世界.png" alt="疯狂水世界" style="width: 200px;" />
    <NImage src="/crazy-water-world/image/福利/每日抽奖.png" alt="疯狂水世界" style="width: 250px;" />
</div>

### 3. 益世界福利中心（类似心悦会员）

#### 3.1. 进入方法

微信直接搜索 <NText type="primary" tag="b">益世界福利中心</NText> <NButton @click="copyText('益世界福利中心')" size="small" type="info">复制</NButton>

<NImage src="/crazy-water-world/image/福利/益世界福利中心.png" alt="益世界福利中心" style="width: 150px;" />

<script setup lang="ts">
    import { NButton, NText, NImage } from 'naive-ui'
    import { createDiscreteApi } from 'naive-ui'

    const { message } = createDiscreteApi(['message'])

    const copyText = (text: string) => {
        navigator.clipboard.writeText(text)
        message.success('复制成功')
    }

</script>

<style scoped>
    .flex-container {
        display: flex;
        gap: 10px;
    }
</style>
