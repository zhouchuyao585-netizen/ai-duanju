# 统一负面提示词（negative-prompts）

## 中文负面词

- 现代手机、智能手表、现代汽车、地铁、现代高楼玻璃幕墙
- LED广告牌、现代品牌logo、二维码、霓虹赛博元素
- 不符合年代的服装（卫衣、运动潮牌、现代羽绒冲锋衣剪裁）
- 现代妆容（韩式平眉、夸张假睫毛、网红高光）
- 人物脸部畸形、手指增生、肢体错位、比例失真
- 过度磨皮、塑料皮肤、卡通化、Q版化
- 夸张舞台剧式表演、非写实表情包化
- 错误字幕、水印、平台logo、乱码文本
- 现代室内装潢（隐藏灯带、极简金属家具、现代厨电）

## English Negative Prompts

- modern smartphone, smartwatch, modern cars, subway system, contemporary glass skyscrapers
- LED billboards, modern brand logos, QR codes, cyberpunk neon style
- anachronistic clothing, modern streetwear hoodie, contemporary technical jackets
- heavy beauty makeup, plastic skin, over-retouched face
- deformed face, extra fingers, broken hand anatomy, distorted limbs
- cartoon style, chibi proportions, exaggerated anime rendering
- overacting theatrical expression, meme-like facial exaggeration
- visible subtitles, watermark, platform logo, corrupted text artifacts
- modern interior design, hidden LED strips, contemporary appliances

## 使用规则

- 负面提示词作为每条正向提示词的尾段追加。
- 若出现穿帮，优先补充“年代物件排除项”，再微调主体描述。

## 资料来源

- 结合剧本时代设定：`/scripts/被调换后，我在北大荒杀疯了 100集-编剧王中辉 (1).txt`

## 当前覆盖范围

- 适配本项目全场景的通用排错与去穿帮。
