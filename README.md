- π Hi, Iβm @turner0166
- π Iβm interested in ...
- π± Iβm currently learning ...
- ποΈ Iβm looking to collaborate on ...
- π« How to reach me ...

<!---
turner0166/turner0166 is a β¨ special β¨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Skip to content
Search or jump toβ¦
Pull requests
Issues
Marketplace
Explore
 
@turner0166 
SamueleA
/
wordpress-fleek
Public
2
110
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
wordpress-fleek/index.html
@SamueleA
SamueleA new article
Latest commit 015c488 on 20 Apr 2020
 History
 1 contributor
689 lines (485 sloc)  27 KB
  
<!DOCTYPE html>
<html lang="en-US">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width">


<title>Code Climbing β Samuele Agostinelli's Blog β Reaching the Heights</title>
<link rel="dns-prefetch" href="//fonts.googleapis.com">
<link rel="dns-prefetch" href="//s.w.org">
<link href="https://fonts.gstatic.com" crossorigin rel="preconnect">



<script type="text/javascript" data-cfasync="false">
	var mi_version         = '7.10.4';
	var mi_track_user      = true;
	var mi_no_track_reason = '';
	
	var disableStr = 'ga-disable-UA-40477212-4';

	/* Function to detect opted out users */
	function __gaTrackerIsOptedOut() {
		return document.cookie.indexOf(disableStr + '=true') > -1;
	}

	/* Disable tracking if the opt-out cookie exists. */
	if ( __gaTrackerIsOptedOut() ) {
		window[disableStr] = true;
	}

	/* Opt-out function */
	function __gaTrackerOptout() {
	  document.cookie = disableStr + '=true; expires=Thu, 31 Dec 2099 23:59:59 UTC; path=/';
	  window[disableStr] = true;
	}
	
	if ( mi_track_user ) {
		(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
			(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
			m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
		})(window,document,'script','//www.google-analytics.com/analytics.js','__gaTracker');

		__gaTracker('create', 'UA-40477212-4', 'auto');
		__gaTracker('set', 'forceSSL', true);
		__gaTracker('require', 'displayfeatures');
		__gaTracker('send','pageview');
	} else {
		console.log( "" );
		(function() {
			/* https://developers.google.com/analytics/devguides/collection/analyticsjs/ */
			var noopfn = function() {
				return null;
			};
			var noopnullfn = function() {
				return null;
			};
			var Tracker = function() {
				return null;
			};
			var p = Tracker.prototype;
			p.get = noopfn;
			p.set = noopfn;
			p.send = noopfn;
			var __gaTracker = function() {
				var len = arguments.length;
				if ( len === 0 ) {
					return;
				}
				var f = arguments[len-1];
				if ( typeof f !== 'object' || f === null || typeof f.hitCallback !== 'function' ) {
					console.log( 'Not running function __gaTracker(' + arguments[0] + " ....) because you are not being tracked. " + mi_no_track_reason );
					return;
				}
				try {
					f.hitCallback();
				} catch (ex) {

				}
			};
			__gaTracker.create = function() {
				return new Tracker();
			};
			__gaTracker.getByName = noopnullfn;
			__gaTracker.getAll = function() {
				return [];
			};
			__gaTracker.remove = noopfn;
			window['__gaTracker'] = __gaTracker;
					})();
		}
</script>

<style type="text/css" id="kt_global_css_variables">
:root {
  --Denim: #1B6AC1;
  --PictonBlue: #63B0E4;
}
</style>
<link rel="stylesheet" id="wp-block-library-css" href="wp-includes/css/dist/block-library/style.min.css" type="text/css" media="all">
<link rel="stylesheet" id="wp-block-library-theme-css" href="wp-includes/css/dist/block-library/theme.min.css" type="text/css" media="all">
<link rel="stylesheet" id="mc4wp-form-themes-css" href="wp-content/plugins/mailchimp-for-wp/assets/css/form-themes.min.css" type="text/css" media="all">
<link rel="stylesheet" id="ribosome-fonts-css" href="https://fonts.googleapis.com/css?family=Open+Sans:400italic,700italic,400,700&subset=latin,latin-ext" type="text/css" media="all">
<link rel="stylesheet" id="ribosome-style-css" href="wp-content/themes/ribosome/style.css" type="text/css" media="all">
<link rel="stylesheet" id="ribosome-block-style-css" href="wp-content/themes/ribosome/css/blocks.css" type="text/css" media="all">

<link rel="stylesheet" id="dashicons-css" href="wp-includes/css/dashicons.min.css" type="text/css" media="all">
<link rel="stylesheet" id="font-awesome-css" href="wp-content/themes/ribosome/css/font-awesome-4.7.0/css/font-awesome.min.css" type="text/css" media="all">
<style id="kt_central_palette_gutenberg_css" type="text/css">.has-central-palette-1-color{color:#1B6AC1}.has-central-palette-1-background-color{background-color:#1B6AC1}.has-central-palette-2-color{color:#63B0E4}.has-central-palette-2-background-color{background-color:#63B0E4}
</style>
<script type="text/javascript">
/* <![CDATA[ */
var monsterinsights_frontend = {"js_events_tracking":"true","download_extensions":"doc,pdf,ppt,zip,xls,docx,pptx,xlsx","inbound_paths":"[{\"path\":\"\\\/go\\\/\",\"label\":\"affiliate\"},{\"path\":\"\\\/recommend\\\/\",\"label\":\"affiliate\"}]","home_url":"http:\/\/PLACEHOLDER.wpsho","hash_tracking":"false"};
/* ]]> */
</script>
<script type="text/javascript" src="wp-content/plugins/google-analytics-for-wordpress/assets/js/frontend.min.js"></script>
<script type="text/javascript" src="wp-includes/js/jquery/jquery.js"></script>
<script type="text/javascript" src="wp-includes/js/jquery/jquery-migrate.min.js"></script>



	<style type="text/css">
		a {color: #0073AA;}
	a:hover {color: #0073AA;}
	.social-icon-wrapper a:hover {color: #0073AA;}
	.toggle-search {color: #0073AA;}
	.prefix-widget-title {color: #0073AA;}
	.sub-title a:hover {color:#0073AA;}
	.entry-content a:visited,.comment-content a:visited {color:#0073AA;}
	button, input[type="submit"], input[type="button"], input[type="reset"] {background-color:#0073AA !important;}
	.bypostauthor cite span {background-color:#0073AA;}
	.entry-header .entry-title a:hover {color:#0073AA ;}
	.archive-header {border-left-color:#0073AA;}
	.main-navigation .current-menu-item > a,
	.main-navigation .current-menu-ancestor > a,
	.main-navigation .current_page_item > a,
	.main-navigation .current_page_ancestor > a {color: #0073AA;}
	.main-navigation li a:hover  {color: #0073AA;}

	.widget-area .widget a:hover {
		color: #0073AA !important;
	}
	footer[role="contentinfo"] a:hover {
		color: #0073AA;
	}
	.author-info a {color: #0073AA;}
	.entry-meta a:hover {
	color: #0073AA;
	}
	.format-status .entry-header header a:hover {
		color: #0073AA;
	}
	.comments-area article header a:hover {
		color: #0073AA;
	}
	a.comment-reply-link:hover,
	a.comment-edit-link:hover {
		color: #0073AA;
	}
	.currenttext, .paginacion a:hover {background-color:#0073AA;}
	.aside{border-left-color:#0073AA !important;}
	blockquote{border-left-color:#0073AA;}
	.logo-header-wrapper{background-color:#0073AA;}
	h3.cabeceras-fp {border-bottom-color:#0073AA;}
	.encabezados-front-page {background-color:#0073AA;}
	.icono-caja-destacados {color: #0073AA;}
	.enlace-caja-destacados:hover {background-color: #0073AA;}
	h2.comments-title {border-left-color:#0073AA;}
	/* Gutenberg */
	.has-theme-color-color,
	a.has-theme-color-color:hover {
		color: #0073AA;
	}
	.has-theme-color-background-color {
		background-color:#0073AA;
	}

	
			.blog-info-sin-imagen {background-color: #0073AA;}
	
			.widget-title-tab{
			background-color:#0073AA;
			color:#fff;
		}
		.widget-title-tab a.rsswidget{color:#fff !important;}
		h3.widget-title { border-bottom:2px solid #0073AA;}
	
	
			.main-navigation {border-top:2px solid #0073AA}
	
			.logo-header-wrapper {
			padding: 21px 14px;
			padding: 1.5rem 1rem;
		}
	
	
	
	
		body.custom-font-enabled {font-family: "Open Sans", Arial, Verdana;}

			@media screen and (min-width: 768px) {
			#primary {float:left;}
			#secondary {float:right;}
			.site-content {
				border-left: none;
				padding-left:0;
				padding-right: 24px;
				padding-right:1.714285714285714rem;
			}

		}
		@media screen and (min-width: 960px) {
			.site-content {
				border-right: 1px solid #e0e0e0;
			}
		}
	
	@media screen and (min-width: 768px) {
			.excerpt-wrapper{border-left:2px solid #0073AA;}
	
	
		}
	</style>

	<style type="text/css" id="ribosome-header-css">
			.site-header h1 a,
		.site-header h2 {
			color: #eaeaea;
		}
		</style>
	<style type="text/css" id="custom-background-css">
body.custom-background { background-color: #afafaf; }
</style>
	<link rel="icon" href="wp-content/uploads/2020/03/cropped-favicon-32x32.png" sizes="32x32">
<link rel="icon" href="wp-content/uploads/2020/03/cropped-favicon-192x192.png" sizes="192x192">
<link rel="apple-touch-icon" href="wp-content/uploads/2020/03/cropped-favicon-180x180.png">
<meta name="msapplication-TileImage" content="wp-content/uploads/2020/03/cropped-favicon-270x270.png">
		<style type="text/css" id="wp-custom-css">
			.logo-header-wrapper {
	background-color: black;
	max-height: 300px;
	padding: 0;
	padding-top: 10px;
}

.header-image {
	width: auto;
	max-height: 300px
}		</style>
		</head>

<body class="home blog custom-background wp-embed-responsive custom-font-enabled single-author">

<div id="page" class="hfeed site">

	<header id="masthead" class="site-header" role="banner">

		<div class="top-bar">
		
		<div class="boton-menu-movil"><i class="fa fa-align-justify"></i></div>

		
		<div class="toggle-search"><i class="fa fa-search"></i></div>
		<div class="social-icon-wrapper">
			
			
			
			
			
			
			
			
					</div>
	</div>

	<div class="wrapper-search-top-bar">
		<div class="search-top-bar">
				<div>
		<form method="get" id="searchform-toggle" action="http://OFFLINEZIP.wpsho/">
			<label for="s" class="assistive-text">Search</label>
			<input type="search" class="txt-search" name="s" id="s">
			<input type="submit" name="submit" id="btn-search" value="Search">
		</form>
    </div>		</div>
	</div>
			<div style="position:relative">
				
<div id="menu-movil">
	<div class="search-form-movil">
		<form method="get" id="searchform-movil" action="http://OFFLINEZIP.wpsho/">
			<label for="s" class="assistive-text">Search</label>
			<input type="search" class="txt-search-movil" placeholder="Search..." name="s" id="s">
			<input type="submit" name="submit" id="btn-search-movil" value="Search">
		</form>
	</div>
	<div class="menu-movil-enlaces">
		<div class="nav-menu"><ul>
<li class="current_page_item"><a href="">Home</a></li><li class="page_item page-item-11"><a href="contact/index.html">Contact</a></li>
</ul></div>
	</div>

	<div class="social-icon-wrapper-movil">
			
			
			
			
			
			
			
			
					</div>	
</div>
			</div>
			<div class="logo-header-wrapper" style="text-align:center;">
			<a href=""><img src="wp-content/uploads/2020/03/cropped-Code-Climbing-scaled-2.jpg" class="header-image" width="2000" height="1034" alt="Code Climbing"></a>
			</div>

			
		<nav id="site-navigation" class="main-navigation" role="navigation">
			<a class="assistive-text" href="#content" title="Skip to content">Skip to content</a>
			<div class="nav-menu"><ul>
<li class="current_page_item"><a href="">Home</a></li><li class="page_item page-item-11"><a href="contact/index.html">Contact</a></li>
</ul></div>
		</nav>

	</header>

	<div id="main" class="wrapper">

	<div id="primary" class="site-content">
		<div id="content" role="main">
		
										
	<article id="post-97" class="post-97 post type-post status-publish format-standard has-post-thumbnail hentry category-general">
		
		
		
					<div class="excerpt-wrapper">

										<a href="how-to-visit-ens-enabled-websites-your-gateway-to-web3/index.html" title="How to Visit ENS-enabled Websites! Your Gateway to Web3" rel="bookmark">
							<div class="wrapper-excerpt-thumbnail">
								<img width="240" height="180" src="wp-content/uploads/2020/04/Screenshot-from-2020-04-19-18-39-00-240x180.png" class="attachment-ribosome-excerpt-thumbnail size-ribosome-excerpt-thumbnail wp-post-image" alt="ens">							</div>
						</a>
				
				<header class="entry-header">
					<h2 class="entry-title">
					<a href="how-to-visit-ens-enabled-websites-your-gateway-to-web3/index.html" rel="bookmark">How to Visit ENS-enabled Websites! Your Gateway to Web3</a>
					</h2>
									</header>

				<p>ENS stands for Ethereum Naming System and is a blockchain-powered DNS. ENS domains end in .eth. For example, this site is codeclimbing.com using a traditional DNS, but there is alsoβ¦ <a href="how-to-visit-ens-enabled-websites-your-gateway-to-web3/index.html">Read more Β»</a></p>

			</div>

		
		<footer class="entry-meta">
			
			
							<div class="entry-meta-term-excerpt">
				
				<span class="entry-meta-categories"><span class="term-icon"><i class="fa fa-folder-open"></i></span> <a href="category/general/index.html" rel="tag">General</a>   </span>

				
				<div style="float:right;"></div>
			</div>

					</footer>
	</article>
							
	<article id="post-91" class="post-91 post type-post status-publish format-standard has-post-thumbnail hentry category-general">
		
		
		
					<div class="excerpt-wrapper">

										<a href="whats-in-a-cid-multi-multi-multi/index.html" title="Whatβs in a CID? Multi, Multi, Multiβ¦" rel="bookmark">
							<div class="wrapper-excerpt-thumbnail">
								<img width="240" height="180" src="wp-content/uploads/2020/04/white-product-label-1111319-240x180.jpg" class="attachment-ribosome-excerpt-thumbnail size-ribosome-excerpt-thumbnail wp-post-image" alt="content-identifier">							</div>
						</a>
				
				<header class="entry-header">
					<h2 class="entry-title">
					<a href="whats-in-a-cid-multi-multi-multi/index.html" rel="bookmark">Whatβs in a CID? Multi, Multi, Multiβ¦</a>
					</h2>
									</header>

				<p>Every piece of data on IPFS can be referenced through its CID, which stands for Content IDentifier. You might have have spotted some while navigating the IPFS jungle. They lookβ¦ <a href="whats-in-a-cid-multi-multi-multi/index.html">Read more Β»</a></p>

			</div>

		
		<footer class="entry-meta">
			
			
							<div class="entry-meta-term-excerpt">
				
				<span class="entry-meta-categories"><span class="term-icon"><i class="fa fa-folder-open"></i></span> <a href="category/general/index.html" rel="tag">General</a>   </span>

				
				<div style="float:right;"></div>
			</div>

					</footer>
	</article>
							
	<article id="post-84" class="post-84 post type-post status-publish format-standard has-post-thumbnail hentry category-docker tag-automation tag-builds tag-docker tag-docker-hub">
		
		
		
					<div class="excerpt-wrapper">

										<a href="automate-your-builds-on-docker-hub-by-writing-a-build-hook-script/index.html" title="Automate your Builds on Docker Hub by Writing a Build Hook Script!" rel="bookmark">
							<div class="wrapper-excerpt-thumbnail">
								<img width="240" height="180" src="wp-content/uploads/2020/04/dockerhub-240x180.png" class="attachment-ribosome-excerpt-thumbnail size-ribosome-excerpt-thumbnail wp-post-image" alt="">							</div>
						</a>
				
				<header class="entry-header">
					<h2 class="entry-title">
					<a href="automate-your-builds-on-docker-hub-by-writing-a-build-hook-script/index.html" rel="bookmark">Automate your Builds on Docker Hub by Writing a Build Hook Script!</a>
					</h2>
									</header>

				<p>Docker Hub is like Github for Docker images, making all our lives way easier. Yet, it can quickly become a nightmare to maintaining multiple docker images. We donβt want toβ¦ <a href="automate-your-builds-on-docker-hub-by-writing-a-build-hook-script/index.html">Read more Β»</a></p>

			</div>

		
		<footer class="entry-meta">
			
			
							<div class="entry-meta-term-excerpt">
				
				<span class="entry-meta-categories"><span class="term-icon"><i class="fa fa-folder-open"></i></span> <a href="category/docker/index.html" rel="tag">Docker</a>   </span>

									<span class="entry-meta-tags"><span class="term-icon"><i class="fa fa-tags"></i></span> <a href="tag/automation/index.html" rel="tag">automation</a>, <a href="tag/builds/index.html" rel="tag">builds</a>, <a href="tag/docker/index.html" rel="tag">docker</a>, <a href="tag/docker-hub/index.html" rel="tag">docker hub</a></span>
					
				<div style="float:right;"></div>
			</div>

					</footer>
	</article>
							
	<article id="post-60" class="post-60 post type-post status-publish format-standard has-post-thumbnail hentry category-docker tag-docker tag-tutorial">
		
		
		
					<div class="excerpt-wrapper">

										<a href="docker-for-newbz-create-a-docker-image-for-your-app/index.html" title="Docker for Newbz: Create a Docker Image for Your App!" rel="bookmark">
							<div class="wrapper-excerpt-thumbnail">
								<img width="240" height="180" src="wp-content/uploads/2020/03/1_9hGvYE5jegHm1r_97gH-jQ-240x180.png" class="attachment-ribosome-excerpt-thumbnail size-ribosome-excerpt-thumbnail wp-post-image" alt="">							</div>
						</a>
				
				<header class="entry-header">
					<h2 class="entry-title">
					<a href="docker-for-newbz-create-a-docker-image-for-your-app/index.html" rel="bookmark">Docker for Newbz: Create a Docker Image for Your App!</a>
					</h2>
									</header>

				<p>Every programmer dreads the phrase: βBut it works on my machine!!!β Our poor developer now knows that he must now figure out whatβs wrong among a bazillion things. βOkay, soβ¦ <a href="docker-for-newbz-create-a-docker-image-for-your-app/index.html">Read more Β»</a></p>

			</div>

		
		<footer class="entry-meta">
			
			
							<div class="entry-meta-term-excerpt">
				
				<span class="entry-meta-categories"><span class="term-icon"><i class="fa fa-folder-open"></i></span> <a href="category/docker/index.html" rel="tag">Docker</a>   </span>

									<span class="entry-meta-tags"><span class="term-icon"><i class="fa fa-tags"></i></span> <a href="tag/docker/index.html" rel="tag">docker</a>, <a href="tag/tutorial/index.html" rel="tag">tutorial</a></span>
					
				<div style="float:right;"></div>
			</div>

					</footer>
	</article>
							
	<article id="post-42" class="post-42 post type-post status-publish format-standard has-post-thumbnail hentry category-ipfs tag-decentralisation tag-ipfs">
		
		
		
					<div class="excerpt-wrapper">

										<a href="the-ipfs-holy-grail-part-2-decentralisation-and-censorship-resistance/index.html" title="The IPFS Holy Grail Part 2: Decentralisation and Censorship Resistance" rel="bookmark">
							<div class="wrapper-excerpt-thumbnail">
								<img width="240" height="160" src="wp-content/uploads/2020/03/abstract-art-blur-bright-373543-1-scaled.jpg" class="attachment-ribosome-excerpt-thumbnail size-ribosome-excerpt-thumbnail wp-post-image" alt="" srcset="wp-content/uploads/2020/03/abstract-art-blur-bright-373543-1-scaled.jpg 2560w,wp-content/uploads/2020/03/abstract-art-blur-bright-373543-1-300x200.jpg 300w,wp-content/uploads/2020/03/abstract-art-blur-bright-373543-1-1024x683.jpg 1024w,wp-content/uploads/2020/03/abstract-art-blur-bright-373543-1-768x512.jpg 768w,wp-content/uploads/2020/03/abstract-art-blur-bright-373543-1-1536x1024.jpg 1536w" sizes="(max-width: 240px) 100vw, 240px">							</div>
						</a>
				
				<header class="entry-header">
					<h2 class="entry-title">
					<a href="the-ipfs-holy-grail-part-2-decentralisation-and-censorship-resistance/index.html" rel="bookmark">The IPFS Holy Grail Part 2: Decentralisation and Censorship Resistance</a>
					</h2>
									</header>

				<p>This is the second and last part in a discussion of how IPFS plans to fix the internetβs biggest problems.In the previous part, weβve discussed how IFPS makes the webβ¦ <a href="the-ipfs-holy-grail-part-2-decentralisation-and-censorship-resistance/index.html">Read more Β»</a></p>

			</div>

		
		<footer class="entry-meta">
			
			
							<div class="entry-meta-term-excerpt">
				
				<span class="entry-meta-categories"><span class="term-icon"><i class="fa fa-folder-open"></i></span> <a href="category/ipfs/index.html" rel="tag">IPFS</a>   </span>

									<span class="entry-meta-tags"><span class="term-icon"><i class="fa fa-tags"></i></span> <a href="tag/decentralisation/index.html" rel="tag">decentralisation</a>, <a href="tag/ipfs/index.html" rel="tag">IPFS</a></span>
					
				<div style="float:right;"></div>
			</div>

					</footer>
	</article>
							
	<article id="post-36" class="post-36 post type-post status-publish format-standard has-post-thumbnail hentry category-ipfs tag-internet tag-ipfs tag-security tag-web">
		
		
		
					<div class="excerpt-wrapper">

										<a href="the-ipfs-holy-grail-part-1-a-more-secure-and-efficient-internet/index.html" title="The IPFS Holy Grail Part 1: A More Secure and Efficient Internet" rel="bookmark">
							<div class="wrapper-excerpt-thumbnail">
								<img width="240" height="180" src="wp-content/uploads/2020/03/evening-567840_1920-240x180.jpg" class="attachment-ribosome-excerpt-thumbnail size-ribosome-excerpt-thumbnail wp-post-image" alt="">							</div>
						</a>
				
				<header class="entry-header">
					<h2 class="entry-title">
					<a href="the-ipfs-holy-grail-part-1-a-more-secure-and-efficient-internet/index.html" rel="bookmark">The IPFS Holy Grail Part 1: A More Secure and Efficient Internet</a>
					</h2>
									</header>

				<p>Last week weβve discussed some of the problems related to our current iteration of the internet. It was pretty doom and gloom, but now weβll discuss what IPFS will doβ¦ <a href="the-ipfs-holy-grail-part-1-a-more-secure-and-efficient-internet/index.html">Read more Β»</a></p>

			</div>

		
		<footer class="entry-meta">
			
			
							<div class="entry-meta-term-excerpt">
				
				<span class="entry-meta-categories"><span class="term-icon"><i class="fa fa-folder-open"></i></span> <a href="category/ipfs/index.html" rel="tag">IPFS</a>   </span>

									<span class="entry-meta-tags"><span class="term-icon"><i class="fa fa-tags"></i></span> <a href="tag/internet/index.html" rel="tag">internet</a>, <a href="tag/ipfs/index.html" rel="tag">IPFS</a>, <a href="tag/security/index.html" rel="tag">security</a>, <a href="tag/web/index.html" rel="tag">web</a></span>
					
				<div style="float:right;"></div>
			</div>

					</footer>
	</article>
							
	<article id="post-33" class="post-33 post type-post status-publish format-standard has-post-thumbnail hentry category-ipfs tag-essay tag-ipfs tag-web">
		
		
		
					<div class="excerpt-wrapper">

										<a href="why-the-internet-is-falling-apart-and-the-need-for-ipfs/index.html" title="Why the Internet is Falling Apart and the Need for IPFS" rel="bookmark">
							<div class="wrapper-excerpt-thumbnail">
								<img width="240" height="180" src="wp-content/uploads/2020/03/abandoned-airplane-apocalypse-crash-6709-240x180.jpg" class="attachment-ribosome-excerpt-thumbnail size-ribosome-excerpt-thumbnail wp-post-image" alt="">							</div>
						</a>
				
				<header class="entry-header">
					<h2 class="entry-title">
					<a href="why-the-internet-is-falling-apart-and-the-need-for-ipfs/index.html" rel="bookmark">Why the Internet is Falling Apart and the Need for IPFS</a>
					</h2>
									</header>

				<p>IPFS is fascinating. Expect to hear a lot more about this groundbreaking new tech in this blog. Over the upcoming weeks and months, weβll discuss its philosophical underpinnings, why itβ¦ <a href="why-the-internet-is-falling-apart-and-the-need-for-ipfs/index.html">Read more Β»</a></p>

			</div>

		
		<footer class="entry-meta">
			
			
							<div class="entry-meta-term-excerpt">
				
				<span class="entry-meta-categories"><span class="term-icon"><i class="fa fa-folder-open"></i></span> <a href="category/ipfs/index.html" rel="tag">IPFS</a>   </span>

									<span class="entry-meta-tags"><span class="term-icon"><i class="fa fa-tags"></i></span> <a href="tag/essay/index.html" rel="tag">essay</a>, <a href="tag/ipfs/index.html" rel="tag">IPFS</a>, <a href="tag/web/index.html" rel="tag">web</a></span>
					
				<div style="float:right;"></div>
			</div>

					</footer>
	</article>
							
	<article id="post-1" class="post-1 post type-post status-publish format-standard hentry category-general">
		
		
		
					<div class="excerpt-wrapper">

				
				<header class="entry-header">
					<h2 class="entry-title">
					<a href="welcome-and-thanks-for-all-the-fish/index.html" rel="bookmark">Welcome, and thanks for all the fish!</a>
					</h2>
									</header>

				<p>Welcome to my programming blog! I have no clue how you stumbled here, but am happy you did. In ten years from now, you will be bragging to your friendsβ¦ <a href="welcome-and-thanks-for-all-the-fish/index.html">Read more Β»</a></p>

			</div>

		
		<footer class="entry-meta">
			
			
							<div class="entry-meta-term-excerpt">
				
				<span class="entry-meta-categories"><span class="term-icon"><i class="fa fa-folder-open"></i></span> <a href="category/general/index.html" rel="tag">General</a>   </span>

				
				<div style="float:right;"></div>
			</div>

					</footer>
	</article>
			<div class="posts-pagination-wrapper"></div>
		
		</div>
	</div>


			<div id="secondary" class="widget-area" role="complementary">
			<aside id="mc4wp_form_widget-2" class="widget widget_mc4wp_form_widget"><h3 class="widget-title"><span class="widget-title-tab">Subscribe by Email!</span></h3><script>(function() {
	window.mc4wp = window.mc4wp || {
		listeners: [],
		forms: {
			on: function(evt, cb) {
				window.mc4wp.listeners.push(
					{
						event   : evt,
						callback: cb
					}
				);
			}
		}
	}
})();
</script><form id="mc4wp-form-1" class="mc4wp-form mc4wp-form-80 mc4wp-form-theme mc4wp-form-theme-blue" method="post" data-id="80" data-name="Subscribers Form"><div class="mc4wp-form-fields"><p>
    <input type="text" name="FNAME" placeholder="First Name" required="">
</p>
<p>
		<input type="email" name="EMAIL" placeholder="Email Address" required>
</p>

<p>
	<input type="submit" value="SUBSCRIBE!">
</p></div><label style="display: none !important;">Leave this field empty if you're human: <input type="text" name="_mc4wp_honeypot" value="" tabindex="-1" autocomplete="off"></label><input type="hidden" name="_mc4wp_timestamp" value="1587339175"><input type="hidden" name="_mc4wp_form_id" value="80"><input type="hidden" name="_mc4wp_form_element_id" value="mc4wp-form-1"><div class="mc4wp-response"></div></form></aside>		</div>
		</div>
	<footer id="colophon" role="contentinfo">
		<div class="site-info">
			<div class="credits credits-left">
			Copyright 2020			</div>

			<div class="credits credits-center">
						</div>

			<div class="credits credits-right">
			<a href="https://galussothemes.com/wordpress-themes/ribosome">Ribosome</a> by GalussoThemes.com<br>
			Powered by<a href="https://wordpress.org/" title="Semantic Personal Publishing Platform"> WordPress</a>
			</div>
		</div>
	</footer>
</div>

	<div class="ir-arriba"><i class="fa fa-arrow-up"></i></div>
	<script>(function() {function maybePrefixUrlField() {
	if (this.value.trim() !== '' && this.value.indexOf('http') !== 0) {
		this.value = "http://" + this.value;
	}
}

var urlFields = document.querySelectorAll('.mc4wp-form input[type="url"]');
if (urlFields) {
	for (var j=0; j < urlFields.length; j++) {
		urlFields[j].addEventListener('blur', maybePrefixUrlField);
	}
}
})();</script><script type="text/javascript" src="wp-content/themes/ribosome/js/navigation.js"></script>
<script type="text/javascript" src="wp-content/themes/ribosome/js/ribosome-scripts-functions.js"></script>
<script type="text/javascript" src="wp-content/plugins/mailchimp-for-wp/assets/js/forms.min.js"></script>

</body>
</html>
Β© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
Loading complete
