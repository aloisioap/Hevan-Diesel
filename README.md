<!DOCTYPE html>
<!--[if lte IE 8]>               <html prefix="og: http://ogp.me/ns#" class="ie8 no-js" lang="en">    <![endif]-->
<!--[if lte IE 10]>				 <html prefix="og: http://ogp.me/ns#" class="ie10 no-js" lang="en">   <![endif]-->
<!--[if !IE]>-->				 <html prefix="og: http://ogp.me/ns#" class="not-ie no-js" lang="en"> <!--<![endif]-->
<head>
		<base href="http://www.hevandiesel.com.br/" />
	<meta http-equiv="content-type" content="text/html; charset=utf-8" />
	<meta name="author" content="ShineTheme" />
	<meta name="generator" content="Joomla! - Open Source Content Management" />
	<title>Hevan Diesel - Página Inicial</title>
	<link href="/components/com_k2/css/k2.css" rel="stylesheet" type="text/css" />
	<link href="http://www.hevandiesel.com.br/media/com_uniterevolution2/assets/rs-plugin/css/settings.css" rel="stylesheet" type="text/css" />
	<link href="http://www.hevandiesel.com.br/index.php?option=com_uniterevolution2&amp;action=getcaptions" rel="stylesheet" type="text/css" />
	<link href="http://www.hevandiesel.com.br/media/com_uniterevolution2/assets/rs-plugin/css/static-captions.css" rel="stylesheet" type="text/css" />
	<link href="/modules/mod_responsive_contact_form/css/style.css" rel="stylesheet" type="text/css" />
	<script type="text/javascript" src="http://ff.kis.v2.scr.kaspersky-labs.com/9B63DFBC-61B6-2346-859F-C532981C531F/main.js" charset="UTF-8"></script><script src="https://ajax.googleapis.com/ajax/libs/jquery/1.8/jquery.min.js" type="text/javascript"></script>
	<script src="/plugins/system/jqueryeasy/jquerynoconflict.js" type="text/javascript"></script>
	<script src="/media/system/js/mootools-core.js" type="text/javascript"></script>
	<script src="/media/system/js/core.js" type="text/javascript"></script>
	<script src="/media/system/js/mootools-more.js" type="text/javascript"></script>
	
	
	
	<script src="/components/com_k2/js/k2.js?v2.6.8&amp;sitepath=/" type="text/javascript"></script>
	<script src="http://maps.google.com/maps/api/js?sensor=true" type="text/javascript"></script>
	<script src="/plugins/system/shinetheme/assets/js/jquery.ui.map.min.js" type="text/javascript"></script>
	
	<script src="/modules/mod_responsive_contact_form/js/jqBootstrapValidation.min.js" type="text/javascript"></script>
	<script type="text/javascript">
jQuery(document).ready(function($) {
				var stmapdefault = '-21.129458,-42.385407';
				var marker = {position:stmapdefault}
				$('#map_canvas').gmap({
					'zoom': 16 ,
					'center': stmapdefault,
					'mapTypeId':google.maps.MapTypeId.ROADMAP  ,
					'callback': function() {
						var self = this;
						self.addMarker(marker).click(function(){
							self.openInfoWindow({'content': 'Avenida Rio Bahia, 5935, Gaspar, Muriaé'}, this);
						});
					},
					panControl: true,
					zoomControl: true,
					mapTypeControl: true,
					streetViewControl: true,
					scrollwheel:false
				});	

				$(window).resize(function(){
					var stct = new google.maps.LatLng('-21.129458','-42.385407');
					$('#map_canvas').gmap('option', 'center', stct);
				});	
			});
			

jQuery(function () { jQuery("input,select,textarea").not("[type=submit]").jqBootstrapValidation(); } );
	</script>

	
	<!-- Load Google Font-->
	<link href='http://fonts.googleapis.com/css?family=Roboto:100,300,300italic,400,700|Julius+Sans+One|Roboto+Condensed:300,400' rel='stylesheet' type='text/css'>
		<style type="text/css">
			body, h1, h2, h3, h4, h5, h6, p, span {
				font-family: 'Roboto Condensed', sans-serif !important;
			}
		</style>
	
	<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
	
	<title>Accio</title>	
	
	<meta name="description" content="">
	<meta name="author" content="">	

	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">

	<link rel="shortcut icon" href="/images/favicon.ico">
	<link rel="apple-touch-icon" href="/images/apple-touch-icon.png">
	<link rel="apple-touch-icon" sizes="72x72" href="/images/apple-touch-icon-72x72.png">
	<link rel="apple-touch-icon" sizes="114x114" href="/images/apple-touch-icon-114x114.png">
	
    <link rel="stylesheet" href="/templates/accio/css/style.css" />
	<link rel="stylesheet" href="/templates/accio/css/grid.css" />
	<link rel="stylesheet" href="/templates/accio/css/layout.css" />
	<link rel="stylesheet" href="/templates/accio/css/fontello.css" />
	<link rel="stylesheet" href="/templates/accio/css/animation.css" />
	
	<link rel="stylesheet" href="/templates/accio/js/layerslider/css/layerslider.css" />
	<link rel="stylesheet" href="/templates/accio/js/flexslider/flexslider.css" />
	<link rel="stylesheet" href="/templates/accio/js/fancybox/jquery.fancybox.css" />
	<link rel="stylesheet" href="/templates/accio/js/layerslider/skins/accio/skin.css" />
	<link rel="stylesheet/less" type="text/css" 
        href="/templates/accio/less/color.php?main_color=333333">
	
    








</head>

<body data-spy="scroll" data-target="#navigation" class="home">
	
	
	<div class="loader" style=" display: none;"></div>	
	
<header id="header" class="transparent">
	<div class="header-in clearfix">
		
		<h1 id="logo"><a href="http://www.hevandiesel.com.br/"><img class="main-logo img-responsive" src="http://www.hevandiesel.com.br/images/logo.png" alt="Hevan Diesel" title="Hevan Diesel" /></a></h1>
		<a id="responsive-nav-button" class="responsive-nav-button" href="#"></a>
		<nav id="navigation" class="navigation" style="">
							<ul class="st-menu ">
<li class="item-102"><a href="#Mod116" >Home</a></li><li class="item-104"><a href="#about" >Sobre Nós</a></li><li class="item-105"><a href="#team" >Equipe</a></li><li class="item-103"><a href="#folio" >Fotos</a></li><li class="item-106"><a href="#services" >Serviços</a></li><li class="item-107"><a href="#contacts" >Contato</a></li></ul>

					</nav>
	</div>
</header>

<div id="wrapper">
        	    <!-- Begin Content -->
		<div id="system-message-container">
	</div>

		<div class="st-module modulepage" id="Mod116">
	<div class="module-inner">
				<div class="module-ct">
			<!-- START REVOLUTION SLIDER 4.6.96 fullwidth mode -->
<script type='text/javascript' src='http://www.hevandiesel.com.br/media/com_uniterevolution2/assets/rs-plugin/js/jquery.themepunch.tools.min.js?rev=4.6.96'></script>
<script type='text/javascript' src='http://www.hevandiesel.com.br/media/com_uniterevolution2/assets/rs-plugin/js/jquery.themepunch.revolution.min.js?rev=4.6.96'></script>

<div id="rev_slider_1_1_wrapper" class="rev_slider_wrapper fullwidthbanner-container" style="margin:0px auto;background-color:#E9E9E9;padding:0px;margin-top:0px;margin-bottom:0px;max-height:530px;">
	<div id="rev_slider_1_1" class="rev_slider fullwidthabanner" style="display:none;max-height:530px;height:530px;">
<ul>	<!-- SLIDE  1-->
	<li data-transition="fade" data-slotamount="5" data-masterspeed="700"  data-saveperformance="off" >
		<!-- MAIN IMAGE -->
		<img src="http://www.hevandiesel.com.br/images/slides/bg_slider_5.jpg"  alt="bg_slider_5"  data-bgposition="center center" data-bgfit="cover" data-bgrepeat="no-repeat">
		<!-- LAYERS -->
	</li>
	<!-- SLIDE  2-->
	<li data-transition="fade" data-slotamount="5" data-masterspeed="700"  data-saveperformance="off" >
		<!-- MAIN IMAGE -->
		<img src="http://www.hevandiesel.com.br/images/slides/slides-01.jpg"  alt="slides-01"  data-bgposition="center center" data-bgfit="cover" data-bgrepeat="no-repeat">
		<!-- LAYERS -->
	</li>
</ul>
<div class="tp-bannertimer"></div>	</div>
			
			<script type="text/javascript">

					
				/******************************************
					-	PREPARE PLACEHOLDER FOR SLIDER	-
				******************************************/
								
				 
						var setREVStartSize = function() {
							var	tpopt = new Object(); 
								tpopt.startwidth = 1500;
								tpopt.startheight = 530;
								tpopt.container = jQuery('#rev_slider_1_1');
								tpopt.fullScreen = "off";
								tpopt.forceFullWidth="off";

							tpopt.container.closest(".rev_slider_wrapper").css({height:tpopt.container.height()});tpopt.width=parseInt(tpopt.container.width(),0);tpopt.height=parseInt(tpopt.container.height(),0);tpopt.bw=tpopt.width/tpopt.startwidth;tpopt.bh=tpopt.height/tpopt.startheight;if(tpopt.bh>tpopt.bw)tpopt.bh=tpopt.bw;if(tpopt.bh<tpopt.bw)tpopt.bw=tpopt.bh;if(tpopt.bw<tpopt.bh)tpopt.bh=tpopt.bw;if(tpopt.bh>1){tpopt.bw=1;tpopt.bh=1}if(tpopt.bw>1){tpopt.bw=1;tpopt.bh=1}tpopt.height=Math.round(tpopt.startheight*(tpopt.width/tpopt.startwidth));if(tpopt.height>tpopt.startheight&&tpopt.autoHeight!="on")tpopt.height=tpopt.startheight;if(tpopt.fullScreen=="on"){tpopt.height=tpopt.bw*tpopt.startheight;var cow=tpopt.container.parent().width();var coh=jQuery(window).height();if(tpopt.fullScreenOffsetContainer!=undefined){try{var offcontainers=tpopt.fullScreenOffsetContainer.split(",");jQuery.each(offcontainers,function(e,t){coh=coh-jQuery(t).outerHeight(true);if(coh<tpopt.minFullScreenHeight)coh=tpopt.minFullScreenHeight})}catch(e){}}tpopt.container.parent().height(coh);tpopt.container.height(coh);tpopt.container.closest(".rev_slider_wrapper").height(coh);tpopt.container.closest(".forcefullwidth_wrapper_tp_banner").find(".tp-fullwidth-forcer").height(coh);tpopt.container.css({height:"100%"});tpopt.height=coh;}else{tpopt.container.height(tpopt.height);tpopt.container.closest(".rev_slider_wrapper").height(tpopt.height);tpopt.container.closest(".forcefullwidth_wrapper_tp_banner").find(".tp-fullwidth-forcer").height(tpopt.height);}
						};
						
						/* CALL PLACEHOLDER */
						setREVStartSize();
								
				
				var tpj=jQuery;				
				tpj.noConflict();				
				var revapi1;
				
				
				
				tpj(document).ready(function() {
				
					
								
				if(tpj('#rev_slider_1_1').revolution == undefined){
					revslider_showDoubleJqueryError('#rev_slider_1_1');
				}else{
				   revapi1 = tpj('#rev_slider_1_1').show().revolution(
					{
											
						dottedOverlay:"none",
						delay:9000,
						startwidth:1500,
						startheight:530,
						hideThumbs:200,
						
						thumbWidth:100,
						thumbHeight:50,
						thumbAmount:2,
													
						simplifyAll:"off",						
						navigationType:"none",
						navigationArrows:"solo",
						navigationStyle:"round",						
						touchenabled:"on",
						onHoverStop:"on",						
						nextSlideOnWindowFocus:"off",
						
						swipe_threshold: 0.7,
						swipe_min_touches: 1,
						drag_block_vertical: false,
																		
																		
						keyboardNavigation:"off",
						
						navigationHAlign:"center",
						navigationVAlign:"bottom",
						navigationHOffset:0,
						navigationVOffset:20,

						soloArrowLeftHalign:"left",
						soloArrowLeftValign:"center",
						soloArrowLeftHOffset:20,
						soloArrowLeftVOffset:0,

						soloArrowRightHalign:"right",
						soloArrowRightValign:"center",
						soloArrowRightHOffset:20,
						soloArrowRightVOffset:0,
								
						shadow:2,
						fullWidth:"on",
						fullScreen:"off",

												spinner:"spinner5",
																		
						stopLoop:"off",
						stopAfterLoops:-1,
						stopAtSlide:-1,

						shuffle:"off",
						
						autoHeight:"off",						
						forceFullWidth:"off",						
												
												
												
						hideThumbsOnMobile:"off",
						hideNavDelayOnMobile:1500,
						hideBulletsOnMobile:"off",
						hideArrowsOnMobile:"off",
						hideThumbsUnderResolution:0,
						
												hideSliderAtLimit:0,
						hideCaptionAtLimit:0,
						hideAllCaptionAtLilmit:0,
						startWithSlide:0,
						isJoomla: true
					});
					
					
					
									}					
				});	/*ready*/
									
			</script>
			</div>
<!-- END REVOLUTION SLIDER -->			</div>
	</div>
</div> <section id="about" class="page"><section class="section"><div class="container"><div class="row"><div class="col-xs-12"><hgroup class="slogan align-center opacity"><h1>Sobre a Oficina Hevan Diesel</h1><h2>Empresa atuante no ramo de Auto Center desde 1985</h2></hgroup></div></div><!--/ .row--><div class="row"><div class="col-md-7 opacity"><p><img src="/images/quem-somos.jpg" alt="" data-mce-src="images/quem-somos.jpg"></p></div><!--/ .col-md-6--><div class="col-md-5"><p class="opacity">A Hevan Diesel Ltda, tem como proposta atender empresas de pequeno, médio e grande portes, no fornecimento de peças e prestação de serviços para regulagem e manutenção do sistema de injeção diesel (bombas e bicos injetores) e comércio de turbinas novas com garantia de fábrica.</p><p class="opacity">Contamos para isso com equipamentos modernos e completos para todos os tipos de sistema de injeção diesel, com corpo técnico especializado, sempre envolvido com a atualização tecnológica da área.</p><p class="opacity">Sabedores da responsabilidade técnica e ética profissional que esta prestação de serviços envolve, a HEVAN DIESEL LTDA., foi constituída dentro dos princípios que garantem uma prestação de serviços com qualidade, garantia e idoneidade.</p><!--/ .list--></div><!--/ .col-md-5--></div><!--/ .row--></div><!--/ .container--></section><!--/ .section--></section><!--/ .about-->	 <section class="section parallax parallax-bg-1 bg-turquoise-color" style="background-color:transparent; color:#FFFFFF">
	
				<div class="full-bg-image" style="background-image: url('/images/parallax/parallax-2.jpg')"></div>
	
				<div class="container">
	
					<div class="row">
						
						<div class="col-xs-12">
							
							<ul class="quotes opacity" data-timeout="6000">
																	<li class="align-center">
										<blockquote class="quote-text">
<p>Empresa comprometida, com equipamentos modernos e completos para todos os tipos de sistema de injeção diesel, com corpo técnico especializado, sempre envolvido com a atualização tecnológica da área.</p>
</blockquote>
<div class="quote-author">Marcos Paulo</div>									</li>
									
							</ul><!--/ .quotes-->
							
						</div>
						
					</div><!--/ .row-->
	
				</div><!--/ .container-->
	
			</section><!--/ .section-->
			
		</section><!--/ .section-->
<section id="folio" class="page">
   	<section class="section padding-bottom-off">
		<div class="container">
			<div class="row">
				<div class="col-xs-12">
					<hgroup class="section-title align-center opacity">
						<h1>Conheça nossa estrutura</h1>
					</hgroup>							
				</div>
			</div><!--/ .row-->
			<div class="row">
				<div class="col-xs-12">
					<ul id="portfolio-filter" class="portfolio-filter opacity">
						<li class="filter active" data-filter="all">All</li>
                       					</ul><!--/ #portfolio-filter -->		
				</div>
			</div><!--/ .row-->
		</div><!--/ .container-->
		<ul id="portfolio-items" class="portfolio-items">
								<li class=" mix mix_all opacity2x">
						<div class="work-item">
						<img alt="Oficina Hevan Diesel 01" title="Oficina Hevan Diesel 01"  src="http://www.hevandiesel.com.br/media/k2/items/cache/d61d44254608dd06ccdd2ff02982d14d_M.jpg"/>
							<div class="image-extra">
								<div class="extra-content">
									<div class="inner-extra">
										<h2 class="extra-title">Oficina Hevan Diesel 01</h2>
										<h6 class="extra-category"></h6>
										<a class="single-image link-icon" href="/index.php/component/k2/item/9?show=show"></a>
										<a class="single-image plus-icon" data-fancybox-group="folio" href="http://www.hevandiesel.com.br/media/k2/items/cache/d61d44254608dd06ccdd2ff02982d14d_M.jpg"></a>
									</div><!--/ .inner-extra-->	
								</div><!--/ .extra-content-->
							</div><!--/ .image-extra-->
						</div><!--/ .work-item-->
					</li>
								<li class=" mix mix_all opacity2x">
						<div class="work-item">
						<img alt="Bancada de Teste" title="Bancada de Teste"  src="http://www.hevandiesel.com.br/media/k2/items/cache/36fdb1a35cd2f54f95cf2119fb5bc7ed_M.jpg"/>
							<div class="image-extra">
								<div class="extra-content">
									<div class="inner-extra">
										<h2 class="extra-title">Bancada de Teste</h2>
										<h6 class="extra-category"></h6>
										<a class="single-image link-icon" href="/index.php/component/k2/item/38?show=show"></a>
										<a class="single-image plus-icon" data-fancybox-group="folio" href="http://www.hevandiesel.com.br/media/k2/items/cache/36fdb1a35cd2f54f95cf2119fb5bc7ed_M.jpg"></a>
									</div><!--/ .inner-extra-->	
								</div><!--/ .extra-content-->
							</div><!--/ .image-extra-->
						</div><!--/ .work-item-->
					</li>
								<li class=" mix mix_all opacity2x">
						<div class="work-item">
						<img alt="Oficina Hevan Diesel 02" title="Oficina Hevan Diesel 02"  src="http://www.hevandiesel.com.br/media/k2/items/cache/e31ace2a15a7c70645ad83df9ecd43b0_M.jpg"/>
							<div class="image-extra">
								<div class="extra-content">
									<div class="inner-extra">
										<h2 class="extra-title">Oficina Hevan Diesel 02</h2>
										<h6 class="extra-category"></h6>
										<a class="single-image link-icon" href="/index.php/component/k2/item/10?show=show"></a>
										<a class="single-image plus-icon" data-fancybox-group="folio" href="http://www.hevandiesel.com.br/media/k2/items/cache/e31ace2a15a7c70645ad83df9ecd43b0_M.jpg"></a>
									</div><!--/ .inner-extra-->	
								</div><!--/ .extra-content-->
							</div><!--/ .image-extra-->
						</div><!--/ .work-item-->
					</li>
								<li class=" mix mix_all opacity2x">
						<div class="work-item">
						<img alt="Oficina Hevan Diesel 03" title="Oficina Hevan Diesel 03"  src="http://www.hevandiesel.com.br/media/k2/items/cache/c82cc4e14a1d2c8c8ffff9840d24b558_M.jpg"/>
							<div class="image-extra">
								<div class="extra-content">
									<div class="inner-extra">
										<h2 class="extra-title">Oficina Hevan Diesel 03</h2>
										<h6 class="extra-category"></h6>
										<a class="single-image link-icon" href="/index.php/component/k2/item/11?show=show"></a>
										<a class="single-image plus-icon" data-fancybox-group="folio" href="http://www.hevandiesel.com.br/media/k2/items/cache/c82cc4e14a1d2c8c8ffff9840d24b558_M.jpg"></a>
									</div><!--/ .inner-extra-->	
								</div><!--/ .extra-content-->
							</div><!--/ .image-extra-->
						</div><!--/ .work-item-->
					</li>
								<li class=" mix mix_all opacity2x">
						<div class="work-item">
						<img alt="Oficina Hevan Diesel 04" title="Oficina Hevan Diesel 04"  src="http://www.hevandiesel.com.br/media/k2/items/cache/3899dfe821816fbcb3db3e3b23f81585_M.jpg"/>
							<div class="image-extra">
								<div class="extra-content">
									<div class="inner-extra">
										<h2 class="extra-title">Oficina Hevan Diesel 04</h2>
										<h6 class="extra-category"></h6>
										<a class="single-image link-icon" href="/index.php/component/k2/item/12?show=show"></a>
										<a class="single-image plus-icon" data-fancybox-group="folio" href="http://www.hevandiesel.com.br/media/k2/items/cache/3899dfe821816fbcb3db3e3b23f81585_M.jpg"></a>
									</div><!--/ .inner-extra-->	
								</div><!--/ .extra-content-->
							</div><!--/ .image-extra-->
						</div><!--/ .work-item-->
					</li>
								<li class=" mix mix_all opacity2x">
						<div class="work-item">
						<img alt="Oficina Hevan Diesel 05" title="Oficina Hevan Diesel 05"  src="http://www.hevandiesel.com.br/media/k2/items/cache/f710044bf79a4b1f5d8b085e5e5d9711_M.jpg"/>
							<div class="image-extra">
								<div class="extra-content">
									<div class="inner-extra">
										<h2 class="extra-title">Oficina Hevan Diesel 05</h2>
										<h6 class="extra-category"></h6>
										<a class="single-image link-icon" href="/index.php/component/k2/item/34?show=show"></a>
										<a class="single-image plus-icon" data-fancybox-group="folio" href="http://www.hevandiesel.com.br/media/k2/items/cache/f710044bf79a4b1f5d8b085e5e5d9711_M.jpg"></a>
									</div><!--/ .inner-extra-->	
								</div><!--/ .extra-content-->
							</div><!--/ .image-extra-->
						</div><!--/ .work-item-->
					</li>
								<li class=" mix mix_all opacity2x">
						<div class="work-item">
						<img alt="Oficina Hevan Diesel 06" title="Oficina Hevan Diesel 06"  src="http://www.hevandiesel.com.br/media/k2/items/cache/0b1ad7a7b79268a1f4558db78e092446_M.jpg"/>
							<div class="image-extra">
								<div class="extra-content">
									<div class="inner-extra">
										<h2 class="extra-title">Oficina Hevan Diesel 06</h2>
										<h6 class="extra-category"></h6>
										<a class="single-image link-icon" href="/index.php/component/k2/item/35?show=show"></a>
										<a class="single-image plus-icon" data-fancybox-group="folio" href="http://www.hevandiesel.com.br/media/k2/items/cache/0b1ad7a7b79268a1f4558db78e092446_M.jpg"></a>
									</div><!--/ .inner-extra-->	
								</div><!--/ .extra-content-->
							</div><!--/ .image-extra-->
						</div><!--/ .work-item-->
					</li>
								<li class=" mix mix_all opacity2x">
						<div class="work-item">
						<img alt="Oficina Hevan Diesel 07" title="Oficina Hevan Diesel 07"  src="http://www.hevandiesel.com.br/media/k2/items/cache/9ecd376e5371efaef9aad9bc9143aed8_M.jpg"/>
							<div class="image-extra">
								<div class="extra-content">
									<div class="inner-extra">
										<h2 class="extra-title">Oficina Hevan Diesel 07</h2>
										<h6 class="extra-category"></h6>
										<a class="single-image link-icon" href="/index.php/component/k2/item/36?show=show"></a>
										<a class="single-image plus-icon" data-fancybox-group="folio" href="http://www.hevandiesel.com.br/media/k2/items/cache/9ecd376e5371efaef9aad9bc9143aed8_M.jpg"></a>
									</div><!--/ .inner-extra-->	
								</div><!--/ .extra-content-->
							</div><!--/ .image-extra-->
						</div><!--/ .work-item-->
					</li>
								<li class=" mix mix_all opacity2x">
						<div class="work-item">
						<img alt="Bancada de Teste" title="Bancada de Teste"  src="http://www.hevandiesel.com.br/media/k2/items/cache/c99e3db826c0f4cc2688a36ce3b60e1a_M.jpg"/>
							<div class="image-extra">
								<div class="extra-content">
									<div class="inner-extra">
										<h2 class="extra-title">Bancada de Teste</h2>
										<h6 class="extra-category"></h6>
										<a class="single-image link-icon" href="/index.php/component/k2/item/39?show=show"></a>
										<a class="single-image plus-icon" data-fancybox-group="folio" href="http://www.hevandiesel.com.br/media/k2/items/cache/c99e3db826c0f4cc2688a36ce3b60e1a_M.jpg"></a>
									</div><!--/ .inner-extra-->	
								</div><!--/ .extra-content-->
							</div><!--/ .image-extra-->
						</div><!--/ .work-item-->
					</li>
			 							
		</ul><!--/ .portfolio-items-->			
	</section><!--/ .section-->	
</section><!--/ .page--><section id="services" class="page">
	<section class="section">
		<div class="container">
			<div class="row">
				<div class="col-xs-12">
					<hgroup class="section-title align-center opacity">
						<h1>Serviços</h1>
						<h2>Estamos mais do que felizes em lhe oferecer</h2>	
					</hgroup>					
				</div>
			</div><!--/ .row-->	
			<div class="row">
				<div class="col-xs-12">
					<div class="flexslider opacity">
						<ul class="slides">
													<li data-icon="icon-flash" data-title="Ferramental completo">
								<p>
									<p style="text-align: center;">Ferramental completo para:</p>
<p style="text-align: center;">
<table style="width: 622px; height: 148px; margin-right: auto; margin-left: auto;" align="center">
<tbody>
<tr>
<td style="margin-right: auto; margin-left: auto; vertical-align: middle;" align="center">
<p><strong><span style="font-size: 18px;">DELPHI</span></strong><br /><span style="font-size: 15px;">BOMBAS:</span><br />DPA<br /> DP 100 <br /> DPC<br /> DP 200<br /> NIPODENSO</p>
</td>
<td style="margin-right: auto; margin-left: auto; vertical-align: middle;" align="center">
<p><strong><span style="font-size: 18px;">BOSCH</span></strong><br /><span style="font-size: 15px;">BOMBAS<br /></span>A<br /> B <br /> P <br /> S&Eacute;RIE 7000<br /> S&Eacute;RIE 7100</p>
</td>
</tr>
</tbody>
</table>
</p>
<p style="text-align: center;">&nbsp;</p>
<p style="text-align: center;">&nbsp;</p>
<div style="position: absolute; left: -40px; top: -25px; width: 1px; height: 1px; overflow: hidden; text-align: center;" data-mce-bogus="1" class="mcePaste" id="_mcePaste"><!--[if !mso]>

<![endif]--><span style="font-size: 11.0pt; line-height: 107%; font-family: 'Calibri',sans-serif; mso-fareast-font-family: Calibri; mso-bidi-font-family: 'Times New Roman'; mso-ansi-language: PT-BR; mso-fareast-language: EN-US; mso-bidi-language: AR-SA;"><img src="file:///C:\Users\Douglas\AppData\Local\Temp\msohtmlclip1\01\clip_image002.jpg" width="359" height="263" /></span><!--[if gte mso 9]><xml>
 <o:OfficeDocumentSettings>
  <o:TargetScreenSize>800x600</o:TargetScreenSize>
 </o:OfficeDocumentSettings>
</xml><![endif]--><!--[if gte mso 9]><xml>
 <w:WordDocument>
  <w:View>Normal</w:View>
  <w:Zoom>0</w:Zoom>
  <w:TrackMoves/>
  <w:TrackFormatting/>
  <w:HyphenationZone>21</w:HyphenationZone>
  <w:PunctuationKerning/>
  <w:ValidateAgainstSchemas/>
  <w:SaveIfXMLInvalid>false</w:SaveIfXMLInvalid>
  <w:IgnoreMixedContent>false</w:IgnoreMixedContent>
  <w:AlwaysShowPlaceholderText>false</w:AlwaysShowPlaceholderText>
  <w:DoNotPromoteQF/>
  <w:LidThemeOther>PT-BR</w:LidThemeOther>
  <w:LidThemeAsian>X-NONE</w:LidThemeAsian>
  <w:LidThemeComplexScript>X-NONE</w:LidThemeComplexScript>
  <w:Compatibility>
   <w:BreakWrappedTables/>
   <w:SnapToGridInCell/>
   <w:WrapTextWithPunct/>
   <w:UseAsianBreakRules/>
   <w:DontGrowAutofit/>
   <w:SplitPgBreakAndParaMark/>
   <w:EnableOpenTypeKerning/>
   <w:DontFlipMirrorIndents/>
   <w:OverrideTableStyleHps/>
  </w:Compatibility>
  <w:BrowserLevel>MicrosoftInternetExplorer4</w:BrowserLevel>
  <m:mathPr>
   <m:mathFont m:val="Cambria Math"/>
   <m:brkBin m:val="before"/>
   <m:brkBinSub m:val="&#45;-"/>
   <m:smallFrac m:val="off"/>
   <m:dispDef/>
   <m:lMargin m:val="0"/>
   <m:rMargin m:val="0"/>
   <m:defJc m:val="centerGroup"/>
   <m:wrapIndent m:val="1440"/>
   <m:intLim m:val="subSup"/>
   <m:naryLim m:val="undOvr"/>
  </m:mathPr></w:WordDocument>
</xml><![endif]--><!--[if gte mso 9]><xml>
 <w:LatentStyles DefLockedState="false" DefUnhideWhenUsed="false"
  DefSemiHidden="false" DefQFormat="false" DefPriority="99"
  LatentStyleCount="371">
  <w:LsdException Locked="false" Priority="0" QFormat="true" Name="Normal"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 1"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 2"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 3"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 4"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 5"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 6"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 7"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 8"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 9"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 7"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 8"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 9"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 1"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 2"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 3"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 4"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 5"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 6"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 7"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 8"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 9"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Normal Indent"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="footnote text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="annotation text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="header"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="footer"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index heading"/>
  <w:LsdException Locked="false" Priority="35" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="caption"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="table of figures"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="envelope address"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="envelope return"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="footnote reference"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="annotation reference"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="line number"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="page number"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="endnote reference"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="endnote text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="table of authorities"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="macro"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="toa heading"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 5"/>
  <w:LsdException Locked="false" Priority="10" QFormat="true" Name="Title"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Closing"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Signature"/>
  <w:LsdException Locked="false" Priority="1" SemiHidden="true"
   UnhideWhenUsed="true" Name="Default Paragraph Font"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text Indent"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Message Header"/>
  <w:LsdException Locked="false" Priority="11" QFormat="true" Name="Subtitle"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Salutation"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Date"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text First Indent"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text First Indent 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Note Heading"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text Indent 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text Indent 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Block Text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Hyperlink"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="FollowedHyperlink"/>
  <w:LsdException Locked="false" Priority="22" QFormat="true" Name="Strong"/>
  <w:LsdException Locked="false" Priority="20" QFormat="true" Name="Emphasis"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Document Map"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Plain Text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="E-mail Signature"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Top of Form"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Bottom of Form"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Normal (Web)"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Acronym"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Address"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Cite"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Code"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Definition"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Keyboard"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Preformatted"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Sample"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Typewriter"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Variable"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Normal Table"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="annotation subject"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="No List"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Outline List 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Outline List 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Outline List 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Simple 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Simple 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Simple 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Colorful 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Colorful 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Colorful 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 7"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 8"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 7"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 8"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table 3D effects 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table 3D effects 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table 3D effects 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Contemporary"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Elegant"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Professional"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Subtle 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Subtle 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Web 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Web 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Web 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Balloon Text"/>
  <w:LsdException Locked="false" Priority="39" Name="Table Grid"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Theme"/>
  <w:LsdException Locked="false" SemiHidden="true" Name="Placeholder Text"/>
  <w:LsdException Locked="false" Priority="1" QFormat="true" Name="No Spacing"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 1"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 1"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 1"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 1"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 1"/>
  <w:LsdException Locked="false" SemiHidden="true" Name="Revision"/>
  <w:LsdException Locked="false" Priority="34" QFormat="true"
   Name="List Paragraph"/>
  <w:LsdException Locked="false" Priority="29" QFormat="true" Name="Quote"/>
  <w:LsdException Locked="false" Priority="30" QFormat="true"
   Name="Intense Quote"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 1"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 1"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 1"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 1"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 1"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 2"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 2"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 2"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 2"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 2"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 2"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 2"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 3"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 3"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 3"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 3"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 3"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 3"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 3"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 4"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 4"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 4"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 4"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 4"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 4"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 4"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 5"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 5"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 5"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 5"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 5"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 5"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 5"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 6"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 6"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 6"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 6"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 6"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 6"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 6"/>
  <w:LsdException Locked="false" Priority="19" QFormat="true"
   Name="Subtle Emphasis"/>
  <w:LsdException Locked="false" Priority="21" QFormat="true"
   Name="Intense Emphasis"/>
  <w:LsdException Locked="false" Priority="31" QFormat="true"
   Name="Subtle Reference"/>
  <w:LsdException Locked="false" Priority="32" QFormat="true"
   Name="Intense Reference"/>
  <w:LsdException Locked="false" Priority="33" QFormat="true" Name="Book Title"/>
  <w:LsdException Locked="false" Priority="37" SemiHidden="true"
   UnhideWhenUsed="true" Name="Bibliography"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="TOC Heading"/>
  <w:LsdException Locked="false" Priority="41" Name="Plain Table 1"/>
  <w:LsdException Locked="false" Priority="42" Name="Plain Table 2"/>
  <w:LsdException Locked="false" Priority="43" Name="Plain Table 3"/>
  <w:LsdException Locked="false" Priority="44" Name="Plain Table 4"/>
  <w:LsdException Locked="false" Priority="45" Name="Plain Table 5"/>
  <w:LsdException Locked="false" Priority="40" Name="Grid Table Light"/>
  <w:LsdException Locked="false" Priority="46" Name="Grid Table 1 Light"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark"/>
  <w:LsdException Locked="false" Priority="51" Name="Grid Table 6 Colorful"/>
  <w:LsdException Locked="false" Priority="52" Name="Grid Table 7 Colorful"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 1"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 1"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 1"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 2"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 2"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 2"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 3"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 3"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 3"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 4"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 4"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 4"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 5"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 5"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 5"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 6"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 6"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 6"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 6"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 6"/>
  <w:LsdException Locked="false" Priority="46" Name="List Table 1 Light"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark"/>
  <w:LsdException Locked="false" Priority="51" Name="List Table 6 Colorful"/>
  <w:LsdException Locked="false" Priority="52" Name="List Table 7 Colorful"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 1"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 1"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 1"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 2"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 2"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 2"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 3"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 3"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 3"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 4"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 4"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 4"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 5"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 5"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 5"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 6"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 6"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 6"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 6"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 6"/>
 </w:LatentStyles>
</xml><![endif]--><!--[if gte mso 10]>

<![endif]--></div>								</p>
							</li>
													<li data-icon="icon-database" data-title="Bancada de teste BOSCH">
								<p>
									<p><img style="float: left;" alt="Bancada de teste BOSCH " src="/images/Bancada_de_teste_BOSCH_.jpg" /><span style="font-size: 20px;">Bancada de teste BOSCH modelo EP 615 Ano 2010</span></p>
<p>&nbsp;</p>								</p>
							</li>
													<li data-icon="icon-resize-small-alt" data-title="Bancada de teste SPEEDMAQ">
								<p>
									<p><img style="float: left;" alt="Bancada de teste SPEEDMAQ" src="/images/Bancada_de_teste_SPEEDMAQ.jpg" /><span style="font-size: 20px;">Bancada de teste SPEEDMAQ modelo SX 108 Ano 98 (Homologada pela DELPHI)</span></p>
<p>&nbsp;</p>								</p>
							</li>
							
						</ul>
					</div><!--/ .flexslider-->	
				</div>
			</div><!--/ .row-->
		</div><!--/ .container-->
	</section><!--/ .section-->
</section><!--/ .page--> <section id="contacts" class="page"><section class="section padding-bottom-off"><div class="container"><div class="row"><div class="col-xs-12"><hgroup class="section-title align-center opacity"><h1>Contato</h1><h2>Entre em contato conosco, estamos sempre de prontos para lhe fornecer o melhor atendimento</h2></hgroup></div></div><!--/ .row--></div><!--/ .container--></section><!--/ .section--> <!--/ .section--></section><!--/ .page--><div id="map_canvas" class="map rounded " style="width:100%;height:300px;"></div>

<footer id="footer" class="">
	<section class="section parallax parallax-bg-4">
		<div class="full-bg-image" style="background-image: url('/images/parallax/parallax-4.jpg');)"></div>
		<div class="container_footer">
									<div class="st-module module col-md-6" id="Mod117">
	<div class="module-inner">
					<h3 class="module-title">
				<span>Entre em contato conosco</span>
			</h3>
				<div class="module-ct">
			<section id="contact">
	<script type="text/javascript">
		 var RecaptchaOptions = {
			theme : "white"
		 };
	 </script>
	<form action="/" method="POST" class="form-horizontal" id="contact-form" novalidate>
	  <input type='hidden' name='form_key' id='form_key' value='9af3e9ad06594994ec02a33d7d5579af' />	  <fieldset>
		<!-- Alert Box-->
				
				
		<!-- Name Field -->
		  <div class="control-group">
			<label class="control-label" for="inputName">Digite seu nome</label>
			<div class="controls">
			  <input class="input-80" name="name" type="text" id="inputName" placeholder="Digite seu nome" required>
			  <p class="help-block"></p>
			</div>
		  </div>
		 
		 <!-- E-mail Field -->
		  			  
		  <div class="control-group">
			<label class="control-label" for="inputEmail">Digite seu e-mail</label>
			<div class="controls">
			  <input class="input-80" name="email" type="email" id="inputEmail" placeholder="Digite seu e-mail" required>
			  <p class="help-block"></p>
			</div>
		  </div>
		  		  
		  <!-- Phone Field -->
		  <div class="control-group">
			<label class="control-label" for="inputPhone">Digite seu telefone</label>
			<div class="controls">
			  <input class="input-80" name="phone" type="text" id="inputPhone" placeholder="Digite seu telefone"  >
			  <p class="help-block"></p>
			</div>
		  </div>
		  		 
		 <!-- Subject Field -->
		  <div class="control-group">
			<label class="control-label" for="selectSubject">Assunto</label>
			<div class="controls">
										<input class="input-80" name="type" type="text" id="selectSubject" placeholder="Assunto" required>
						<p class="help-block"></p>
							</div>
		  </div>
		  		 
		 <!-- Message Field -->
		  <div class="control-group">
			<label class="control-label" for="inputMessage">Mensagem</label>
			<div class="controls">
			  <textarea class="input-80" name="message" rows="12" id="inputMessage" placeholder="Digite sua mensagem" minlength="0" required></textarea>
			  <p class="help-block"></p>
			</div>
		  </div>
		  		 
		 <!-- Captcha Field -->
		  <div class="control-group">
			<label class="control-label" for="recaptcha">Você é humano?</label>
			<div class="controls" id="recaptcha">
				<p>
					<script type="text/javascript" src="http://www.google.com/recaptcha/api/challenge?k=6LfUEAgTAAAAANjWjWQIOXNDhGJp0OILw9R14lLb"></script>

	<noscript>
  		<iframe src="http://www.google.com/recaptcha/api/noscript?k=6LfUEAgTAAAAANjWjWQIOXNDhGJp0OILw9R14lLb" height="300" width="500" frameborder="0"></iframe><br/>
  		<textarea name="recaptcha_challenge_field" rows="3" cols="40"></textarea>
  		<input type="hidden" name="recaptcha_response_field" value="manual_challenge"/>
	</noscript>				</p>
			</div>
		  </div> 
		  		 
		 <!-- Submit Button -->
		  <div class="control-group">
			<div class="controls">
			  <button type="submit" name="sbutton" value="Send" class="btn btn-danger">Enviar</button>
			</div>
		  </div>
		  		</fieldset>
	</form>
</section>		</div>
	</div>
</div> <div class="col-md-6"><div class="widget widget_text opacity"><p>Entre em contato conosco. Deixe sua mensagem para agendar uma reserva, tirar uma dúvida, etc. Retornaremos sua mensagem o mais rápido possível.</p></div><!--/ .widget--><div class="widget widget_contacts opacity"><ul class="contact-details"><li>Endereço: Avenida Rio Bahia n.º 5935 BR 116 Km 708, Bairro Gaspar Muriaé-MG Cep: 36.880.000</li><li>Telefone: (32) 3721-5202</li><li>E-mail: contato@hevandiesel.com.br</li></ul><!--/ .contact-details--></div><!--/ .widget--><div class="widget widget_social opacity"><ul class="social-icons"><li class="facebook"><a href="#" data-mce-href="#"><i class="icon-facebook" data-mce-bootstrap="1">&nbsp;</i>Facebook</a><br data-mce-bogus="1"></li><li class="linkedin"><a href="#" data-mce-href="#"><i class="icon-linkedin" data-mce-bootstrap="1">&nbsp;</i>LinkedIn</a><br data-mce-bogus="1"></li><li class="gplus"><a href="#" data-mce-href="#"><i class="icon-gplus" data-mce-bootstrap="1">&nbsp;</i>Gplus</a><br data-mce-bogus="1"></li><li class="youtube"><a href="#" data-mce-href="#"><i class="icon-youtube" data-mce-bootstrap="1">&nbsp;</i>Youtube</a><br data-mce-bogus="1"></li></ul><!--/ .social-icons--></div><!--/ .widget--></div>   						</div><!--/ .container-->
	</section><!--/ .section-->
</footer><!--/ #footer-->
<div class="st-module module" id="Mod108">
	<div class="module-inner">
				<div class="module-ct">
			

<div class="custom none_bg"  >
	<div class="bottom-footer clearfix">
<div class="container">
<div class="row">
<div class="col-sm-6">
<div class="copyright">Copyright © 2018 Hevan Diesel. Todos os direitos reservados.</div>
<!--/ .cppyright--></div>
<div class="col-sm-3 col-sm-offset-3">
</div>
<!--/ .row--></div>
<!--/ .container--></div>
<!--/ .bottom-footer--></div>
		</div>
	</div>
</div>         
		<!-- End Content -->
        	</div><!--/ #wrapper-->

</body>
</html>
