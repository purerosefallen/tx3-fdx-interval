# tx3-fdx-interval
天下3跳舞各歌曲按空格间隔

## 关于本项目
本项目记录《天下3》妃蝶轩玩法中各歌曲按空格的间隔，用于部分自动按键脚本。
按照乐理知识，每小节的理论间隔应该为 `60 / bpm * 4`s，但是由于《天下3》的系统原因，直接使用理论值会导致偏移导致部分miss判定。因此按空格的间隔需要加上一个偏移值。
若大家发现本项目的偏移值有误，欢迎发 issue 或 pull request。

## 文档格式

```
歌曲 BPM 实际间隔(ms) 偏移值(ms)
```

eg.
```
建木 180 1323 -10
```
