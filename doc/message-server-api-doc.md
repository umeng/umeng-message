<p align="CENTER">
    <strong>友盟推送服务器端</strong>
    <strong>API</strong>
    <strong>使用说明</strong>
</p>
<h1>
    目录
</h1>
><div id="Table of Contents1" dir="LTR">
    <p>
        <a href="#__RefHeading__2401_1239996969">一. 概述</a>
    </p>
</div> 
  
>><div id="Table of Contents1" dir="LTR">
    <p>
        <a href="#__RefHeading__2403_1239996969">1.1</a>
        <a href="#__RefHeading__2403_1239996969">基本说明</a>
    </p>
</div>
  
><div id="Table of Contents1" dir="LTR">
    <p>
        <a href="#__RefHeading__2405_1239996969">二. 接口描述</a>
    </p>
</div>
  
>><div id="Table of Contents1" dir="LTR">
    <p>
        <a href="#__RefHeading__2407_1239996969">2.1</a>
        <a href="#__RefHeading__2407_1239996969">消息发送</a>
    </p>
</div>
    
>>><div id="Table of Contents1" dir="LTR">
    <p>
        <a href="#__RefHeading__2409_1239996969">2.1.1 </a>
        <a href="#__RefHeading__2409_1239996969">功能说明</a>
    </p>
    <p>
        <a href="#__RefHeading__2411_1239996969">2.1.2</a>
        <a href="#__RefHeading__2411_1239996969">调用地址</a>
    </p>
    <p>
        <a href="#__RefHeading__2413_1239996969">2.2.3</a>
        <a href="#__RefHeading__2413_1239996969">调用参数</a>
    </p>
    <p>
        <a href="#__RefHeading__2415_1239996969">2.1.4 </a>
        <a href="#__RefHeading__2415_1239996969">调用返回</a>
    </p>
    <p>
        <a href="#__RefHeading__2417_1239996969">2.1.5</a>
        <a href="#__RefHeading__2417_1239996969">回调接口</a>
    </p>
</div>
        
>><div id="Table of Contents1" dir="LTR">
    <p>
        <a href="#__RefHeading__2419_1239996969">2.2 </a>
        <a href="#__RefHeading__2419_1239996969">发送任务状态查询</a>
    </p>
</div>
    
>>><div id="Table of Contents1" dir="LTR">
    <p>
        <a href="#__RefHeading__2421_1239996969">2.2.1 </a>
        <a href="#__RefHeading__2421_1239996969">功能说明</a>
    </p>
    <p>
        <a href="#__RefHeading__2423_1239996969">2.2.2 </a>
        <a href="#__RefHeading__2423_1239996969">调用地址</a>
    </p>
    <p>
        <a href="#__RefHeading__2425_1239996969">2.2.3 </a>
        <a href="#__RefHeading__2425_1239996969">调用参数</a>
    </p>
    <p>
        <a href="#__RefHeading__2427_1239996969">2.2.4 </a>
        <a href="#__RefHeading__2427_1239996969">调用返回</a>
    </p>
</div>
    
>><div id="Table of Contents1" dir="LTR">
    <p>
        <a href="#__RefHeading__2429_1239996969">2.3 </a>
        <a href="#__RefHeading__2429_1239996969">取消任务</a>
    </p>
</div>

>>><div id="Table of Contents1" dir="LTR">
    <p>
        <a href="#__RefHeading__2431_1239996969">2.3.1 </a>
        <a href="#__RefHeading__2431_1239996969">功能说明</a>
    </p>
    <p>
        <a href="#__RefHeading__2433_1239996969">2.3.2 </a>
        <a href="#__RefHeading__2433_1239996969">调用地址</a>
    </p>
    <p>
        <a href="#__RefHeading__2435_1239996969">2.3.3 </a>
        <a href="#__RefHeading__2435_1239996969">调用参数</a>
    </p>
    <p>
        <a href="#__RefHeading__2437_1239996969">2.3.4 </a>
        <a href="#__RefHeading__2437_1239996969">调用返回</a>
    </p>
</div>
    
><div id="Table of Contents1" dir="LTR">
    <p>
        <a href="#__RefHeading__2439_1239996969">附录</a>
    </p>
</div>
    
>><div id="Table of Contents1" dir="LTR">
    <p>
        <a href="#__RefHeading__2441_1239996969">附录</a>
        <a href="#__RefHeading__2441_1239996969">A unicast</a>
        <a href="#__RefHeading__2441_1239996969">消息发送示例</a>
    </p>
    <p>
        <a href="#__RefHeading__2443_1239996969">附录</a>
        <a href="#__RefHeading__2443_1239996969">B listcast</a>
        <a href="#__RefHeading__2443_1239996969">消息发送示例</a>
    </p>
    <p>
        <a href="#__RefHeading__2445_1239996969">附录</a>
        <a href="#__RefHeading__2445_1239996969">C broadcast</a>
        <a href="#__RefHeading__2445_1239996969">消息发送示例</a>
    </p>
    <p>
        <a href="#__RefHeading__2447_1239996969">附录</a>
        <a href="#__RefHeading__2447_1239996969">D groupcast</a>
        <a href="#__RefHeading__2447_1239996969">消息发送示例</a>
    </p>
    <p>
        <a href="#__RefHeading__2449_1239996969">附录</a>
        <a href="#__RefHeading__2449_1239996969">E customizedcast</a>
        <a href="#__RefHeading__2449_1239996969">消息发送示例</a>
    </p>
    <p>
        <a href="#__RefHeading__2451_1239996969">附录</a>
        <a href="#__RefHeading__2451_1239996969">F </a>
        <a href="#__RefHeading__2451_1239996969">过滤条件示例</a>
    </p>
    <p>
        <a href="#__RefHeading__2453_1239996969">附录</a>
        <a href="#__RefHeading__2453_1239996969">G MD5</a>
        <a href="#__RefHeading__2453_1239996969">生成代码示例</a>
    </p>
</div>

<h1>
    <a name="_Toc373181457"></a>
    <a name="__RefHeading__2401_1239996969"></a>
    一 概述
</h1>
<h2>
    <a name="_Toc373181458"></a>
    <a name="__RefHeading__2403_1239996969"></a>
    1.1 基本说明
</h2>
>>
>><p align="LEFT">
        本文描述的Push API接口协议均基于HTTP Rest协议消息，若无特殊说明接口均使用UTF-8编码，消息体参数采用Json格式.
</p>
>><p align="LEFT">
    在使用这些API前需要获取appkey和app_master_secret<a name="sdfootnote1anc" href="#sdfootnote1sym"><sup>1</sup></a>，同时在web后台<a name="sdfootnote1anc" href="#sdfootnote1sym"><sup>1</sup></a>添加您的服务器IP.
</p>

>>**<p align="LEFT">
    appkey：应用唯一标识
</p>**

>>**<p align="LEFT">
    app_master_secret：应用密钥
</p>**
<h1>
    <a name="Bookmark"></a>
    <a name="__RefHeading__2405_1239996969"></a>
    <a name="_Toc373181459"></a>
</h1>


<h1>
    二 接口描述
</h1>
<h2>
    <a name="_Toc373181460"></a>
    <a name="__RefHeading__2407_1239996969"></a>
    2.1消息发送
</h2>

><h3>
    <a name="_Toc373181461"></a>
    <a name="__RefHeading__2409_1239996969"></a>
    2.1.1 功能说明
</h3>

>><p>
        开发者调用此接口，向指定终端用户(单播)、所有终端用户(广播)或满足特定条件的终端用户群(组播)，发送通知消息或自定义消息.
</p>

><h3>
    <a name="_Toc373181462"></a>
    <a name="__RefHeading__2411_1239996969"></a>
    2.1.2 调用地址
</h3>

>><p>
    POST http://msg.umeng.com/api/send
</p>

><h3>
    <a name="_Toc373181463"></a>
    <a name="__RefHeading__2413_1239996969"></a>
    2.1.3 调用参数
</h3>

>><table width="800" cellpadding="20" cellspacing="0">
    <colgroup>
        <col width="122"/>
        <col width="44"/>
        <col width="74"/>
        <col width="46"/>
        <col width="80"/>
        <col width="35"/>
        <col width="4365"/>
        <col width="86"/>
    </colgroup>
    <tbody>
        <tr valign="TOP">
            <td width="122">
                <p>
                    <strong>参数</strong>
                </p>
            </td>
            <td width="800">
                <p>
                    <strong>选择项</strong>
                </p>
            </td>
            <td colspan="6" width="500">
                <p>
                    <strong>说明</strong>
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="122">
                <p>
                    appkey
                </p>
            </td>
            <td width="130">
                <p>
                    必选
                </p>
            </td>
            <td colspan="6" width="500">
                <p>
                    应用唯一标识
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="122">
                <p>
                    validation_token
                </p>
            </td>
            <td width="44">
                <p>
                    必选
                </p>
            </td>
            <td colspan="6" width="387">
                <p>
                    appkey, app_master_secret和timestamp的MD5的sum, 示例代码请参照附录G, 注意：app_master_secret请先全部转换成小写形式
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="122">
                <p>
                    timestamp
                </p>
            </td>
            <td width="44">
                <p>
                    必选
                </p>
            </td>
            <td colspan="6" width="387">
                <p>
                    上面生成MD5时的时间戳（请用String类型）
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="122">
                <p>
                    type
                </p>
            </td>
            <td width="44">
                <p>
                    必选
                </p>
            </td>
            <td colspan="6" width="387">
                <p>
                    消息类型，可以是：
                </p>
                <p>
                    unicast(单播);
                </p>
                <p>
                    listcast(列播, 多个device_tokens, 用英文逗号分隔);
                </p>
                <p>
                    groupcast(组播, 按照filter条件过滤, 具体请参考filter参数);
                </p>
                <p>
                    broadcast(广播);
                </p>
                <p>
                    customizedcast(通过开发者定义的alias和umeng的device_tokens进行映射, 可以传入单个alias, 也可以传入文件id。具体请参照alias和file_id参数);
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="122">
                <p>
                    device_tokens
                </p>
            </td>
            <td width="44">
                <p>
                    可选
                </p>
            </td>
            <td colspan="6" width="387">
                <p>
                    当消息类型为unicast时，此参数表示指定的单个设备;
                </p>
                <p>
                    当消息类型为listcast时，此参数表示多个设备<a name="sdfootnote3anc" href="#sdfootnote3sym"><sup>3</sup></a>，格式为"id1,id2,id3…"，多个id使用英文逗号分隔;
                </p>
                <p>
                    当消息类型为groupcast，broadcast和customizedcast时，无需填写此参数.
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="122">
                <p>
                    alias
                </p>
            </td>
            <td width="44">
                <p>
                    可选
                </p>
            </td>
            <td colspan="6" width="387">
                <p>
                    当type为customizedcast时，填写开发者自己的alias，多个alias<a name="sdfootnote3anc" href="#sdfootnote3sym"><sup>3</sup></a>时用英文逗号分隔。
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="122">
                <p>
                    file_id
                </p>
            </td>
            <td width="44">
                <p>
                    可选
                </p>
            </td>
            <td colspan="6" width="387">
                <p>
                    可以把alias存到文件里，通过上传文件接口获取对应的file_id, 实现通过文件的方式发送消息。具体请参照文件上传接口。
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="122">
                <p>
                    filter
                </p>
            </td>
            <td width="44">
                <p>
                    可选
                </p>
            </td>
            <td colspan="6" width="387">
                <p>
                    终端用户群筛选条件,如用户标签、地域、应用版本以及分发渠道等，使用方法请参考附录 F.
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td rowspan="23" width="122" height="10">
                <p>
                    payload
                </p>
            </td>
            <td rowspan="23" width="44">
                <p>
                    必选
                </p>
            </td>
            <td colspan="6" width="387">
                <p>
                    消息内容(Andriod最大512Byte)，其包含的参数说明如下:
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="74">
                <p>
                    <strong>参数</strong>
                </p>
            </td>
            <td width="60">
                <p>
                    <strong>选择项</strong>
                </p>
            </td>
            <td colspan="4" width="239">
                <p>
                    <strong>说明</strong>
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="74">
                <p>
                    display_type
                </p>
            </td>
            <td width="46">
                <p>
                    Android必选
                </p>
            </td>
            <td colspan="4" width="239">
                <p>
                    <a name="__DdeLink__2454_1239996969"></a>
                    payload类型，notification或message.
                </p>
                <p>
                    notification：由友盟处理消息内容在通知栏的展示和提醒方式.
                </p>
                <p>
                    message：应用自己解析和处理消息内容。友盟不对该内容进行展示和提醒.
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td rowspan="15" width="94">
                <p>
                    body
                </p>
            </td>
            <td rowspan="15" width="66">
                <p>
                    Android必选
                </p>
            </td>
            <td colspan="4" width="239">
                <p>
                    当display_type为message时，body的内容只需填写custom字段；当display_type为notification时，body可包含如下参数:
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="80">
                <p>
                    <strong>参数</strong>
                </p>
            </td>
            <td width="800">
                <p>
                    <strong>选择项</strong>
                </p>
            </td>
            <td colspan="2" width="230">
                <p>
                    <strong>说明</strong>
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="80">
                <p>
                    ticker
                </p>
            </td>
            <td width="35">
                <p>
                    必选
                </p>
            </td>
            <td colspan="2" width="96">
                <p>
                    通知栏提示文字
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="80">
                <p>
                    title
                </p>
            </td>
            <td width="35">
                <p>
                    必选
                </p>
            </td>
            <td colspan="2" width="96">
                <p>
                    通知标题
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="80">
                <p>
                    text
                </p>
            </td>
            <td width="35">
                <p>
                    必选
                </p>
            </td>
            <td colspan="2" width="96">
                <p>
                    通知文字描述
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="80">
                <p>
                    icon
                </p>
            </td>
            <td width="35">
                <p>
                    可选
                </p>
            </td>
            <td colspan="2" width="96">
                <p>
                    状态栏图标ID, R.drawable.[smarllIcon]， 如果没有， 默认使用应用图标。 图片要求为24dp*24dp 的图标， 或 24*24px在drawable-mdpi 下. 注意四周各留1个dp 的空白像素
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="80">
                <p>
                    largeIcon
                </p>
            </td>
            <td width="35">
                <p>
                    可选
                </p>
            </td>
            <td colspan="2" width="96">
                <p>
                    通知栏拉开后左侧图标 ID, R.drawable.[largeIcon]. 图片要求为 64*64 dp 的图标. 可设计一张64*64px 放在 drawable-mdpi 下, 注意图片四周留空，不至于显示太拥挤
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="80">
                <p>
                    img
                </p>
            </td>
            <td width="35">
                <p>
                    可选
                </p>
            </td>
            <td colspan="2" width="96">
                <p>
                    通知栏图标文件URL
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="80">
                <p>
                    sound
                </p>
            </td>
            <td width="35">
                <p>
                    可选
                </p>
            </td>
            <td colspan="2" width="96">
                <p>
                    通知提醒声音文件URL
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="80">
                <p>
                    play_vibrate
                </p>
            </td>
            <td width="35">
                <p>
                    可选
                </p>
            </td>
            <td colspan="2" width="96">
                <p>
                    收到通知是否震动，默认为true
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="80">
                <p>
                    play_lights
                </p>
            </td>
            <td width="35">
                <p>
                    可选
                </p>
            </td>
            <td colspan="2" width="96">
                <p>
                    收到通知是否闪灯，默认为true
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="80">
                <p>
                    play_sound
                </p>
            </td>
            <td width="35">
                <p>
                    可选
                </p>
            </td>
            <td colspan="2" width="96">
                <p>
                    收到通知是否发出声音，默认为true
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="80">
                <p>
                    url
                </p>
            </td>
            <td width="35">
                <p>
                    可选
                </p>
            </td>
            <td colspan="2" width="96">
                <p>
                    通知栏点击后跳转的URL
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="80">
                <p>
                    activity
                </p>
            </td>
            <td width="35">
                <p>
                    可选
                </p>
            </td>
            <td colspan="2" width="96">
                <p>
                    通知栏点击后打开的Activity
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="80">
                <p>
                    custom
                </p>
            </td>
            <td width="35">
                <p>
                    必选/可选
                </p>
            </td>
            <td colspan="2" width="96">
                <p>
                    用户自定义内容(如果display_type为message， 该字段为必选)
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td rowspan="5" width="74">
                <p>
                    apns (暂缓开通)
                </p>
            </td>
            <td rowspan="5" width="46">
                <p>
                    IOS必选
                </p>
            </td>
            <td colspan="4" width="239">
                <p>
                    此参数用于ios推送，其包含如下参数，其中alert和badge必须至少有一个填充有效值:
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="8">
                <p>
                    <strong>参数</strong>
                </p>
            </td>
            <td colspan="2" width="6">
                <p>
                    <strong>选择项</strong>
                </p>
            </td>
            <td width="8886">
                <p>
                    <strong>说明</strong>
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="80">
                <p>
                    alert
                </p>
            </td>
            <td colspan="2" width="46">
                <p>
                    必选
                </p>
            </td>
            <td width="86">
                <p>
                    提示窗口文字
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="80">
                <p>
                    badge
                </p>
            </td>
            <td colspan="2" width="46">
                <p>
                    必选
                </p>
            </td>
            <td width="86">
                <p>
                    显示在手机应用图标上的数字
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="80">
                <p>
                    sound
                </p>
            </td>
            <td colspan="2" width="46">
                <p>
                    可选
                </p>
            </td>
            <td width="86">
                <p>
                    提示声音
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td rowspan="4" width="122" height="54">
                <p>
                    policy
                </p>
            </td>
            <td rowspan="4" width="44">
                <p>
                    可选
                </p>
            </td>
            <td colspan="6" width="387">
                <p>
                    发送策略，指定开始发送消息的时间和消息过期的时间，默认为立即发送，过期时间为3天后.只针对groupcast，broadcast，customizedcast(通过上传文件方式传入file_id)有效，其包含的参数说明如下:
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="74">
                <p>
                    <strong>参数</strong>
                </p>
            </td>
            <td width="46">
                <p>
                    <strong>选择项</strong>
                </p>
            </td>
            <td colspan="4" width="239">
                <p>
                    <strong>说明</strong>
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="74">
                <p>
                    start_time
                </p>
            </td>
            <td width="46">
                <p>
                    可选
                </p>
            </td>
            <td colspan="4" width="239">
                <p>
                    开始发送时间，其值不可小于当前时间，格式为”YYYY-MM-DD hh-mm-ss”，如"2013-08-30 12:00:00"
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="74">
                <p>
                    expire_time
                </p>
            </td>
            <td width="46">
                <p>
                    可选
                </p>
            </td>
            <td colspan="4" width="239">
                <p>
                    消息过期时间，其值不可小于当前时间，默认为3天后过期，格式和start_time格式相同
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="122">
                <p>
                    feedback
                </p>
            </td>
            <td width="44">
                <p>
                    可选
                </p>
            </td>
            <td colspan="6" width="387">
                <p>
                    发送结果的回调接口URL，在type为groupcast、broadcast或者customizedcast(通过上传文件方式传入file_id)，可使用此参数。具体请参照2.1.5
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="122">
                <p>
                    description
                </p>
            </td>
            <td width="44">
                <p>
                    可选
                </p>
            </td>
            <td colspan="6" width="387">
                <p>
                    发送任务文字描述，建议填写。
                </p>
            </td>
        </tr>
    </tbody>
</table>

<h3>
    <a name="_Toc373181464"></a>
    <a name="__RefHeading__2415_1239996969"></a>
</h3>

><h3>
    2.1.4 调用返回
</h3>

>><p>
    在正常情况下，返回消息的状态码为200，错误情况下一般为500或其他标准的HTTP错误码. 返回结果采用Json格式，包含的参数有:
</p>
<p>
    ret: 消息结果，"FAIL"或"SUCCESS"
</p>
<p>
    data：返回结果内容描述
</p>
<p>
    当ret为"FAIL"时，此参数描述错误的原因.
</p>
<p>
    当ret为"SUCCESS"时，当type为"unicast"时，此参数描述msg_id的值；在type为"listcast"，此参数描述msg_id的多个值；当type为"grouplist"或"broadcast"时，此参数描述task_id的值；在type为customizedcast时，当file_id为空，alias不空时，此参数描述成功的msg_id的值，
    当file_id不空时，此参数描述task_id的值。
</p>
<p>
    实例请参考附录A~E.
</p>

><h3>
    <a name="_Toc373181465"></a>
    <a name="__RefHeading__2417_1239996969"></a>
    2.1.5回调接口
</h3>

>><p>
    当type为"groupcast"，"broadcast"或"customizedcast"(通过file_id)的消息发送完成后，会通过POST方式回调此发送任务指定的feedback回调接口，回调消息采用Json格式，包含的参数有:
</p>
<p>
    is_success: 任务处理是否成功，其值是"true" or "false"
</p>
<p>
    accept_count: 消息受理数
</p>
<p>
    send_count: 消息计划发送数
</p>
<p>
    task_id: 发送任务ID
</p>

<h2>
    <a name="_Toc373181466"></a>
    <a name="__RefHeading__2419_1239996969"></a>
    2.2 发送任务状态查询
</h2>

><h3>
    <a name="_Toc373181467"></a>
    <a name="__RefHeading__2421_1239996969"></a>
    2.2.1 功能说明
</h3>

>><p>
    当消息发送的type类型为groupcast，broadcast或者customizedcast(通过file_id传参),
    可以查询task_id对应的当前状态.当type类型为unicast，listcast或者customizedcast的file_id为空，alias不空时，不提供发送对应msg_id的状态查询功能.
</p>

><h3>
    <a name="_Toc373181468"></a>
    <a name="__RefHeading__2423_1239996969"></a>
    2.2.2 调用地址
</h3>

>><p>
    POST http://msg.umeng.com/api/status
</p>

><h3>
    <a name="_Toc373181469"></a>
    <a name="__RefHeading__2425_1239996969"></a>
    2.2.3 调用参数
</h3>

>><table width="595" cellpadding="7" cellspacing="0">
    <colgroup>
        <col width="115"/>
        <col width="57"/>
        <col width="382"/>
    </colgroup>
    <tbody>
        <tr valign="TOP">
            <td width="115">
                <p>
                    <strong>参数</strong>
                </p>
            </td>
            <td width="57">
                <p>
                    <strong>选择项</strong>
                </p>
            </td>
            <td width="382">
                <p>
                    <strong>说明</strong>
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="115">
                <p>
                    appkey
                </p>
            </td>
            <td width="57">
                <p>
                    必选
                </p>
            </td>
            <td width="382">
                <p>
                    应用唯一标识
                </p>
            </td>
        </tr>
        <tr valign="TOP">
                    <td width="122">
                        <p>
                            validation_token
                        </p>
                    </td>
                    <td width="44">
                        <p>
                            必选
                        </p>
                    </td>
                    <td colspan="6" width="387">
                        <p>
                            appkey, app_master_secret和timestamp的MD5的sum, 其中app_master_secret请先全部转换成小写形式
                        </p>
                    </td>
                </tr>
                <tr valign="TOP">
                    <td width="122">
                        <p>
                            timestamp
                        </p>
                    </td>
                    <td width="44">
                        <p>
                            必选
                        </p>
                    </td>
                    <td colspan="6" width="387">
                        <p>
                            上面生成MD5时的时间戳（请用String类型）
                        </p>
                    </td>
                </tr>
        <tr valign="TOP">
            <td width="115">
                <p>
                    task_id
                </p>
            </td>
            <td width="57">
                <p>
                    必选
                </p>
            </td>
            <td width="382">
                <p>
                    消息发送时，从返回消息中获取的task_id.
                </p>
            </td>
        </tr>
    </tbody>
</table>

><h3>
    <a name="_Toc373181470"></a>
    <a name="__RefHeading__2427_1239996969"></a>
    2.2.4 调用返回
</h3>

>><p>
    返回的Json格式信息包括如下内容:
</p>
<p>
    ret: 查询操作结果，FAIL或SUCCESS
</p>
<p>
    data: 查询状态内容描述，如果ret为FAIL包括失败原因，如果ret为SUCCESS，包括的参数有：
</p>
<p>
    task_id: 任务ID
</p>
<p>
    status: 消息状态，0表示排队中，1表示发送中，2表示发送完成，3表示发送失败，4表示被撤销，5表示发送过期，6表示筛选结果为空。
</p>
<p>
    total_count：消息计划发送数
</p>
<p>
    accept_count：消息受理数
</p>

<h2>
    <a name="_Toc373181471"></a>
    <a name="__RefHeading__2429_1239996969"></a>
    2.3 取消任务
</h2>

><h3>
    <a name="_Toc373181472"></a>
    <a name="__RefHeading__2431_1239996969"></a>
    2.3.1 功能说明
</h3>

>><p>
    当消息发送的type类型为groupcast，broadcast或者customizedcast(通过file_id传参),
    可以取消对应的正在进行中的发送任务
</p>

><h3>
    <a name="_Toc373181473"></a>
    <a name="__RefHeading__2433_1239996969"></a>
    2.3.2 调用地址
</h3>

>><p>
    POST http://msg.umeng.com/api/cancel
</p>

><h3>
    <a name="_Toc373181474"></a>
    <a name="__RefHeading__2435_1239996969"></a>
    2.3.3 调用参数
</h3>

>><table width="595" cellpadding="7" cellspacing="0">
    <colgroup>
        <col width="115"/>
        <col width="57"/>
        <col width="382"/>
    </colgroup>
    <tbody>
        <tr valign="TOP">
            <td width="115">
                <p>
                    <strong>参数</strong>
                </p>
            </td>
            <td width="57">
                <p>
                    <strong>选择项</strong>
                </p>
            </td>
            <td width="382">
                <p>
                    <strong>说明</strong>
                </p>
            </td>
        </tr>
        <tr valign="TOP">
            <td width="115">
                <p>
                    appkey
                </p>
            </td>
            <td width="57">
                <p>
                    必选
                </p>
            </td>
            <td width="382">
                <p>
                    应用唯一标识
                </p>
            </td>
        </tr>
        <tr valign="TOP">
                    <td width="122">
                        <p>
                            validation_token
                        </p>
                    </td>
                    <td width="44">
                        <p>
                            必选
                        </p>
                    </td>
                    <td colspan="6" width="387">
                        <p>
                            appkey, app_master_secret和timestamp的MD5的sum, 其中app_master_secret请先全部转换成小写形式
                        </p>
                    </td>
                </tr>
                <tr valign="TOP">
                    <td width="122">
                        <p>
                            timestamp
                        </p>
                    </td>
                    <td width="44">
                        <p>
                            必选
                        </p>
                    </td>
                    <td colspan="6" width="387">
                        <p>
                            上面生成MD5时的时间戳（请用String类型）
                        </p>
                    </td>
                </tr>
        <tr valign="TOP">
            <td width="115">
                <p>
                    task_id
                </p>
            </td>
            <td width="57">
                <p>
                    必选
                </p>
            </td>
            <td width="382">
                <p>
                    消息发送时，从返回消息中获取的task_id
                </p>
            </td>
        </tr>
    </tbody>
</table>

><h3>
    <a name="_Toc373181475"></a>
    <a name="__RefHeading__2437_1239996969"></a>
    2.3.4 调用返回
</h3>

>><p>
    返回的Json格式信息包括如下内容:
</p>
<p>
    SUCCESS：指明成功取消的task_id; FAIL：指明失败的task_id和失败的原因。
</p>

<h1>
    <a name="_Toc373181476"></a>
    <a name="__RefHeading__2439_1239996969"></a>
    附录
</h1>
<h2>
    <a name="_Toc373181477"></a>
    <a name="__RefHeading__2441_1239996969"></a>
    附录A unicast消息发送示例
</h2>
<p>
    <strong>请求消息</strong>
    POST http://msg.umeng.com/api/send
</p>
<p>
    发送通知示例:
</p>
<pre><code>{
              "appkey":"你的appkey",
              "validation_token":"appkey, app_master_secret和timestamp的MD5的sum",
              "timestamp":"你的timestamp",
              "type":"unicast",
              "device_tokens":"你的设备标识",
              "payload":{
                    "display_type": "notification",
                    "body":{
                                  "ticker":"测试提示文字",
                                  "title":"测试标题",
                                  "text":"测试文字描述"
                                }
                        },
              "policy":{
                        "expire_time":"2013-10-30 12:00:00"
                     },
              "description":"测试单播"
           }
                </code></pre>
<p>
    发送消息示例:
</p>
<pre><code>{
              "appkey":"你的appkey",
              "validation_token":"appkey, app_master_secret和timestamp的MD5的sum",
              "timestamp":"你的timestamp",
              "type":"unicast",
              "device_tokens":"你的设备标识",
              "payload":{
                    "display_type": "message",
                    "body":{
                                  "custom":"自定义custom"
                        }    
                        },
              "policy":{
                        "expire_time":"2013-10-30 12:00:00"
                     },
              "description":"测试单播"
           }
                </code></pre>

<p>
    <strong>响应消息</strong>
</p>
<p>
    成功: 如{"ret":"SUCCESS","data":{"msg_id":"um0631382593995207"}}
</p>
<p>
    失败: 如{"ret":"FAIL","data":["ER_PARAM_EXPIRED::失效时间格式错误"]}
</p>
<h2>
    <a name="_Toc373181478"></a>
    <a name="__RefHeading__2443_1239996969"></a>
    附录B listcast消息发送示例
</h2>
<p>
    <strong>请求消息</strong>
    POST http://msg.umeng.com/api/send
</p>
<p>
    消息体参数:
</p>
<pre><code>{
              "appkey":"你的appkey",
              "validation_token":"appkey, app_master_secret和timestamp的MD5的sum",
              "timestamp":"你的timestamp",
              "type":"listcast",
              "device_tokens":"device1标识,device1标识,…",
              "payload":{
                         "display_type": "notification",
                         "body":{
                                  "ticker":"测试提示文字",
                                  "title":"测试标题",
                                  "text":"测试文字描述"
                                }
                        },
              "policy":{
                        "expire_time":"2013-10-30 12:00:00"
                     },
              "description":"测试列播"
           }
                </code></pre>
<p>
    <em>说明</em>
    <em>: </em>
    <em>多个</em>
    <em>device</em>
    <em>标识之间用”</em>
    <em>,”</em>
    <em>号分隔</em>
</p>
<p>
    <strong>响应消息</strong>
</p>
<p>
    成功: 如{"ret":"SUCCESS","data":{"msg_id":["um3491382593995210", "um0211382593995211"]}}
</p>
<p>
    失败: 如{"ret":"FAIL","data":"Invalid app key or secret"}
</p>
<h2>
    <a name="_Toc373181479"></a>
    <a name="__RefHeading__2445_1239996969"></a>
    附录C broadcast消息发送示例
</h2>
<p>
    <strong>请求消息</strong>
    POST http://msg.umeng.com/api/send
</p>
<p>
    消息体参数:
</p>
<pre><code>{
              "appkey":"你的appkey",
              "validation_token":"appkey, app_master_secret和timestamp的MD5的sum",
              "timestamp":"你的timestamp",
              "type":"broadcast",
              "payload":{
                         "display_type": "notification",
                         "body":{
                                  "ticker":"测试提示文字",
                                  "title":"测试标题",
                                  "text":"测试文字描述"
                                }
                        },
              "policy":{
              "expire_time":"2013-10-30 12:00:00"
                     },
              "feedback":"你的回调URL接口",
              "description":"测试广播"
           }
                </code></pre>
<p>
    <strong>响应消息</strong>
</p>
<p>
    成功: 如{"ret":"SUCCESS","data":{"task_id":"um1231382593995318"}}
</p>
<p>
    失败: 如{"ret":"FAIL","data":["ER_PARAM_START_TIME::开始时间格式错误"]}
</p>
<h2>
    <a name="_Toc373181480"></a>
    <a name="__RefHeading__2447_1239996969"></a>
    附录D groupcast消息发送示例
</h2>
<p>
    <strong>请求消息</strong>
    POST http://msg.umeng.com/api/send
</p>
<p>
    消息体参数:
</p>
<pre><code>{
            "appkey":"你的appkey",
           	"validation_token":"appkey, app_master_secret和timestamp的MD5的sum",
            "timestamp":"你的timestamp",
           	"type":"groupcast",
           	"filter":{
           		"where": {
           			"and": [{ "not": {"app_version": "v1.0"} } ]
           		}
               },
           	"payload":{
                         "display_type": "notification",
                         "body":{
                                  "ticker":"测试提示文字",
                                  "title":"测试标题",
                                  "text":"测试文字描述"
                                }
                        },
           	"policy":{
                "expire_time":"2013-10-30 12:00:00"
            },
           	"feedback":"你的回调URL地址",
           	"description":"测试组播"
           }
                </code></pre>
<p>
    说明: 其中的filter内容表示向当前所有app_version不是v1.0的应用客户端发送消息，其内容的使用语法示例请参考附录E。
</p>
<p>
    <strong>响应消息</strong>
</p>
<p>
    成功: 如{"ret":"SUCCESS","data":{"task_id":"us1821382505885729"}}
</p>
<p>
    失败: 如{"ret":"FAIL","data":"JSON format error"}
</p>
<h2>
    <a name="_Toc373181481"></a>
    <a name="__RefHeading__2449_1239996969"></a>
    附录E customizedcast消息发送示例
</h2>
<p>
    <strong>请求消息</strong>
    POST http://msg.umeng.com/api/send
</p>
<p>
    消息体参数:
</p>
<pre><code>{
              "appkey":"你的appkey",
              "validation_token":"appkey, app_master_secret和timestamp的MD5的sum",
              "timestamp":"你的timestamp",
              "type":"customizedcast",
              "alias":"你们用户的alias，多个用英文逗号隔开",
              "file_id":"存放alias的文件id，该id通过文件上传接口获得",
              "payload":{
                         "display_type": "notification",
                         "body":{
                                  "ticker":"测试提示文字",
                                  "title":"测试标题",
                                  "text":"测试文字描述"
                                }
                        },
              "policy":{
                      "expire_time":"2013-10-30 12:00:00"
                     },
              "description":"测试customizedcast"
           }
                </code></pre>
<p>
    <strong>响应消息</strong>
</p>
<p>
    成功: 
</p>
<p>
    当file_id为空，alias不空时，如{"ret":"SUCCESS","data":{"msg_id":"um1231382593995318"}}
</p>
<p>
    当file_id不空时，如{"ret":"SUCCESS","data":{"task_id":"um1231382593995318"}}
</p>
<p>
    失败: 如{"ret":"FAIL","data":["ER_PARAM_START_TIME::开始时间格式错误"]}
</p>
<h2>
    <a name="_Toc373181482"></a>
    <a name="__RefHeading__2451_1239996969"></a>
    附录F 过滤条件示例
</h2>
<p>
    注, 目前开放的筛选字段有:
    "app_version"(应用版本), "channel"(分发渠道), "device_model"(设备型号), "province"(地域)，"tags"(用户标签)
</p>
<p>
    query expression的最顶层只能是 and 或者 or
</p>
<p>
    (1). and
</p>
<p>
    已注册的(registered_user)<b>并且</b>为男性(male)的用户群
</p>
<pre><code>"where": {
             "and": [
                { "tag": "registered_user" },
                { "tag": "male" }
             ]
           }
                </code></pre>
<p>
    (2). or
</p>
<p>
    已注册(registered_user)用户<b>或者</b>男性(male)用户群
</p>
<pre><code>"where": {
             "or": [
                { "tag": "registered_user" },
                { "tag": "male" }
             ]
           }
                </code></pre>
<p>
    (3). not
</p>
<p>
    未注册的(registered_user)的用户群
</p>
<pre><code>"where": {
             "and": [
               {
                 "not": {
                   "tag": "registered_user"
                 }
               }
             ]
           }
                </code></pre>
<p>
    (4). and, or, not的组合
</p>
<p>
    发送给"非注册或者男性(male)"并且"玩过5次以上的用户(played_more_than_5_times)"
</p>
<pre><code>"where": {
             "and": [
               {
                 "or": [
                   {
                     "not": {
                       "tag": "registered_user"
                     }
                   },
                   {
                     "tag": "male"
                   }
                 ]
               },
               {
                 "tag": "played_more_than_5_times"
               }
             ]
           }
                </code></pre>
<h2>
    <a name="_Toc373181483"></a>
    <a name="__RefHeading__2453_1239996969"></a>
    附录G MD5生成代码示例
</h2>

python
----------------------

```python
>>> import hashlib
>>> appkey = '50e26c315270156df0000031'
>>> app_master_secret = 'b3a09842d2c86177aa8268ee64f14f7e'
>>> ts = '1385321933302'
>>> my_str = appkey + app_master_secret + ts
>>> my_str
'50e26c315270156df0000031b3a09842d2c86177aa8268ee64f14f7e1385321933302'
>>> validation_token = hashlib.md5(my_str).hexdigest()
>>> validation_token
'a159e9f76ede3f18bf0a59495ad8bf97'

```
java
-------------------------------

```java

import org.apache.commons.codec.digest.DigestUtils;
class md {
    public static void main(String args[]) {
        String appkey = "50e26c315270156df0000031";
        String app_master_secret = "b3a09842d2c86177aa8268ee64f14f7e";
        String ts = "1385321933302";
        String my_str = appkey + app_master_secret + ts;
        String my_str = DigestUtils.md5Hex(appkey + msg.app_master_secret.getOrElse("").toLowerCase + timestamp)
        System.out.println(my_str);
    }
}
```
ruby
-------------

```ruby

irb(main):002:0> require 'digest/md5'
=> true
irb(main):003:0> appkey = '50e26c315270156df0000031'
=> "50e26c315270156df0000031"
irb(main):004:0> app_master_secret = 'b3a09842d2c86177aa8268ee64f14f7e'
=> "b3a09842d2c86177aa8268ee64f14f7e"
irb(main):005:0> ts = '1385321933302'
=> "1385321933302"
irb(main):006:0> my_str = appkey + app_master_secret + ts
=> "50e26c315270156df0000031b3a09842d2c86177aa8268ee64f14f7e1385321933302"
irb(main):007:0> validation_token = Digest::MD5.hexdigest(my_str)
=> "a159e9f76ede3f18bf0a59495ad8bf97"
     

```
<!--
scala
----------

```scala
scala> import java.security.MessageDigest
import java.security.MessageDigest
scala> val appkey = "50e26c315270156df0000031"
appkey: String = 50e26c315270156df0000031
scala> val app_master_secret = "b3a09842d2c86177aa8268ee64f14f7e"
app_master_secret: String = b3a09842d2c86177aa8268ee64f14f7e
scala> val ts = "1385321933302"
ts: String = 1385321933302
scala> val my_str = appkey + app_master_secret + ts
my_str: String = 50e26c315270156df0000031b3a09842d2c86177aa8268ee64f14f7e1385321933302
scala> def md5SumString(bytes : Array[Byte]) : String = {
     |   val md5 = MessageDigest.getInstance("MD5")
     |   md5.reset()
     |   md5.update(bytes)
     | 
     |   md5.digest().map(0xFF & _).map { "%02x".format(_) }.foldLeft(""){_ + _}
     | }
md5SumString: (bytes: Array[Byte])String
scala> md5SumString(my_str.getBytes)
res1: String = a159e9f76ede3f18bf0a59495ad8bf97

```

-->
<p>
</p>

<div id="sdfootnote1">
    <p align="LEFT">
        <a name="sdfootnote1sym" href="#sdfootnote1anc">1</a>
        <sup></sup>
        http://message.umeng.com
    </p>
</div>
<div id="sdfootnote2">
    <p align="LEFT">
        <a name="sdfootnote2sym" href="#sdfootnote2anc">2</a>
        <sup></sup>
        生成MD5前请将app_master_secret全部转换成小写
    </p>
</div>
  <div id="sdfootnote3">
      <p align="LEFT">
          <a name="sdfootnote3sym" href="#sdfootnote3anc">3</a>
          <sup></sup>
          个数不要超过50个
      </p>
  </div>

**如有任何问题请联系：support@umeng.com**

**如有任何问题请联系：support@umeng.com**


