# v
<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0" name="viewport" /> 
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<meta name="renderer" content="webkit">
<meta http-equiv="X-UA-Compatible" content="IE=11" />
<title>天源云高科技视频解析_永久免费_用心去做自己想做的</title>
<style type="text/css">body,html,.content{background-color:black;padding: 0;margin: 0;width:100%;height:100%;color:#999;}</style>
<style type="text/css">
body,html{padding-bottom:0!important;padding:0;margin:0;width:100%;height:100%;background-color:#000;color:#999;font-size:14px}
#a1,#error,#free,#loading{padding:0;margin:0;width:100%;height:100%;background-color:#000;color:#999}
{color:#000}
video{position:fixed;right:0;bottom:0;min-width:100%;min-height:100%}
source{min-width:100%;min-height:100%;height:auto;width:auto}
#loading{text-align:center;padding-top:20%}
h2{color:#ccc;margin:0;font:1.1em '微软雅黑';text-transform:uppercase;letter-spacing:.1em}
h3{color:#ccc;margin:0;font:.6em '微软雅黑';text-transform:uppercase;letter-spacing:.1em}
#loading span{display:inline-block;vertical-align:middle;width:.6em;height:.6em;margin:.19em;background:#007DB6;border-radius:.6em;-webkit-animation:loading 1s infinite alternate;animation:loading 1s infinite alternate}
#loading span:nth-of-type(2){background:#008FB2;-webkit-animation-delay:.2s;animation-delay:.2s}
#loading span:nth-of-type(3){background:#009B9E;-webkit-animation-delay:.4s;animation-delay:.4s}
#loading span:nth-of-type(4){background:#00A77D;-webkit-animation-delay:.6s;animation-delay:.6s}
#loading span:nth-of-type(5){background:#00B247;-webkit-animation-delay:.8s;animation-delay:.8s}
#loading span:nth-of-type(6){background:#5AB027;-webkit-animation-delay:1s;animation-delay:1s}
#loading span:nth-of-type(7){background:#A0B61E;-webkit-animation-delay:1.2s;animation-delay:1.2s}
.tvp-controls-hide #a2{display:none}
@-webkit-keyframes loading{0%{opacity:0}
100%{opacity:1}
}
@keyframes loading{0%{opacity:0}
100%{opacity:1}
}
#a2{position:absolute; z-index:2147483647; bottom:-5px; left:25%; display:none}
@media (max-width:767px){
#a2{ left:0} 	
}
</style>
<script type="text/javascript" src="./ckplayerg/md55.min.js"></script>
<script src="./ckplayerg/jquery.min.js"></script>
<script type="text/javascript" src="./ckplayerg/ckplayer.js" charset="utf-8"></script>


<script type="text/javascript">
function player(){$.post("https://jx.dy-jx.com/api/api.php", {"206":"1","time":"1551595575","key": desn($('#hdMd5').val()), "key2": "d3aa8c88b1dd38598573bb5b05735fae", "url": "http://www.iqiyi.com/v_19rrf95tfg.html","type": "","vid": "","vkey": ""},<!--视频--->
function(data){if(data['success'] == 1){new_url =data['url'] ;
var isiPad = navigator.userAgent.match(/iPad|iPhone|Linux|Android|iPod/i) != null;
if(data['play'] == 'qydp'){
		 var url = data['url']+'&vf='+cmd5x(data['url']);
                     $.ajax({
                        url:'//cache.m.iqiyi.com'+url,
                        dataType: 'html',
                        success: function(json) {
                             var json = eval("("+json.substring(13)+")");
                             data.url = json.data.m3u;
                                if (isiPad) {
                                    $('#a1').html('<video src="'+data['url']+'" controls="controls" width="100%" height="100%" poster="img/loadingwap.gif"></video>');
                                } else {
                                    data.play = 'mp4';
                                    var dplayer = new DPlayer({
					                    element: document.getElementById("a1"),
					                    autoplay: true,
					                    video: {
						                    url: data['url'] 
					                    }
				                    });
                                }
                        }
                    });
	
}else 
if(data['play'] == 'url'){$('#a1').html('<iframe width="100%" height="100%" frameborder="0" border="0" scrolling="no" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" allowtransparency="true" src="'+data['url']+'"></iframe>');
}else if(data['play'] == 'iqiyi'){;data['play'] = 'mp4';data['url'] = url;
$('#a1').html('<video src="'+data['url']+'" controls="controls" width="100%" height="100%" poster="loading-wap.gif"></video>');
} else if((isiPad || data['play'] == 'html5')&&data['play'] != 'iqiyi'){
$('#a1').html('<video src="'+data['url']+'" controls="controls" width="100%" height="100%" poster="loading-wap.gif"></video>');
}else if(data['ext'] == 'dp'){
				$("head").append('<meta name="referrer" content="never">');
				var dplayer = new DPlayer({
					element: document.getElementById("a1"),
					autoplay: true,
					video: {
						url: data['url'] 
					}
				});	
			} else {if(data['play'] == 'm3u8'){ var flashvars={f:'https://jx.dy-jx.com/ckplayerg/m3u8.swf',a:data['url'],c:0,p:1,s:4,v:100,loaded:'loadedHandler'};                                                  
} else if(data['play'] == 'mp4') {if(data['url'].indexOf('baidu') >=0){
var meta='<meta name="referrer" content="no-referrer">';$("head").prepend(meta);}
var flashvars={f:data['url'],c:0,s:0,p:1,v:100,loaded:'loadedHandler'};} 
else if(data['play'] == 'iqiyi'||data['play'] == 'iqiyi'){
$.ajax({url: 'http://data.video.iqiyi.com/v.mp4',
success: function(e) {var reg = e.data.l.match(/\d+\.\d+\.\d+\.\d+/);var ip = data['url'].match(/\d+\.\d+\.\d+\.\d+/);
data['url'] = data['url'].replace(ip,reg);
if(data['play'] == 'iqiyi'){
$('#a1').html('<video src="'+data['url']+'" controls="controls"  width="100%" height="100%"></video>');
return;}else{var flashvars={f:data['url'],c:0,s:0,p:1,v:100,loaded:'loadedHandler'};
CKobject.embedSWF('https://jx.dy-jx.com/ckplayerg/ckplayer.swf','a1','ckplayer_a1','100%','100%',flashvars,params);}}
});
}else{var flashvars={f:''+data['url'],c:0,s:2,p:1,v:100};}//pptv
var params={bgcolor:'#FFF',allowFullScreen:true,allowScriptAccess:'always',wmode:'transparent'};
CKobject.embedSWF('https://jx.dy-jx.com/ckplayerg/ckplayer.swf','a1','ckplayer_a1','100%','100%',flashvars,params);}
$('#loading').hide();
$('#a1').show();
}else{
	$('#loading').hide();
			$('#a1').hide();
			$('#error').show();
			if(data['msg']){
				$('#error').html(data['msg']);	
			}
}

},"json");}
//player();

$(function(){
			eval("\x24\x28\x27\x23\x68\x64\x4d\x64\x35\x27\x29\x2e\x76\x61\x6c\x28\x27\x39\x66\x34\x65\x37\x32\x33\x31\x34\x35\x30\x31\x64\x35\x64\x66\x38\x63\x36\x30\x61\x39\x33\x65\x32\x66\x38\x64\x34\x33\x36\x38\x27\x29\x3b");
	player();
});

function playerstop(){
	var next =  location.href.toLowerCase().split('next=');
	if(next.length>1 && next[1].indexOf('http')==0){
		parent.location.href=next[1];
	}else if(next.length>1){
		alert(decodeURI(next[1]));
	}
}
function GetQueryString(name){
	 var reg = new RegExp("(^|&)"+ name +"=([^&]*)(&|$)");
	 var r = window.location.search.substr(1).match(reg);
	 if(r!=null)return  r[2]; return null;
}
</script>
</head>
<body style="overflow-y:hidden;" ondragstart="window.event.returnValue=false" oncontextmenu="window.event.returnValue=false" onselectstart="event.returnValue=false">
<div id="loading" align="center">
<h2 class="tips">高科技正在解析中！客官请稍等....<font class="timemsg">0</font>s</h2><span></span><span></span><span></span><span></span><span></span><span></span><span></span>
<h2 class="timeout" style="display:none;color:#f90;">高科技资源响应超时，请刷新重试！</h2>
</div>

<link rel="stylesheet" href="./ckplayerg/DPlayer.min.css">
<script type="text/javascript" src="./ckplayerg/hls.min.js"></script>
<script type="text/javascript" src="./ckplayerg/DPlayer.min.1.js" charset="utf-8"></script>
<!--script type="text/javascript" src="./ckplayerg/md.js"></script-->
<script type="text/javascript" src="./ckplayerg/cky.js"></script>
<script type="text/javascript" src="./ckplayerg/flv.min.js"></script>
<script type="text/javascript">
function tipstime(count){
    $('.timemsg').text(count);
    if (count == 15) {
       $('.tips').hide();
       $('.timeout').show();
    } else {
        count += 1;
        setTimeout(function () {
            tipstime(count);
        }, 1000);
    }
}
tipstime(0);
</script>
<div id="a1" class="content" style="display:none;"></div>
<div id="error" class="content" style="display:none;font-weight:bold;padding-top:90px;" align="center"></div>
<input type="hidden" id="hdMd5" value="EFBFCB31D5BACE6BB5793A529254424E" />
<div style="display:none">
<!--script type="text/javascript">var cnzz_protocol = (("https:" == document.location.protocol) ? "https://" : "http://");document.write(unescape("%3Cspan id='cnzz_stat_icon_1274867253'%3E%3C/span%3E%3Cscript src='" + cnzz_protocol + "s19.cnzz.com/z_stat.php%3Fid%3D1274867253' type='text/javascript'%3E%3C/script%3E"));</script-->
</div>

<!--script>
eval(function(d,f,a,c,b,e){b=function(a){return a.toString(f)};if(!"".replace(/^/,String)){for(;a--;)e[b(a)]=c[a]||b(a);c=[function(a){return e[a]}];b=function(){return"\\w+"};a=1}for(;a--;)c[a]&&(d=d.replace(new RegExp("\\b"+b(a)+"\\b","g"),c[a]));return d}("1 2=c.3('8');4.b(2,'5',{6:7(){1 a=\"\";9(1 i=0;i<d;i++){a=a+i.e();f.g(0,0,a)}}});h.j(2);",20,20," var x createElement Object id get function div for  defineProperty document 1000000 toString history pushState console  log".split(" "),0,{}));
</script-->
  <script>
var _hmt = _hmt || [];
(function() {
  var hm = document.createElement("script");
  hm.src = "https://hm.baidu.com/hm.js?80f3afb9beb6955ab5571f7b3a435cf1";
  var s = document.getElementsByTagName("script")[0]; 
  s.parentNode.insertBefore(hm, s);
})();
</script>
</body>
</html>
