| 错误码 | 描述 | 处理建议 |
| -- | -- | -- |
|  0 |  执行成功。 | - |
|  4 |  错误的后台请求参数。 | 请检查请求参数是否正确，如有疑问，请联系 ZEGO 技术支持。|
|  5 |  AppID 不可用。 | 请确认申请到的 AppID 是否正确。|
|  6 |  非法签名。 | 请确认申请到的 AppID 和 AppSign 是否匹配。|
|  8 |  AppID 校验失败。 | <p>请排查以下两种原因：</p><ul><li>AppID 或 AppSign 是否填写错误；</li><li>AppID 是否过期。</li></ul><p>如果仍无法解决，请联系 ZEGO 技术支持。</p>|
|  9 |  签名过期。 | 签名有时效性，有效期为 10 分钟。|
|  10 |  不是毫秒级时间戳。| 请确认时间戳是否正确。|
|  10001 |  后台请求的文本过长。|  后台请求文本过长，请联系 ZEGO 技术支持，确认后台请求字符限制。|
|  10002 |  传入文本非 UTF-8 编码。|  请检查传入文本格式，确保所有字符为 UTF-8 编码。|
|  10003 |  voice_type 非法。| 请参考音色列表。请联系 ZEGO 技术支持获取。|
|  10005 |  参数 volume 错误。| 请确认参数 volume 是否正确，范围为 [0,9]。|
|  10006 |  参数 speed 错误。| 请确认参数 speed 是否正确，范围为 [0,9]。|
|  20001 |  请求文本含有非法字符，或请求文本没有有效字符。| 请检查文本，如需确定非法字符，请联系 ZEGO 技术支持。 |
|  90004 |  初始化没有传入 Avatar 的 Character。| 请在 ZegoTextAPI 初始化时传入 Character。|
|  90005 |  `playTextExpression` 的 参数 text 为空。| 请确认参数 text 是否正确。|
|  90006 |  `playTextExpression` 的 参数 text 过长。| 请确认参数 text 是否小于 1000 个字符。|


















