(function(g){var window=this;'use strict';var Hhb=function(a,b){g.V.call(this,{G:"button",Ia:["ytp-miniplayer-expand-watch-page-button","ytp-button","ytp-miniplayer-button-top-left"],X:{title:"{{title}}","data-tooltip-target-id":"ytp-miniplayer-expand-watch-page-button","aria-keyshortcuts":"i","data-title-no-tooltip":"{{data-title-no-tooltip}}"},W:[{G:"svg",X:{height:"24px",version:"1.1",viewBox:"0 0 24 24",width:"24px"},W:[{G:"g",X:{fill:"none","fill-rule":"evenodd",stroke:"none","stroke-width":"1"},W:[{G:"g",X:{transform:"translate(12.000000, 12.000000) scale(-1, 1) translate(-12.000000, -12.000000) "},
W:[{G:"path",X:{d:"M19,19 L5,19 L5,5 L12,5 L12,3 L5,3 C3.89,3 3,3.9 3,5 L3,19 C3,20.1 3.89,21 5,21 L19,21 C20.1,21 21,20.1 21,19 L21,12 L19,12 L19,19 Z M14,3 L14,5 L17.59,5 L7.76,14.83 L9.17,16.24 L19,6.41 L19,10 L21,10 L21,3 L14,3 Z",fill:"#fff","fill-rule":"nonzero"}}]}]}]}]});this.F=a;this.Ra("click",this.onClick,this);this.updateValue("title",g.QT(a,"Expand","i"));this.update({"data-title-no-tooltip":"Expand"});g.jb(this,g.IS(b.Dc(),this.element))},Ihb=function(a){g.V.call(this,{G:"div",
N:"ytp-miniplayer-ui"});this.dg=!1;this.player=a;this.S(a,"minimized",this.Uh);this.S(a,"onStateChange",this.uP)},Jhb=function(a){g.sT.call(this,a);
this.u=new g.aI(this);this.j=new Ihb(this.player);this.j.hide();g.uS(this.player,this.j.element,4);a.eg()&&(this.load(),g.Up(a.getRootNode(),"ytp-player-minimized",!0))};
g.x(Hhb,g.V);Hhb.prototype.onClick=function(){this.F.Na("onExpandMiniplayer")};g.x(Ihb,g.V);g.k=Ihb.prototype;
g.k.qM=function(){this.tooltip=new g.TV(this.player,this);g.J(this,this.tooltip);g.uS(this.player,this.tooltip.element,4);this.tooltip.scale=.6;this.Rc=new g.bU(this.player);g.J(this,this.Rc);this.Uj=new g.V({G:"div",N:"ytp-miniplayer-scrim"});g.J(this,this.Uj);this.Uj.Ga(this.element);this.S(this.Uj.element,"click",this.bH);var a=new g.V({G:"button",Ia:["ytp-miniplayer-close-button","ytp-button"],X:{"aria-label":"Close"},W:[g.EQ()]});g.J(this,a);a.Ga(this.Uj.element);this.S(a.element,"click",this.Zo);
a=new Hhb(this.player,this);g.J(this,a);a.Ga(this.Uj.element);this.Ku=new g.V({G:"div",N:"ytp-miniplayer-controls"});g.J(this,this.Ku);this.Ku.Ga(this.Uj.element);this.S(this.Ku.element,"click",this.bH);var b=new g.V({G:"div",N:"ytp-miniplayer-button-container"});g.J(this,b);b.Ga(this.Ku.element);a=new g.V({G:"div",N:"ytp-miniplayer-play-button-container"});g.J(this,a);a.Ga(this.Ku.element);var c=new g.V({G:"div",N:"ytp-miniplayer-button-container"});g.J(this,c);c.Ga(this.Ku.element);this.XW=new g.eV(this.player,
this,!1);g.J(this,this.XW);this.XW.Ga(b.element);b=new g.dV(this.player,this);g.J(this,b);b.Ga(a.element);this.nextButton=new g.eV(this.player,this,!0);g.J(this,this.nextButton);this.nextButton.Ga(c.element);this.sj=new g.MV(this.player,this);g.J(this,this.sj);this.sj.Ga(this.Uj.element);this.Kc=new g.jV(this.player,this);g.J(this,this.Kc);g.uS(this.player,this.Kc.element,4);this.OG=new g.V({G:"div",N:"ytp-miniplayer-buttons"});g.J(this,this.OG);g.uS(this.player,this.OG.element,4);a=new g.V({G:"button",
Ia:["ytp-miniplayer-close-button","ytp-button"],X:{"aria-label":"Close"},W:[g.EQ()]});g.J(this,a);a.Ga(this.OG.element);this.S(a.element,"click",this.Zo);a=new g.V({G:"button",Ia:["ytp-miniplayer-replay-button","ytp-button"],X:{"aria-label":"Close"},W:[g.yDa()]});g.J(this,a);a.Ga(this.OG.element);this.S(a.element,"click",this.X6);this.S(this.player,"presentingplayerstatechange",this.Bd);this.S(this.player,"appresize",this.Fb);this.S(this.player,"fullscreentoggled",this.Fb);this.Fb()};
g.k.show=function(){this.qf=new g.Gp(this.Iv,null,this);this.qf.start();this.dg||(this.qM(),this.dg=!0);0!==this.player.getPlayerState()&&g.V.prototype.show.call(this);this.Kc.show();this.player.unloadModule("annotations_module")};
g.k.hide=function(){this.qf&&(this.qf.dispose(),this.qf=void 0);g.V.prototype.hide.call(this);this.player.eg()||(this.dg&&this.Kc.hide(),this.player.loadModule("annotations_module"))};
g.k.qa=function(){this.qf&&(this.qf.dispose(),this.qf=void 0);g.V.prototype.qa.call(this)};
g.k.Zo=function(){this.player.stopVideo();this.player.Na("onCloseMiniplayer")};
g.k.X6=function(){this.player.playVideo()};
g.k.bH=function(a){if(a.target===this.Uj.element||a.target===this.Ku.element)g.hP(this.player.Eb())?this.player.pauseVideo():this.player.playVideo()};
g.k.Uh=function(){g.Up(this.player.getRootNode(),"ytp-player-minimized",this.player.eg())};
g.k.Pe=function(){this.Kc.yc();this.sj.yc()};
g.k.Iv=function(){this.Pe();this.qf&&this.qf.start()};
g.k.Bd=function(a){g.hO(a.state,32)&&this.tooltip.hide()};
g.k.Fb=function(){g.vV(this.Kc,0,this.player.jb().getPlayerSize().width,!1);g.kV(this.Kc)};
g.k.uP=function(a){this.player.eg()&&(0===a?this.hide():this.show())};
g.k.Dc=function(){return this.tooltip};
g.k.zg=function(){return!1};
g.k.Xg=function(){return!1};
g.k.Ub=function(){return!1};
g.k.Ql=function(){return!1};
g.k.XH=function(){};
g.k.Op=function(){};
g.k.qy=function(){};
g.k.Om=function(){return null};
g.k.KF=function(){return null};
g.k.JL=function(){return new g.xe(0,0)};
g.k.Ak=function(){return new g.Om(0,0,0,0)};
g.k.handleGlobalKeyDown=function(){return!1};
g.k.handleGlobalKeyUp=function(){return!1};
g.k.Tv=function(a,b,c,d,e){var f=0,h=d=0,l=g.bn(a);if(b){c=g.Pp(b,"ytp-prev-button")||g.Pp(b,"ytp-next-button");var m=g.Pp(b,"ytp-play-button"),n=g.Pp(b,"ytp-miniplayer-expand-watch-page-button");c?f=h=12:m?(b=g.$m(b,this.element),h=b.x,f=b.y-12):n&&(h=g.Pp(b,"ytp-miniplayer-button-top-left"),f=g.$m(b,this.element),b=g.bn(b),h?(h=8,f=f.y+40):(h=f.x-l.width+b.width,f=f.y-20))}else h=c-l.width/2,d=25+(e||0);b=this.player.jb().getPlayerSize().width;e=f+(e||0);l=g.pe(h,0,b-l.width);e?(a.style.top=e+"px",
a.style.bottom=""):(a.style.top="",a.style.bottom=d+"px");a.style.left=l+"px"};
g.k.showControls=function(){};
g.k.tp=function(){};
g.k.Il=function(){return!1};
g.k.PD=function(){};
g.k.Qz=function(){};
g.k.Tq=function(){};
g.k.Sq=function(){};
g.k.UA=function(){};
g.k.Wr=function(){};
g.k.AD=function(){};g.x(Jhb,g.sT);g.k=Jhb.prototype;g.k.onVideoDataChange=function(){if(this.player.getVideoData()){var a=this.player.getVideoAspectRatio(),b=16/9;a=a>b+.1||a<b-.1;g.Up(this.player.getRootNode(),"ytp-rounded-miniplayer-not-regular-wide-video",a)}};
g.k.create=function(){g.sT.prototype.create.call(this);this.u.S(this.player,"videodatachange",this.onVideoDataChange);this.onVideoDataChange()};
g.k.Xk=function(){return!1};
g.k.load=function(){this.player.hideControls();this.j.show()};
g.k.unload=function(){this.player.showControls();this.j.hide()};g.rT("miniplayer",Jhb);})(_yt_player);
