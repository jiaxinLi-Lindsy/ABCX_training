#【ABCX任务设计说明】
前三个音 (A, B, C)：包含 standard、level sound、foil sound（顺序随机）
第四个音 (X)：只能是 standard 或 level sound 的复制

被试任务
判断 X 更像第一个音、第二个音，还是第三个音

【foil 选择规则】
距离: Foil 与 Level Sound 至少相隔 3 个难度等级
方向:
if (currentLevel ≤ 3) {
    foil 往更难方向选择（level 更高）
} else {
    foil 往更容易方向选择（level 更低）
}

设计意图：
确保 foil 与 level sound 有足够区分度
避免三个音太相似导致任务过难
防止被试通过排除法轻松答题

【正确答案设计】
X 永远不会匹配 foil
Standard 和 level sound 交替作为正确答案（平衡设计）

By YE Yanyuan