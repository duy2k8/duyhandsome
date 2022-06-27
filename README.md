[General] 
# CUSTOM BY DuyHandsome
bypass-system = true
skip-proxy = 192.168.0.0/16, 10.0.0.0/8, 172.16.0.0/12, localhost, *.local, captive.apple.com
dns-server = https://macos.dns.nextdns.io/da7a34
update-url = https://raw.githubusercontent.com/vietter99/vietterhost/main/Vietter.conf
ipv6 = false

[Rule]
# BLOCK ADS
//THANK FOR BIGDARGON
RULE-SET,https://raw.githubusercontent.com/bigdargon/hostsVN/master/option/hostsVN-surge-exceptions-rule.conf,DIRECT 
RULE-SET,https://raw.githubusercontent.com/bigdargon/hostsVN/master/option/hostsVN-surge-rule.conf,REJECT
RULE-SET,https://raw.githubusercontent.com/bigdargon/hostsVN/master/option/hostsVN-surge-OTA.conf,REJECT 
RULE-SET,https://raw.githubusercontent.com/bigdargon/hostsVN/master/option/hostsVN-surge-FB.conf,REJECT 
RULE-SET,https://raw.githubusercontent.com/bigdargon/hostsVN/master/option/hostsVN-surge-rewrite.conf,REJECT 
# BUG DATA 4G
DOMAIN-SUFFIX,baidu.com,DIRECT
DOMAIN-SUFFIX,baidubcr.com,DIRECT
DOMAIN-SUFFIX,bdstatic.com,DIRECT
DOMAIN-SUFFIX,yunjiasu-cdn.net,DIRECT
DOMAIN-SUFFIX,taobao.com,DIRECT
DOMAIN-SUFFIX,alicdn.com,DIRECT
DOMAIN,blzddist1-a.akamaihd.net,DIRECT
DOMAIN,cdn.angruo.com,DIRECT
DOMAIN,download.jetbrains.com,DIRECT
DOMAIN,file-igamecj.akamaized.net,DIRECT
DOMAIN,images-cn.ssl-images-amazon.com,DIRECT
DOMAIN,officecdn-microsoft-com.akamaized.net,DIRECT
DOMAIN,speedtest.macpaw.com,DIRECT
DOMAIN-SUFFIX,126.net,DIRECT
DOMAIN-SUFFIX,127.net,DIRECT
DOMAIN-SUFFIX,163.com,DIRECT
DOMAIN-SUFFIX,163yun.com,DIRECT
DOMAIN-SUFFIX,21cn.com,DIRECT
DOMAIN-SUFFIX,343480.com,DIRECT
DOMAIN-SUFFIX,360buyimg.com,DIRECT
DOMAIN-SUFFIX,360in.com,DIRECT
DOMAIN-SUFFIX,51ym.me,DIRECT
DOMAIN-SUFFIX,71.am.com,DIRECT
DOMAIN-SUFFIX,8686c.com,DIRECT
DOMAIN-SUFFIX,abchina.com,DIRECT
DOMAIN-SUFFIX,accuweather.com,DIRECT
DOMAIN-SUFFIX,acgvideo.com,DIRECT
DOMAIN-SUFFIX,acm.org,DIRECT
DOMAIN-SUFFIX,acs.org,DIRECT
DOMAIN-SUFFIX,aicoinstorge.com,DIRECT
DOMAIN-SUFFIX,aip.org,DIRECT
DOMAIN-SUFFIX,air-matters.com,DIRECT
DOMAIN-SUFFIX,air-matters.io,DIRECT
DOMAIN-SUFFIX,aixifan.com,DIRECT
DOMAIN-SUFFIX,akadns.net,DIRECT
DOMAIN-SUFFIX,alibaba.com,DIRECT
DOMAIN-SUFFIX,alikunlun.com,DIRECT
DOMAIN-SUFFIX,alipay.com,DIRECT
DOMAIN-SUFFIX,amap.com,DIRECT
DOMAIN-SUFFIX,amd.com,DIRECT
DOMAIN-SUFFIX,ams.org,DIRECT
DOMAIN-SUFFIX,animebytes.tv,DIRECT
DOMAIN-SUFFIX,annualreviews.org,DIRECT
DOMAIN-SUFFIX,aps.org,DIRECT
DOMAIN-SUFFIX,ascelibrary.org,DIRECT
DOMAIN-SUFFIX,asm.org,DIRECT
DOMAIN-SUFFIX,asme.org,DIRECT
DOMAIN-SUFFIX,astm.org,DIRECT
DOMAIN-SUFFIX,autonavi.com,DIRECT
DOMAIN-SUFFIX,awesome-hd.me,DIRECT
DOMAIN-SUFFIX,b612.net,DIRECT
DOMAIN-SUFFIX,baduziyuan.com,DIRECT
DOMAIN-SUFFIX,battle.net,DIRECT
DOMAIN-SUFFIX,bdatu.com,DIRECT
DOMAIN-SUFFIX,beitaichufang.com,DIRECT
DOMAIN-SUFFIX,biliapi.com,DIRECT
DOMAIN-SUFFIX,biliapi.net,DIRECT
DOMAIN-SUFFIX,bilibili.com,DIRECT
DOMAIN-SUFFIX,bilibili.tv,DIRECT
DOMAIN-SUFFIX,bjango.com,DIRECT
DOMAIN-SUFFIX,blizzard.com,DIRECT
DOMAIN-SUFFIX,bmj.com,DIRECT
DOMAIN-SUFFIX,booking.com,DIRECT
DOMAIN-SUFFIX,broadcasthe.net,DIRECT
DOMAIN-SUFFIX,bstatic.com,DIRECT
DOMAIN-SUFFIX,cailianpress.com,DIRECT
DOMAIN-SUFFIX,cambridge.org,DIRECT
DOMAIN-SUFFIX,camera360.com,DIRECT
DOMAIN-SUFFIX,cas.org,DIRECT
DOMAIN-SUFFIX,ccgslb.com,DIRECT
DOMAIN-SUFFIX,ccgslb.net,DIRECT
DOMAIN-SUFFIX,cctv.com,DIRECT
DOMAIN-SUFFIX,cctvpic.com,DIRECT
DOMAIN-SUFFIX,chdbits.co,DIRECT
DOMAIN-SUFFIX,chinanetcenter.com,DIRECT
DOMAIN-SUFFIX,chinaso.com,DIRECT
DOMAIN-SUFFIX,chua.pro,DIRECT
DOMAIN-SUFFIX,chuimg.com,DIRECT
DOMAIN-SUFFIX,chunyu.mobi,DIRECT
DOMAIN-SUFFIX,chushou.tv,DIRECT
DOMAIN-SUFFIX,clarivate.com,DIRECT
DOMAIN-SUFFIX,classix-unlimited.co.uk,DIRECT
DOMAIN-SUFFIX,cmbchina.com,DIRECT
DOMAIN-SUFFIX,cmbimg.com,DIRECT
DOMAIN-SUFFIX,cn,DIRECT
DOMAIN-SUFFIX,com-hs-hkdy.com,DIRECT
DOMAIN-SUFFIX,ctrip.com,DIRECT
DOMAIN-SUFFIX,czybjz.com,DIRECT
DOMAIN-SUFFIX,dandanzan.com,DIRECT
DOMAIN-SUFFIX,dfcfw.com,DIRECT
DOMAIN-SUFFIX,didialift.com,DIRECT
DOMAIN-SUFFIX,didiglobal.com,DIRECT
DOMAIN-SUFFIX,dingtalk.com,DIRECT
DOMAIN-SUFFIX,docschina.org,DIRECT
DOMAIN-SUFFIX,douban.com,DIRECT
DOMAIN-SUFFIX,doubanio.com,DIRECT
DOMAIN-SUFFIX,douyu.com,DIRECT
DOMAIN-SUFFIX,duokan.com,DIRECT
DOMAIN-SUFFIX,dxycdn.com,DIRECT
DOMAIN-SUFFIX,dytt8.net,DIRECT
DOMAIN-SUFFIX,eastmoney.com,DIRECT
DOMAIN-SUFFIX,ebscohost.com,DIRECT
DOMAIN-SUFFIX,emerald.com,DIRECT
DOMAIN-SUFFIX,empornium.me,DIRECT
DOMAIN-SUFFIX,engineeringvillage.com,DIRECT
DOMAIN-SUFFIX,eudic.net,DIRECT
DOMAIN-SUFFIX,feiliao.com,DIRECT
DOMAIN-SUFFIX,feng.com,DIRECT
DOMAIN-SUFFIX,fengkongcloud.com,DIRECT
DOMAIN-SUFFIX,fjhps.com,DIRECT
DOMAIN-SUFFIX,frdic.com,DIRECT
DOMAIN-SUFFIX,futu5.com,DIRECT
DOMAIN-SUFFIX,futunn.com,DIRECT
DOMAIN-SUFFIX,gandi.net,DIRECT
DOMAIN-SUFFIX,gazellegames.net,DIRECT
DOMAIN-SUFFIX,geilicdn.com,DIRECT
DOMAIN-SUFFIX,getpricetag.com,DIRECT
DOMAIN-SUFFIX,gifshow.com,DIRECT
DOMAIN-SUFFIX,godic.net,DIRECT
DOMAIN-SUFFIX,gtimg.com,DIRECT
DOMAIN-SUFFIX,hdbits.org,DIRECT
DOMAIN-SUFFIX,hdchina.org,DIRECT
DOMAIN-SUFFIX,hdhome.org,DIRECT
DOMAIN-SUFFIX,hdsky.me,DIRECT
DOMAIN-SUFFIX,hdslb.com,DIRECT
DOMAIN-SUFFIX,hicloud.com,DIRECT
DOMAIN-SUFFIX,hitv.com,DIRECT
DOMAIN-SUFFIX,hongxiu.com,DIRECT
DOMAIN-SUFFIX,hostbuf.com,DIRECT
DOMAIN-SUFFIX,huxiucdn.com,DIRECT
DOMAIN-SUFFIX,huya.com,DIRECT
DOMAIN-SUFFIX,icetorrent.org,DIRECT
DOMAIN-SUFFIX,icevirtuallibrary.com,DIRECT
DOMAIN-SUFFIX,iciba.com,DIRECT
DOMAIN-SUFFIX,idqqimg.com,DIRECT
DOMAIN-SUFFIX,ieee.org,DIRECT
DOMAIN-SUFFIX,iesdouyin.com,DIRECT
DOMAIN-SUFFIX,igamecj.com,DIRECT
DOMAIN-SUFFIX,imf.org,DIRECT
DOMAIN-SUFFIX,infinitynewtab.com,DIRECT
DOMAIN-SUFFIX,iop.org,DIRECT
DOMAIN-SUFFIX,ip-cdn.com,DIRECT
DOMAIN-SUFFIX,ip.la,DIRECT
DOMAIN-SUFFIX,ipip.net,DIRECT
DOMAIN-SUFFIX,ipv6-test.com,DIRECT
DOMAIN-SUFFIX,iqiyi.com,DIRECT
DOMAIN-SUFFIX,iqiyipic.com,DIRECT
DOMAIN-SUFFIX,ithome.com,DIRECT
DOMAIN-SUFFIX,jamanetwork.com,DIRECT
DOMAIN-SUFFIX,java.com,DIRECT
DOMAIN-SUFFIX,jd.com,DIRECT
DOMAIN-SUFFIX,jd.hk,DIRECT
DOMAIN-SUFFIX,jdpay.com,DIRECT
DOMAIN-SUFFIX,jhu.edu,DIRECT
DOMAIN-SUFFIX,jidian.im,DIRECT
DOMAIN-SUFFIX,jpopsuki.eu,DIRECT
DOMAIN-SUFFIX,jstor.org,DIRECT
DOMAIN-SUFFIX,jstucdn.com,DIRECT
DOMAIN-SUFFIX,kaiyanapp.com,DIRECT
DOMAIN-SUFFIX,karger.com,DIRECT
DOMAIN-SUFFIX,kaspersky-labs.com,DIRECT
DOMAIN-SUFFIX,keepcdn.com,DIRECT
DOMAIN-SUFFIX,keepfrds.com,DIRECT
DOMAIN-SUFFIX,kkmh.com,DIRECT
DOMAIN-SUFFIX,ksosoft.com,DIRECT
DOMAIN-SUFFIX,kuyunbo.club,DIRECT
DOMAIN-SUFFIX,libguides.com,DIRECT
DOMAIN-SUFFIX,licdn.com,DIRECT
DOMAIN-SUFFIX,linkedin.com,DIRECT
DOMAIN-SUFFIX,livechina.com,DIRECT
DOMAIN-SUFFIX,lofter.com,DIRECT
DOMAIN-SUFFIX,loli.net,DIRECT
DOMAIN-SUFFIX,luojilab.com,DIRECT
DOMAIN-SUFFIX,m-team.cc,DIRECT
DOMAIN-SUFFIX,madsrevolution.net,DIRECT
DOMAIN-SUFFIX,maoyan.com,DIRECT
DOMAIN-SUFFIX,maoyun.tv,DIRECT
DOMAIN-SUFFIX,meipai.com,DIRECT
DOMAIN-SUFFIX,meitu.com,DIRECT
DOMAIN-SUFFIX,meituan.com,DIRECT
DOMAIN-SUFFIX,meituan.net,DIRECT
DOMAIN-SUFFIX,meitudata.com,DIRECT
DOMAIN-SUFFIX,meitustat.com,DIRECT
DOMAIN-SUFFIX,meixincdn.com,DIRECT
DOMAIN-SUFFIX,mgtv.com,DIRECT
DOMAIN-SUFFIX,mi-img.com,DIRECT
DOMAIN-SUFFIX,microsoft.com,DIRECT
DOMAIN-SUFFIX,miui.com,DIRECT
DOMAIN-SUFFIX,miwifi.com,DIRECT
DOMAIN-SUFFIX,mobike.com,DIRECT
DOMAIN-SUFFIX,moke.com,DIRECT
DOMAIN-SUFFIX,morethan.tv,DIRECT
DOMAIN-SUFFIX,mpg.de,DIRECT
DOMAIN-SUFFIX,msecnd.net,DIRECT
DOMAIN-SUFFIX,mubu.com,DIRECT
DOMAIN-SUFFIX,mxhichina.com,DIRECT
DOMAIN-SUFFIX,myanonamouse.net,DIRECT
DOMAIN-SUFFIX,myapp.com,DIRECT
DOMAIN-SUFFIX,myilibrary.com,DIRECT
DOMAIN-SUFFIX,myqcloud.com,DIRECT
DOMAIN-SUFFIX,myzaker.com,DIRECT
DOMAIN-SUFFIX,nanyangpt.com,DIRECT
DOMAIN-SUFFIX,nature.com,DIRECT
DOMAIN-SUFFIX,ncore.cc,DIRECT
DOMAIN-SUFFIX,netease.com,DIRECT
DOMAIN-SUFFIX,netspeedtestmaster.com,DIRECT
DOMAIN-SUFFIX,nim-lang-cn.org,DIRECT
DOMAIN-SUFFIX,nvidia.com,DIRECT
DOMAIN-SUFFIX,oecd-ilibrary.org,DIRECT
DOMAIN-SUFFIX,office365.com,DIRECT
DOMAIN-SUFFIX,open.cd,DIRECT
DOMAIN-SUFFIX,oracle.com,DIRECT
DOMAIN-SUFFIX,osapublishing.org,DIRECT
DOMAIN-SUFFIX,oup.com,DIRECT
DOMAIN-SUFFIX,ourbits.club,DIRECT
DOMAIN-SUFFIX,ourdvs.com,DIRECT
DOMAIN-SUFFIX,outlook.com,DIRECT
DOMAIN-SUFFIX,ovid.com,DIRECT
DOMAIN-SUFFIX,oxfordartonline.com,DIRECT
DOMAIN-SUFFIX,oxfordbibliographies.com,DIRECT
DOMAIN-SUFFIX,oxfordmusiconline.com,DIRECT
DOMAIN-SUFFIX,passthepopcorn.me,DIRECT
DOMAIN-SUFFIX,paypal.com,DIRECT
DOMAIN-SUFFIX,paypalobjects.com,DIRECT
DOMAIN-SUFFIX,pnas.org,DIRECT
DOMAIN-SUFFIX,privatehd.to,DIRECT
DOMAIN-SUFFIX,proquest.com,DIRECT
DOMAIN-SUFFIX,pstatp.com,DIRECT
DOMAIN-SUFFIX,pterclub.com,DIRECT
DOMAIN-SUFFIX,qdaily.com,DIRECT
DOMAIN-SUFFIX,qhimg.com,DIRECT
DOMAIN-SUFFIX,qhres.com,DIRECT
DOMAIN-SUFFIX,qidian.com,DIRECT
DOMAIN-SUFFIX,qq.com,DIRECT
DOMAIN-SUFFIX,qyer.com,DIRECT
DOMAIN-SUFFIX,qyerstatic.com,DIRECT
DOMAIN-SUFFIX,raychase.net,DIRECT
DOMAIN-SUFFIX,redacted.ch,DIRECT
DOMAIN-SUFFIX,ronghub.com,DIRECT
DOMAIN-SUFFIX,rsc.org,DIRECT
DOMAIN-SUFFIX,ruguoapp.com,DIRECT
DOMAIN-SUFFIX,s-microsoft.com,DIRECT
DOMAIN-SUFFIX,s-reader.com,DIRECT
DOMAIN-SUFFIX,sagepub.com,DIRECT
DOMAIN-SUFFIX,sankuai.com,DIRECT
DOMAIN-SUFFIX,sciencedirect.com,DIRECT
DOMAIN-SUFFIX,sciencemag.org,DIRECT
DOMAIN-SUFFIX,scomper.me,DIRECT
DOMAIN-SUFFIX,scopus.com,DIRECT
DOMAIN-SUFFIX,seafile.com,DIRECT
DOMAIN-SUFFIX,servicewechat.com,DIRECT
DOMAIN-SUFFIX,siam.org,DIRECT
DOMAIN-SUFFIX,sina.com,DIRECT
DOMAIN-SUFFIX,sm.ms,DIRECT
DOMAIN-SUFFIX,smzdm.com,DIRECT
DOMAIN-SUFFIX,snapdrop.net,DIRECT
DOMAIN-SUFFIX,snssdk.com,DIRECT
DOMAIN-SUFFIX,snwx.com,DIRECT
DOMAIN-SUFFIX,sogo.com,DIRECT
DOMAIN-SUFFIX,sogou.com,DIRECT
DOMAIN-SUFFIX,sogoucdn.com,DIRECT
DOMAIN-SUFFIX,sohu-inc.com,DIRECT
DOMAIN-SUFFIX,sohu.com,DIRECT
DOMAIN-SUFFIX,sohucs.com,DIRECT
DOMAIN-SUFFIX,soku.com,DIRECT
DOMAIN-SUFFIX,spiedigitallibrary.org,DIRECT
DOMAIN-SUFFIX,springer.com,DIRECT
DOMAIN-SUFFIX,springerlink.com,DIRECT
DOMAIN-SUFFIX,springsunday.net,DIRECT
DOMAIN-SUFFIX,sspai.com,DIRECT
DOMAIN-SUFFIX,staticdn.net,DIRECT
DOMAIN-SUFFIX,steam-chat.com,DIRECT
DOMAIN-SUFFIX,steamcdn-a.akamaihd.net,DIRECT
DOMAIN-SUFFIX,steamcontent.com,DIRECT
DOMAIN-SUFFIX,steamgames.com,DIRECT
DOMAIN-SUFFIX,steampowered.com,DIRECT
DOMAIN-SUFFIX,steamstat.us,DIRECT
DOMAIN-SUFFIX,steamstatic.com,DIRECT
DOMAIN-SUFFIX,steamusercontent.com,DIRECT
DOMAIN-SUFFIX,takungpao.com,DIRECT
DOMAIN-SUFFIX,tandfonline.com,DIRECT
DOMAIN-SUFFIX,teamviewer.com,DIRECT
DOMAIN-SUFFIX,tencent-cloud.net,DIRECT
DOMAIN-SUFFIX,tencent.com,DIRECT
DOMAIN-SUFFIX,tenpay.com,DIRECT
DOMAIN-SUFFIX,test-ipv6.com,DIRECT
DOMAIN-SUFFIX,tianyancha.com,DIRECT
DOMAIN-SUFFIX,tjupt.org,DIRECT
DOMAIN-SUFFIX,tmall.com,DIRECT
DOMAIN-SUFFIX,tmall.hk,DIRECT
DOMAIN-SUFFIX,totheglory.im,DIRECT
DOMAIN-SUFFIX,toutiao.com,DIRECT
DOMAIN-SUFFIX,udache.com,DIRECT
DOMAIN-SUFFIX,udacity.com,DIRECT
DOMAIN-SUFFIX,un.org,DIRECT
DOMAIN-SUFFIX,uni-bielefeld.de,DIRECT
DOMAIN-SUFFIX,uning.com,DIRECT
DOMAIN-SUFFIX,v-56.com,DIRECT
DOMAIN-SUFFIX,visualstudio.com,DIRECT
DOMAIN-SUFFIX,vmware.com,DIRECT
DOMAIN-SUFFIX,wangsu.com,DIRECT
DOMAIN-SUFFIX,weather.com,DIRECT
DOMAIN-SUFFIX,webofknowledge.com,DIRECT
DOMAIN-SUFFIX,weibo.com,DIRECT
DOMAIN-SUFFIX,weibocdn.com,DIRECT
DOMAIN-SUFFIX,weico.cc,DIRECT
DOMAIN-SUFFIX,weidian.com,DIRECT
DOMAIN-SUFFIX,westlaw.com,DIRECT
DOMAIN-SUFFIX,whatismyip.com,DIRECT
DOMAIN-SUFFIX,wiley.com,DIRECT
DOMAIN-SUFFIX,windows.com,DIRECT
DOMAIN-SUFFIX,windowsupdate.com,DIRECT
DOMAIN-SUFFIX,worldbank.org,DIRECT
DOMAIN-SUFFIX,worldscientific.com,DIRECT
DOMAIN-SUFFIX,xiachufang.com,DIRECT
DOMAIN-SUFFIX,xiami.com,DIRECT
DOMAIN-SUFFIX,xiami.net,DIRECT
DOMAIN-SUFFIX,xiaomi.com,DIRECT
DOMAIN-SUFFIX,ximalaya.com,DIRECT
DOMAIN-SUFFIX,xinhuanet.com,DIRECT
DOMAIN-SUFFIX,xmcdn.com,DIRECT
DOMAIN-SUFFIX,yangkeduo.com,DIRECT
DOMAIN-SUFFIX,ydstatic.com,DIRECT
DOMAIN-SUFFIX,youku.com,DIRECT
DOMAIN-SUFFIX,zhangzishi.cc,DIRECT
DOMAIN-SUFFIX,zhihu.com,DIRECT
DOMAIN-SUFFIX,zhimg.com,DIRECT
DOMAIN-SUFFIX,zhuihd.com,DIRECT
DOMAIN-SUFFIX,zimuzu.io,DIRECT
DOMAIN-SUFFIX,zimuzu.tv,DIRECT
DOMAIN-SUFFIX,zmz2019.com,DIRECT
DOMAIN-SUFFIX,zmzapi.com,DIRECT
DOMAIN-SUFFIX,zmzapi.net,DIRECT
DOMAIN-SUFFIX,zmzfile.com,DIRECT
DOMAIN-SUFFIX,google.cn,DIRECT
DOMAIN-SUFFIX,manmanbuy.com,DIRECT
DOMAIN,www-cdn.icloud.com.akadns.net,DIRECT
DOMAIN-SUFFIX,aaplimg.com,DIRECT
DOMAIN-SUFFIX,apple-cloudkit.com,DIRECT
DOMAIN-SUFFIX,apple.co,DIRECT
DOMAIN-SUFFIX,apple.com,DIRECT
DOMAIN-SUFFIX,apple.com.cn,DIRECT
DOMAIN-SUFFIX,appstore.com,DIRECT
DOMAIN-SUFFIX,cdn-apple.com,DIRECT
DOMAIN-SUFFIX,crashlytics.com,DIRECT
DOMAIN-SUFFIX,icloud-content.com,DIRECT
DOMAIN-SUFFIX,icloud.com,DIRECT
DOMAIN-SUFFIX,icloud.com.cn,DIRECT
DOMAIN-SUFFIX,me.com,DIRECT
DOMAIN-SUFFIX,mzstatic.com,DIRECT
DOMAIN-SUFFIX,scdn.co,PROXY
DOMAIN-SUFFIX,line.naver.jp,PROXY
DOMAIN-SUFFIX,line.me,PROXY
DOMAIN-SUFFIX,line-apps.com,PROXY
DOMAIN-SUFFIX,line-cdn.net,PROXY
DOMAIN-SUFFIX,line-scdn.net,PROXY
USER-AGENT,Line*,PROXY
DOMAIN-KEYWORD,blogspot,PROXY
DOMAIN-KEYWORD,google,PROXY
DOMAIN-SUFFIX,abc.xyz,PROXY
DOMAIN-SUFFIX,admin.recaptcha.net,PROXY
DOMAIN-SUFFIX,ampproject.org,PROXY
DOMAIN-SUFFIX,android.com,PROXY
DOMAIN-SUFFIX,androidify.com,PROXY
DOMAIN-SUFFIX,appspot.com,PROXY
DOMAIN-SUFFIX,autodraw.com,PROXY
DOMAIN-SUFFIX,blogger.com,PROXY
DOMAIN-SUFFIX,capitalg.com,PROXY
DOMAIN-SUFFIX,certificate-transparency.org,PROXY
DOMAIN-SUFFIX,chrome.com,PROXY
DOMAIN-SUFFIX,chromeexperiments.com,PROXY
DOMAIN-SUFFIX,chromestatus.com,PROXY
DOMAIN-SUFFIX,chromium.org,PROXY
DOMAIN-SUFFIX,creativelab5.com,PROXY
DOMAIN-SUFFIX,debug.com,PROXY
DOMAIN-SUFFIX,deepmind.com,PROXY
DOMAIN-SUFFIX,dialogflow.com,PROXY
DOMAIN-SUFFIX,firebaseio.com,PROXY
DOMAIN-SUFFIX,getmdl.io,PROXY
DOMAIN-SUFFIX,getoutline.org,PROXY
DOMAIN-SUFFIX,ggpht.com,PROXY
DOMAIN-SUFFIX,gmail.com,PROXY
DOMAIN-SUFFIX,gmodules.com,PROXY
DOMAIN-SUFFIX,godoc.org,PROXY
DOMAIN-SUFFIX,golang.org,PROXY
DOMAIN-SUFFIX,gstatic.com,PROXY
DOMAIN-SUFFIX,gv.com,PROXY
DOMAIN-SUFFIX,gvt0.com,PROXY
DOMAIN-SUFFIX,gvt1.com,PROXY
DOMAIN-SUFFIX,gvt3.com,PROXY
DOMAIN-SUFFIX,gwtproject.org,PROXY
DOMAIN-SUFFIX,itasoftware.com,PROXY
DOMAIN-SUFFIX,madewithcode.com,PROXY
DOMAIN-SUFFIX,material.io,PROXY
DOMAIN-SUFFIX,polymer-project.org,PROXY
DOMAIN-SUFFIX,recaptcha.net,PROXY
DOMAIN-SUFFIX,shattered.io,PROXY
DOMAIN-SUFFIX,synergyse.com,PROXY
DOMAIN-SUFFIX,telephony.goog,PROXY
DOMAIN-SUFFIX,tensorflow.org,PROXY
DOMAIN-SUFFIX,tfhub.dev,PROXY
DOMAIN-SUFFIX,tiltbrush.com,PROXY
DOMAIN-SUFFIX,waveprotocol.org,PROXY
DOMAIN-SUFFIX,waymo.com,PROXY
DOMAIN-SUFFIX,webmproject.org,PROXY
DOMAIN-SUFFIX,webrtc.org,PROXY
DOMAIN-SUFFIX,whatbrowser.org,PROXY
DOMAIN-SUFFIX,widevine.com,PROXY
DOMAIN-SUFFIX,x.company,PROXY
DOMAIN-SUFFIX,xn--ngstr-lra8j.com,PROXY
DOMAIN-SUFFIX,youtu.be,PROXY
DOMAIN-SUFFIX,yt.be,PROXY
DOMAIN-SUFFIX,ytimg.com,PROXY
DOMAIN-KEYWORD,aka,PROXY
DOMAIN-KEYWORD,facebook,PROXY
DOMAIN-KEYWORD,youtube,PROXY
DOMAIN-KEYWORD,twitter,PROXY
DOMAIN-KEYWORD,instagram,PROXY
DOMAIN-KEYWORD,gmail,PROXY
DOMAIN-KEYWORD,pixiv,PROXY
DOMAIN-SUFFIX,fb.com,PROXY
DOMAIN-SUFFIX,twimg.com,PROXY
DOMAIN-SUFFIX,t.co,PROXY
DOMAIN-SUFFIX,kenengba.com,PROXY
DOMAIN-SUFFIX,akamai.net,PROXY
DOMAIN-SUFFIX,whatsapp.net,PROXY
DOMAIN-SUFFIX,whatsapp.com,PROXY
DOMAIN-SUFFIX,snapchat.com,PROXY
DOMAIN-SUFFIX,amazonaws.com,PROXY
DOMAIN-SUFFIX,angularjs.org,PROXY
DOMAIN-SUFFIX,akamaihd.net,PROXY
DOMAIN-SUFFIX,amazon.com,PROXY
DOMAIN-SUFFIX,bit.ly,PROXY
DOMAIN-SUFFIX,bitbucket.org,PROXY
DOMAIN-SUFFIX,blog.com,PROXY
DOMAIN-SUFFIX,blogcdn.com,PROXY
DOMAIN-SUFFIX,blogsmithmedia.com,PROXY
DOMAIN-SUFFIX,box.net,PROXY
DOMAIN-SUFFIX,bloomberg.com,PROXY
DOMAIN-SUFFIX,cl.ly,PROXY
DOMAIN-SUFFIX,cloudfront.net,PROXY
DOMAIN-SUFFIX,cloudflare.com,PROXY
DOMAIN-SUFFIX,cocoapods.org,PROXY
DOMAIN-SUFFIX,dribbble.com,PROXY
DOMAIN-SUFFIX,dropbox.com,PROXY
DOMAIN-SUFFIX,dropboxstatic.com,PROXY
DOMAIN-SUFFIX,dropboxusercontent.com,PROXY
DOMAIN-SUFFIX,docker.com,PROXY
DOMAIN-SUFFIX,duckduckgo.com,PROXY
DOMAIN-SUFFIX,digicert.com,PROXY
DOMAIN-SUFFIX,dnsimple.com,PROXY
DOMAIN-SUFFIX,edgecastcdn.net,PROXY
DOMAIN-SUFFIX,engadget.com,PROXY
DOMAIN-SUFFIX,eurekavpt.com,PROXY
DOMAIN-SUFFIX,fb.me,PROXY
DOMAIN-SUFFIX,fbcdn.net,PROXY
DOMAIN-SUFFIX,fc2.com,PROXY
DOMAIN-SUFFIX,feedburner.com,PROXY
DOMAIN-SUFFIX,fabric.io,PROXY
DOMAIN-SUFFIX,flickr.com,PROXY
DOMAIN-SUFFIX,fastly.net,PROXY
DOMAIN-SUFFIX,github.com,PROXY
DOMAIN-SUFFIX,github.io,PROXY
DOMAIN-SUFFIX,githubusercontent.com,PROXY
DOMAIN-SUFFIX,goo.gl,PROXY
DOMAIN-SUFFIX,godaddy.com,PROXY
DOMAIN-SUFFIX,gravatar.com,PROXY
DOMAIN-SUFFIX,imageshack.us,PROXY
DOMAIN-SUFFIX,imgur.com,PROXY
DOMAIN-SUFFIX,jshint.com,PROXY
DOMAIN-SUFFIX,ift.tt,PROXY
DOMAIN-SUFFIX,j.mp,PROXY
DOMAIN-SUFFIX,kat.cr,PROXY
DOMAIN-SUFFIX,linode.com,PROXY
DOMAIN-SUFFIX,lithium.com,PROXY
DOMAIN-SUFFIX,megaupload.com,PROXY
DOMAIN-SUFFIX,mobile01.com,PROXY
DOMAIN-SUFFIX,modmyi.com,PROXY
DOMAIN-SUFFIX,nytimes.com,PROXY
DOMAIN-SUFFIX,name.com,PROXY
DOMAIN-SUFFIX,openvpn.net,PROXY
DOMAIN-SUFFIX,openwrt.org,PROXY
DOMAIN-SUFFIX,ow.ly,PROXY
DOMAIN-SUFFIX,pinboard.in,PROXY
DOMAIN-SUFFIX,ssl-images-amazon.com,PROXY
DOMAIN-SUFFIX,sstatic.net,PROXY
DOMAIN-SUFFIX,stackoverflow.com,PROXY
DOMAIN-SUFFIX,staticflickr.com,PROXY
DOMAIN-SUFFIX,squarespace.com,PROXY
DOMAIN-SUFFIX,symcd.com,PROXY
DOMAIN-SUFFIX,symcb.com,PROXY
DOMAIN-SUFFIX,symauth.com,PROXY
DOMAIN-SUFFIX,ubnt.com,PROXY
DOMAIN-SUFFIX,thepiratebay.org,PROXY
DOMAIN-SUFFIX,tumblr.com,PROXY
DOMAIN-SUFFIX,twitch.tv,PROXY
DOMAIN-SUFFIX,twitter.com,PROXY
DOMAIN-SUFFIX,wikipedia.com,PROXY
DOMAIN-SUFFIX,wikipedia.org,PROXY
DOMAIN-SUFFIX,wikimedia.org,PROXY
DOMAIN-SUFFIX,wordpress.com,PROXY
DOMAIN-SUFFIX,wsj.com,PROXY
DOMAIN-SUFFIX,wsj.net,PROXY
DOMAIN-SUFFIX,wp.com,PROXY
DOMAIN-SUFFIX,vimeo.com,PROXY
DOMAIN-SUFFIX,tapbots.com,PROXY
DOMAIN-SUFFIX,ykimg.com,DIRECT
DOMAIN-SUFFIX,medium.com,PROXY
DOMAIN-SUFFIX,fast.com,PROXY
DOMAIN-SUFFIX,nflxvideo.net,PROXY
DOMAIN-SUFFIX,soundcloud.com,PROXY
DOMAIN-SUFFIX,sndcdn.com,PROXY
DOMAIN-SUFFIX,t.me,PROXY
DOMAIN-SUFFIX,tdesktop.com,PROXY
DOMAIN-SUFFIX,telegra.ph,PROXY
DOMAIN-SUFFIX,telegram.me,PROXY
DOMAIN-SUFFIX,telegram.org,PROXY
DOMAIN-SUFFIX,telesco.pe,PROXY
IP-CIDR,91.108.4.0/22,PROXY,no-resolve
IP-CIDR,91.108.8.0/22,PROXY,no-resolve
IP-CIDR,91.108.12.0/22,PROXY,no-resolve
IP-CIDR,91.108.16.0/22,PROXY,no-resolve
IP-CIDR,91.108.56.0/22,PROXY,no-resolve
IP-CIDR,109.239.140.0/24,PROXY,no-resolve
IP-CIDR,149.154.160.0/20,PROXY,no-resolve
IP-CIDR,2001:B28:F23D::/48,PROXY,no-resolve
IP-CIDR,2001:B28:F23F::/48,PROXY,no-resolve
IP-CIDR,2001:67C:4E8::/48,PROXY,no-resolve
IP-CIDR,192.168.0.0/16,DIRECT
IP-CIDR,10.0.0.0/8,DIRECT
IP-CIDR,172.16.0.0/12,DIRECT
IP-CIDR,127.0.0.0/8,DIRECT
GEOIP,CN,DIRECT
FINAL,DIRECT
FINAL,PROXY

[Host]
localhost = 127.0.0.1

[URL Rewrite]
(^https?:\/\/.+\.googlevideo\.com\/.+)(&ctier=[A-Z])(&.+) $1$3 302
^http://(www.)?g.cn https://www.google.com 302
^http://(www.)?google.cn https://www.google.com 302
//UPDATE: 19-04-2022
//Block Revoke
https://ppq.apple.com/.+/authorization https://dl.dropboxusercontent.com/s/oopmg6wybca8eyj/anti-revoke 302
(ocsp.+)/(ocsp.+wwdrg.+) _ REJECT
^https?:\/\/(\w+\.)?(adclick|ads([0-9]+)?|adx|adserver|adformat|analysis|analytics|banners?|click|counter|delivery|log|log-?\w+?|pagead|stat|stats|statis|trace|track|tracking|uniad)\.\w+\.(com|cn|org|info|io|net|vn|com.vn) reject 
[Script]
# FAKE IN-APP
//THANKS FOR HCSAVN
———————• fakeiAP 1 •——————— = type=rule,script-path=Restore.,timeout=10,enable=false 
Adguard = type=http-response,script-path=https://raw.githubusercontent.com/hcsavn/Quantumult-X/main/script/adguard.js,pattern = https://mobile-api.adguard.com/api/.+/ios_validate_receipt,max-size=131072,requires-body=true,timeout=10,enable=true
Apollo for Reddit = type=http-response,script-path=https://raw.githubusercontent.com/hcsavn/Quantumult-X/main/script/apollo.js,pattern = https://apollopushserver.xyz/api/verify,max-size=131072,requires-body=true,timeout=10,enable=true
Boom: Bass Booster & Equalizer = type=http-response,script-path=https://raw.githubusercontent.com/hcsavn/Quantumult-X/main/script/boom-music.js,pattern = https://apimboom2.globaldelight.net/itunesreceipt_v2.php,max-size=131072,requires-body=true,timeout=10,enable=true
KineMaster = type=http-response,script-path=https://raw.githubusercontent.com/hcsavn/Quantumult-X/main/script/kinemaster.js,pattern = https://api-kinemaster-assetstore.kinemasters.com/.+/product/verifyReceipt,max-size=131072,requires-body=true,timeout=10,enable=true
Picsart = type=http-response,script-path=https://raw.githubusercontent.com/hcsavn/Quantumult-X/main/script/picsart.js,pattern = https://api.picsart.com/shop/subscription/validate,max-size=131072,requires-body=true,timeout=10,enable=true
‎ = type=dns,script-path=‎,timeout=10,enable=false
———————• fakeiAP 2 •——————— = type=http-response,script-path=Login account.,pattern=none,max-size=131072,requires-body=true,timeout=10,enable=false 
‎ = type=dns,script-path=‎,timeout=10,enable=false 
———————• fakeiAP 3 •——————— = type=rule,script-path=Always enable VPN when use app.,timeout=10,enable=false 
Mate Translate = type=http-response,script-path=https://raw.githubusercontent.com/hcsavn/Quantumult-X/main/script/mate-translate.js,pattern = https://sync.matetranslate.com/subscription,max-size=131072,requires-body=true,timeout=10,enable=true
RNI Films & RNI Aero = type=http-response,script-path=https://raw.githubusercontent.com/hcsavn/Quantumult-X/main/script/rni.js,pattern = https://pro-status-service-prod.azurewebsites.net/api/.+,max-size=131072,requires-body=true,timeout=10,enable=true
‎ = type=dns,script-path=‎,timeout=10,enable=false
———————• fakeiAP 4 •——————— = type=rule,script-path=Only enable script when restore.,timeout=10,enable=false 
MD Clock = type=http-response,script-path=https://raw.githubusercontent.com/hcsavn/Quantumult-X/main/script/mdclock.js,pattern=https://api.revenuecat.com/v1/receipts,max-size=131072,requires-body=true,timeout=10,enable=false
VSCO = type=http-response,script-path=https://raw.githubusercontent.com/hcsavn/Quantumult-X/main/script/vsco.js,pattern=https://api.revenuecat.com/v1/(receipts$|subscribers/\d{0,10}$),max-size=131072,requires-body=true,timeout=10,enable=false

// THANK FOR ISTEAL-IT
Kinemaster = type=http-response,script-path=https://raw.githubusercontent.com/iSteal-it/script/main/Kinemaster.json,pattern=^https:\/\/api-kinemaster-assetstore\.(nexstreaming|kinemasters)\.com\/.+\/product\/verifyReceipt$,max-size=131072,requires-body=true,timeout=10,enable=true
alight motion = type=http-response,script-path=https://raw.githubusercontent.com/iSteal-it/script/main/alight-motion.json,pattern=^https?:\/\/us-central1-alight-creative\.cloudfunctions\.net\/getAccountStatusAndLicenses,max-size=131072,requires-body=true,timeout=10,enable=true 
picsart = type=http-response,script-path=https://raw.githubusercontent.com/iSteal-it/script/main/picart.json,pattern=^https:\/\/api\.picsart\.com\/shop\/subscription\/validate,max-size=131072,requires-body=true,timeout=10,enable=true 
funimate = type=http-response,script-path=https://raw.githubusercontent.com/iSteal-it/script/main/Funimate.json,pattern=^https:\/\/api\.funimate\.com\/users\/me,max-size=131072,requires-body=true,timeout=10,enable=true 
Photomath =type=http-response,script-path=https://raw.githubusercontent.com/iSteal-it/script/main/Photomath.json,pattern=^https:\/\/lapi\.photomath\.net\/v4\/me,max-size=131072,requires-body=true,timeout=10,enable=true 
Photoshop =type=http-response,script-path=https://raw.githubusercontent.com/iSteal-it/script/main/Photoshop.json,pattern=^https:\/\/lcs-mobile-cops\.adobe\.io\/mobile_profile,max-size=131072,requires-body=true,timeout=10,enable=true 
Lightroom =type=http-response,script-path=https://raw.githubusercontent.com/iSteal-it/script/main/Lightroom.json,pattern=^https:\/\/photos\.adobe\.io\/v2\/accounts,max-size=131072,requires-body=true,timeout=10,enable=true 
Djay = type=http-response,script-path=https://raw.githubusercontent.com/iSteal-it/script/main/djay.json,pattern=^https:\/\/app\.algoriddim\.com\/api\/v1\/validate-receipt,max-size=131072,requires-body=true,timeout=10,enable=true 
Vllo = type=http-response,script-path=https://raw.githubusercontent.com/iSteal-it/script/main/vllo.json,pattern=^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt,max-size=131072,requires-body=true,timeout=10,enable=true 
vizmato = type=http-response,script-path=https://raw.githubusercontent.com/iSteal-it/script/main/vizmato.json,pattern=^https:\/\/web\.vizmato\.com\/itunesreceipt_v5\.php,max-size=131072,requires-body=true,timeout=10,enable=true 
reface = type = http-response, script-path=https://raw.githubusercontent.com/iSteal-it/script/main/reface.json,pattern=^https:\/\/api\.reface\.video\/api\/reface\/v1\/iosSubscription,requires-body=true,timeout=10,enable=true 
mojo = type = http-response, script-path=https://raw.githubusercontent.com/iSteal-it/script/main/mojo.json,pattern=^https?:\/\/api\.revenuecat\.com\/.+\/(receipts$|subscribers\/[a-zA-Z0-9_-]*$),max-size=131072,requires-body=true,timeout=10,enable=true 
bussu = type = http-response, script-path=https://raw.githubusercontent.com/iSteal-it/script/main/bussu.json,pattern=^https:\/\/api\.busuu\.com\/users\/me,max-size=131072,requires-body=true,timeout=10,enable=true 
calm = type = http-response,script-path=https://raw.githubusercontent.com/iSteal-it/script/main/calm.json,pattern=^https:\/\/api\.calm\.com\/me$,requires-body=true,timeout=10,enable=true 
unfold =type=http-response,script-path=https://raw.githubusercontent.com/iSteal-it/script/main/unfoldtest.json,pattern=^https:\/\/api\.unfold\.app\/v1\/ios\/receipts,requires-body=true,timeout=10,enable=true 
mosaic = type=http-response,script-path=https://raw.githubusercontent.com/iSteal-it/script/main/mosaic.json,pattern=^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt$,requires-body=true,timeout=10,enable=true 
[MITM]
hostname = ppq.apple.com,ocsp*.apple.com,graph.nhaccuatui.com,spclient.wg.spotify.com,*.googlevideo.com,s.youtube.com,www.youtube.com,www.googleapis.com,youtubei.googleapis.com,mobile-api.adguard.com,apollopushserver.xyz,apimboom*.globaldelight.net,api-kinemaster-assetstore.kinemasters.com,sync.matetranslate.com,api.revenuecat.com,api.picsart.com,pro-status-service-prod.azurewebsites.net, api-kinemaster-assetstore.kinemasters.com,us-central1-alight-creative.cloudfunctions.net,api.picsart.com,api.funimate.com,lapi.photomath.net,lcs-mobile-cops.adobe.io,api.revenuecat.com,app.algoriddim.com,buy.itunes.apple.com,web.vizmato.com,api.reface.video,api.revenuecat.com,api.busuu.com,api.calm.com,www.calm.com,api.unfold.app
ca-passphrase = Shadowrocket
enable = true
ca-p12 = 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
