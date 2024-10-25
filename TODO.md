v0.2.0
- [x] 新框架设计.
- [x] 待解决ma, ema指标位置定位.
- [x] 待解决ma, ema, candle 最大最小值.
- [x] 待解决最新价移出可视区后的变换.
- [x] macd指标计算与绘制.
- [x] 配置序列化反序列化框架实现.
- [x] 待解决指标配置管理.
- [x] 待解决calcuManager中数据缓存dirty.
- [x] 指标计算算法优化 (MAVOL, EMA, MACD).

v0.3.0
- [x] CandleModel重构(指标数据绑定到Model上).
- [x] 指标的定制化实现.
- [x] 指标计算与算法实现统一.
- [x] 优化核心框架状态可配置.
- [x] 配置管理调整: 由FlexiKlineConfig统一管理所有配置, FlexiKline构造时必传. 所有配置实现Serializer和CopyWith接口. 

v0.4.0
- [x] 主题切换实现.
- [x] 配置框架优化.
- [x] 数据加载接口封装.
- [x] 蜡烛数据合并算法优化.
- [x] 指标计算性能优化.
- [x] 手势操作优化.
- [x] Flutter最低支持版本

v0.5.0
- [x] 支持横屏.
- [x] 缩放优化.
- [x] 配置管理优化.
- [x] 添加指标要dispose解绑下. (clone需要给Indicator增加clone接口, 暂不考虑.)
- [x] 增加副图指标.

v0.6.0
- [x] 支持Desktop
- [x] 支持Web
- [x] 手势识别框架重构, 适配Web/Desktop
- [x] 自定义指标与替换内置指标demo.
- [x] 增加精度大于16的测试demo. 
- [ ] 文档撰写v1.
- [ ] 第一版: 1. 发布到pub; 2. github开源

v0.7.0
- [ ] 性能优化: 
  1. 更新蜡烛数据方式反转, 同步所有计算逻辑.
  2. 按需计算, 增加指标同时触发指标计算后, 再绘制.
  3. 考虑保留上次最新数据计算中间态, 当新数据更新时继续计算.
- [ ] 蜡烛数据超出double类型精度时, 自动切换使用ComputeMode.accurate模式, 优化CandleModel模型.
- [ ] 文档撰写v2.

v0.8.0
- [ ] Tooltip可点击实现.
- [ ] 画图工具实现.
- [ ] 画图框架实现.

v0.9.0
- [ ] 文档撰写v3.
- [ ] 全面调优.