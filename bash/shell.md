





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://github.githubassets.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" media="all" integrity="sha512-pWLt6abkYhNeAHaDrPVG0yXCtIGRuCkwSUqQpsyN6smAIpIt+Iuq2IZKmoH9l3Cy/9ZnjvVrFZnvFFjGiqE3EA==" rel="stylesheet" href="https://github.githubassets.com/assets/frameworks-a3b8a10d4a9e37a78f033ef4a4f525f5.css" />
  <link crossorigin="anonymous" media="all" integrity="sha512-rKfY0i2mZNv0BG7UyrzAdcm8GXBGHIB0y/hugtNxVUpHP41KoUR1CRRiR7eTvDuRDLF+x8P9fEsP7yxQwO464Q==" rel="stylesheet" href="https://github.githubassets.com/assets/github-aa5c2f579992daf0b40c175aabf01dfb.css" />
  
  
  <link crossorigin="anonymous" media="all" integrity="sha512-L+Xfjk72/sIPS5T8Z8Wy/+/78ngrN7jAjVpE5Zoo2KfZYqr9s8p6selV7sLydYrh0Y3Pu02CuEa7uuq70RjSxg==" rel="stylesheet" href="https://github.githubassets.com/assets/site-278e4176d194ae782983c71f1f767503.css" />
  
  

  <meta name="viewport" content="width=device-width">
  
  <title>DevOps/Shell.md at master · sslinux/DevOps · GitHub</title>
    <meta name="description" content="运维知识学习笔记，希望能长期记录！. Contribute to sslinux/DevOps development by creating an account on GitHub.">
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    
    <meta property="og:image" content="https://avatars2.githubusercontent.com/u/18586288?s=400&amp;v=4" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="sslinux/DevOps" /><meta property="og:url" content="https://github.com/sslinux/DevOps" /><meta property="og:description" content="运维知识学习笔记，希望能长期记录！. Contribute to sslinux/DevOps development by creating an account on GitHub." />

  <link rel="assets" href="https://github.githubassets.com/">
  
  <meta name="pjax-timeout" content="1000">
  
  <meta name="request-id" content="E8EA:11F0:263AE95:3FBF4FE:5C612DB7" data-pjax-transient>


  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

      <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">

  <meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-request_id" content="E8EA:11F0:263AE95:3FBF4FE:5C612DB7" /><meta name="octolytics-dimension-region_edge" content="iad" /><meta name="octolytics-dimension-region_render" content="iad" />
<meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" />



    <meta name="google-analytics" content="UA-3769691-2">


<meta class="js-ga-set" name="dimension1" content="Logged Out">



  

      <meta name="hostname" content="github.com">
    <meta name="user-login" content="">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="MDE2ZWE5ODdhZDJlMTk4ZDkxN2YzOGY1MGRjODU3MTdkNDNjZmM5YmU1MDU5NzA0NmQxZGJlY2M2YmI2MWUyZHx7InJlbW90ZV9hZGRyZXNzIjoiNTIuMjI5LjE2Mi43NSIsInJlcXVlc3RfaWQiOiJFOEVBOjExRjA6MjYzQUU5NTozRkJGNEZFOjVDNjEyREI3IiwidGltZXN0YW1wIjoxNTQ5ODcyNTY4LCJob3N0IjoiZ2l0aHViLmNvbSJ9">

    <meta name="enabled-features" content="UNIVERSE_BANNER,MARKETPLACE_PLAN_RESTRICTION_EDITOR,MARKETPLACE_BROWSING_V2">

  <meta name="html-safe-nonce" content="2f7ee29d1e58add25eeb994cc09b6f38bc881436">

  <meta http-equiv="x-pjax-version" content="595387260052339286e860de63e19cac">
  

      <link href="https://github.com/sslinux/DevOps/commits/master.atom" rel="alternate" title="Recent Commits to DevOps:master" type="application/atom+xml">

  <meta name="go-import" content="github.com/sslinux/DevOps git https://github.com/sslinux/DevOps.git">

  <meta name="octolytics-dimension-user_id" content="18586288" /><meta name="octolytics-dimension-user_login" content="sslinux" /><meta name="octolytics-dimension-repository_id" content="67809447" /><meta name="octolytics-dimension-repository_nwo" content="sslinux/DevOps" /><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="false" /><meta name="octolytics-dimension-repository_network_root_id" content="67809447" /><meta name="octolytics-dimension-repository_network_root_nwo" content="sslinux/DevOps" /><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="false" />


    <link rel="canonical" href="https://github.com/sslinux/DevOps/blob/master/Bash/Shell.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://github.githubassets.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://github.githubassets.com/favicon.ico">

<meta name="theme-color" content="#1e2327">



  <link rel="manifest" href="/manifest.json" crossOrigin="use-credentials">

  </head>

  <body class="logged-out env-production page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="px-2 py-4 bg-blue text-white show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    


        
<header class="Header header-logged-out  position-relative f4 py-3" role="banner">
  <div class="container-lg d-flex px-3">
    <div class="d-flex flex-justify-between flex-items-center">
        <a class="mr-4" href="https://github.com/" aria-label="Homepage" data-ga-click="(Logged out) Header, go to homepage, icon:logo-wordmark">
          <svg height="32" class="octicon octicon-mark-github text-white" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
        </a>
    </div>

    <div class="HeaderMenu HeaderMenu--logged-out d-flex flex-justify-between flex-items-center flex-auto">
      <div class="d-none">
        <button class="btn-link js-details-target" type="button" aria-label="Toggle navigation" aria-expanded="false">
          <svg height="24" class="octicon octicon-x text-gray" viewBox="0 0 12 16" version="1.1" width="18" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
        </button>
      </div>

        <nav class="mt-0" aria-label="Global">
          <ul class="d-flex list-style-none">
              <li class=" mr-3 mr-lg-3 edge-item-fix position-relative flex-wrap flex-justify-between d-flex flex-items-center ">
                <details class="HeaderMenu-details details-overlay details-reset width-full">
                  <summary class="HeaderMenu-summary HeaderMenu-link px-0 py-3 border-0 no-wrap  d-inline-block">
                    Why GitHub?
                    <svg x="0px" y="0px" viewBox="0 0 14 8" xml:space="preserve" fill="none" class="icon-chevon-down-mktg position-relative">
                      <path d="M1,1l6.2,6L13,1"></path>
                    </svg>
                  </summary>
                  <div class="dropdown-menu flex-auto rounded-1 bg-white px-0 mt-0  p-4 left-n4 position-absolute">
                    <a href="/features" class="py-2 lh-condensed-ultra d-block link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Features">Features <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a>
                    <ul class="list-style-none f5 pb-3">
                      <li class="edge-item-fix"><a href="/features/code-review/" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Code review">Code review</a></li>
                      <li class="edge-item-fix"><a href="/features/project-management/" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Project management">Project management</a></li>
                      <li class="edge-item-fix"><a href="/features/integrations" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Integrations">Integrations</a></li>
                      <li class="edge-item-fix"><a href="/features/actions" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Actions">Actions</a>
                      <li class="edge-item-fix"><a href="/features#team-management" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Team management">Team management</a></li>
                      <li class="edge-item-fix"><a href="/features#social-coding" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Social coding">Social coding</a></li>
                      <li class="edge-item-fix"><a href="/features#documentation" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Documentation">Documentation</a></li>
                      <li class="edge-item-fix"><a href="/features#code-hosting" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Code hosting">Code hosting</a></li>
                    </ul>

                    <ul class="list-style-none mb-0 border-lg-top pt-lg-3">
                      <li class="edge-item-fix"><a href="/case-studies" class="py-2 lh-condensed-ultra d-block no-underline link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Case studies">Case Studies <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a></li>
                      <li class="edge-item-fix"><a href="/security" class="py-2 lh-condensed-ultra d-block no-underline link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Security">Security <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a></li>
                    </ul>
                  </div>
                </details>
              </li>
              <li class=" mr-3 mr-lg-3">
                <a href="/enterprise" class="HeaderMenu-link no-underline py-3 d-block d-lg-inline-block" data-ga-click="(Logged out) Header, click, go to Enterprise">Enterprise</a>
              </li>

              <li class=" mr-3 mr-lg-3 edge-item-fix position-relative flex-wrap flex-justify-between d-flex flex-items-center ">
                <details class="HeaderMenu-details details-overlay details-reset width-full">
                  <summary class="HeaderMenu-summary HeaderMenu-link px-0 py-3 border-0 no-wrap  d-inline-block">
                    Explore
                    <svg x="0px" y="0px" viewBox="0 0 14 8" xml:space="preserve" fill="none" class="icon-chevon-down-mktg position-relative">
                      <path d="M1,1l6.2,6L13,1"></path>
                    </svg>
                  </summary>

                  <div class="dropdown-menu flex-auto rounded-1 bg-white px-0 pt-2 pb-0 mt-0  p-4 left-n4 position-absolute">
                    <ul class="list-style-none mb-3">
                      <li class="edge-item-fix"><a href="/explore" class="py-2 lh-condensed-ultra d-block link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Features">Explore GitHub <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a></li>
                    </ul>

                    <h4 class="text-gray-light text-normal text-mono f5 mb-2  border-top pt-3">Learn &amp; contribute</h4>
                    <ul class="list-style-none mb-3">
                      <li class="edge-item-fix"><a href="/topics" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Topics">Topics</a></li>
                      <li class="edge-item-fix"><a href="/collections" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Collections">Collections</a></li>
                      <li class="edge-item-fix"><a href="/trending" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Trending">Trending</a></li>
                      <li class="edge-item-fix"><a href="https://lab.github.com/" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Learning lab">Learning Lab</a></li>
                      <li class="edge-item-fix"><a href="https://opensource.guide" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Open source guides">Open source guides</a></li>
                    </ul>

                    <h4 class="text-gray-light text-normal text-mono f5 mb-2  border-top pt-3">Connect with others</h4>
                    <ul class="list-style-none mb-0">
                      <li class="edge-item-fix"><a href="/events" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Events">Events</a></li>
                      <li class="edge-item-fix"><a href="https://github.community" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Community forum">Community forum</a></li>
                      <li class="edge-item-fix"><a href="https://education.github.com" class="py-2 pb-0 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to GitHub Education">GitHub Education</a></li>
                    </ul>
                  </div>
                </details>
              </li>

              <li class=" mr-3 mr-lg-3">
                <a href="/marketplace" class="HeaderMenu-link no-underline py-3 d-block d-lg-inline-block" data-ga-click="(Logged out) Header, go to Marketplace">Marketplace</a>
              </li>

              <li class=" mr-3 mr-lg-3 edge-item-fix position-relative flex-wrap flex-justify-between d-flex flex-items-center ">
                <details class="HeaderMenu-details details-overlay details-reset width-full">
                  <summary class="HeaderMenu-summary HeaderMenu-link px-0 py-3 border-0 no-wrap  d-inline-block">
                    Pricing
                    <svg x="0px" y="0px" viewBox="0 0 14 8" xml:space="preserve" fill="none" class="icon-chevon-down-mktg position-relative">
                       <path d="M1,1l6.2,6L13,1"></path>
                    </svg>
                  </summary>

                  <div class="dropdown-menu flex-auto rounded-1 bg-white px-0 pt-2 pb-4 mt-0  p-4 left-n4 position-absolute">
                    <a href="/pricing" class="pb-2 lh-condensed-ultra d-block link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Pricing">Plans <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a>

                    <ul class="list-style-none mb-3">
                      <li class="edge-item-fix"><a href="/pricing#feature-comparison" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Compare features">Compare plans</a></li>
                      <li class="edge-item-fix"><a href="https://enterprise.github.com/contact" class="py-2 lh-condensed-ultra d-block link-gray no-underline f5" data-ga-click="(Logged out) Header, go to Compare features">Contact Sales</a></li>
                    </ul>

                    <ul class="list-style-none mb-0  border-top pt-3">
                      <li class="edge-item-fix"><a href="/nonprofit" class="py-2 lh-condensed-ultra d-block no-underline link-gray-dark no-underline h5 Bump-link--hover" data-ga-click="(Logged out) Header, go to Nonprofits">Nonprofit <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a></li>
                      <li class="edge-item-fix"><a href="https://education.github.com" class="py-2 pb-0 lh-condensed-ultra d-block no-underline link-gray-dark no-underline h5 Bump-link--hover"  data-ga-click="(Logged out) Header, go to Education">Education <span class="Bump-link-symbol float-right text-normal text-gray-light">&rarr;</span></a></li>
                    </ul>
                  </div>
                </details>
              </li>
          </ul>
        </nav>

      <div class="d-flex flex-items-center px-0 text-center text-left">
          <div class="d-lg-flex mr-3">
            <div class="header-search scoped-search site-scoped-search js-site-search position-relative js-jump-to"
  role="combobox"
  aria-owns="jump-to-results"
  aria-label="Search or jump to"
  aria-haspopup="listbox"
  aria-expanded="false"
>
  <div class="position-relative">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-site-search-form" data-scope-type="Repository" data-scope-id="67809447" data-scoped-search-url="/sslinux/DevOps/search" data-unscoped-search-url="/search" action="/sslinux/DevOps/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
      <label class="form-control header-search-wrapper header-search-wrapper-jump-to position-relative d-flex flex-justify-between flex-items-center js-chromeless-input-container">
        <input type="text"
          class="form-control header-search-input jump-to-field js-jump-to-field js-site-search-focus js-site-search-field is-clearable"
          data-hotkey="s,/"
          name="q"
          value=""
          placeholder="Search"
          data-unscoped-placeholder="Search GitHub"
          data-scoped-placeholder="Search"
          autocapitalize="off"
          aria-autocomplete="list"
          aria-controls="jump-to-results"
          aria-label="Search"
          data-jump-to-suggestions-path="/_graphql/GetSuggestedNavigationDestinations#csrf-token=tj89C3D5z5FwkHEX10wLFUXp9jT/HWjCMtW6QWmHi/qONhvh/W70Mc3lwSInSyB3hi/KVzWUkLLJ6FWfdlIn1w=="
          spellcheck="false"
          autocomplete="off"
          >
          <input type="hidden" class="js-site-search-type-field" name="type" >
            <img src="https://github.githubassets.com/images/search-key-slash.svg" alt="" class="mr-2 header-search-key-slash">

            <div class="Box position-absolute overflow-hidden d-none jump-to-suggestions js-jump-to-suggestions-container">
              
<ul class="d-none js-jump-to-suggestions-template-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-suggestion" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

</ul>

<ul class="d-none js-jump-to-no-results-template-container">
  <li class="d-flex flex-justify-center flex-items-center f5 d-none js-jump-to-suggestion p-2">
    <span class="text-gray">No suggested jump to results</span>
  </li>
</ul>

<ul id="jump-to-results" role="listbox" class="p-0 m-0 js-navigation-container jump-to-suggestions-results-container js-jump-to-suggestions-results-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-scoped-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-global-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>


</ul>

            </div>
      </label>
</form>  </div>
</div>

          </div>

        <a class="HeaderMenu-link no-underline mr-3" href="/login?return_to=%2Fsslinux%2FDevOps%2Fblob%2Fmaster%2FBash%2FShell.md" data-ga-click="(Logged out) Header, clicked Sign in, text:sign-in">Sign&nbsp;in</a>
          <a class="HeaderMenu-link d-inline-block no-underline border border-gray-dark rounded-1 px-2 py-1" href="/join" data-ga-click="(Logged out) Header, clicked Sign up, text:sign-up">Sign&nbsp;up</a>
      </div>
    </div>
  </div>
</header>

  </div>

  <div id="start-of-content" class="show-on-focus"></div>

    <div id="js-flash-container">

</div>



  <div role="main" class="application-main " data-commit-hovercards-enabled>
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <div id="js-repo-pjax-container" data-pjax-container >
      


  





  <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav  ">
    <div class="repohead-details-container clearfix container">

      <ul class="pagehead-actions">

  <li>
      <a href="/login?return_to=%2Fsslinux%2FDevOps"
    class="btn btn-sm btn-with-count tooltipped tooltipped-s"
    aria-label="You must be signed in to watch a repository" rel="nofollow">
    <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
    Watch
  </a>
  <a class="social-count" href="/sslinux/DevOps/watchers"
     aria-label="1 user is watching this repository">
    1
  </a>

  </li>

  <li>
        <a href="/login?return_to=%2Fsslinux%2FDevOps"
      class="btn btn-sm btn-with-count tooltipped tooltipped-s"
      aria-label="You must be signed in to star a repository" rel="nofollow">
      <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
      Star
    </a>

    <a class="social-count js-social-count" href="/sslinux/DevOps/stargazers"
      aria-label="1 user starred this repository">
      1
    </a>

  </li>

  <li>
      <a href="/login?return_to=%2Fsslinux%2FDevOps"
        class="btn btn-sm btn-with-count tooltipped tooltipped-s"
        aria-label="You must be signed in to fork a repository" rel="nofollow">
        <svg class="octicon octicon-repo-forked v-align-text-bottom" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
        Fork
      </a>

    <a href="/sslinux/DevOps/network/members" class="social-count"
       aria-label="0 users forked this repository">
      0
    </a>
  </li>
</ul>

      <h1 class="public ">
  <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a class="url fn" rel="author" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=18586288" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/sslinux">sslinux</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a data-pjax="#js-repo-pjax-container" href="/sslinux/DevOps">DevOps</a></strong>

</h1>

    </div>
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax container"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
    aria-label="Repository"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a class="js-selected-navigation-item selected reponav-item" itemprop="url" data-hotkey="g c" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /sslinux/DevOps" href="/sslinux/DevOps">
      <svg class="octicon octicon-code" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" data-hotkey="g i" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /sslinux/DevOps/issues" href="/sslinux/DevOps/issues">
        <svg class="octicon octicon-issue-opened" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a data-hotkey="g p" itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /sslinux/DevOps/pulls" href="/sslinux/DevOps/pulls">
      <svg class="octicon octicon-git-pull-request" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>


    <a data-hotkey="g b" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /sslinux/DevOps/projects" href="/sslinux/DevOps/projects">
      <svg class="octicon octicon-project" viewBox="0 0 15 16" version="1.1" width="15" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      Projects
      <span class="Counter" >0</span>
</a>


    <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse alerts security people /sslinux/DevOps/pulse" href="/sslinux/DevOps/pulse">
      <svg class="octicon octicon-graph" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
      Insights
</a>

</nav>


  </div>
<div class="container new-discussion-timeline experiment-repo-nav  ">
  <div class="repository-content ">

    
    



  
    <a class="d-none js-permalink-shortcut" data-hotkey="y" href="/sslinux/DevOps/blob/b447feac242b4671df862af305ad260a8123051a/Bash/Shell.md">Permalink</a>

    <!-- blob contrib key: blob_contributors:v21:259d63cfc67c6b3e58e569ddfc8868a4 -->

        <div class="signup-prompt-bg rounded-1">
      <div class="signup-prompt p-4 text-center mb-4 rounded-1">
        <div class="position-relative">
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form action="/site/dismiss_signup_prompt" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="eqA2uDX8jA5juqaE2g/wvo0DR1v8lil4PMVm+1AtKxeuDJM/TAEW2ep733Aard/6Bw4ArV/Mwmx13kEZIzy30g==" />
            <button type="submit" class="position-absolute top-0 right-0 btn-link link-gray" data-ga-click="(Logged out) Sign up prompt, clicked Dismiss, text:dismiss">
              Dismiss
            </button>
</form>          <h3 class="pt-2">Join GitHub today</h3>
          <p class="col-6 mx-auto">GitHub is home to over 31 million developers working together to host and review code, manage projects, and build software together.</p>
          <a class="btn btn-primary" href="/join?source=prompt-blob-show" data-ga-click="(Logged out) Sign up prompt, clicked Sign up, text:sign-up">Sign up</a>
        </div>
      </div>
    </div>


    <div class="file-navigation">
      
<details class="details-reset details-overlay select-menu branch-select-menu float-left">
  <summary class="btn btn-sm select-menu-button css-truncate"
           data-hotkey="w"
           
           title="Switch branches or tags">
    <i>Branch:</i>
    <span class="css-truncate-target">master</span>
  </summary>

  <details-menu class="select-menu-modal position-absolute" style="z-index: 99;" src="/sslinux/DevOps/ref-list/master/Bash/Shell.md?source_action=show&amp;source_controller=blob" preload>
    <include-fragment class="select-menu-loading-overlay anim-pulse">
      <svg height="32" class="octicon octicon-octoface" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M14.7 5.34c.13-.32.55-1.59-.13-3.31 0 0-1.05-.33-3.44 1.3-1-.28-2.07-.32-3.13-.32s-2.13.04-3.13.32c-2.39-1.64-3.44-1.3-3.44-1.3-.68 1.72-.26 2.99-.13 3.31C.49 6.21 0 7.33 0 8.69 0 13.84 3.33 15 7.98 15S16 13.84 16 8.69c0-1.36-.49-2.48-1.3-3.35zM8 14.02c-3.3 0-5.98-.15-5.98-3.35 0-.76.38-1.48 1.02-2.07 1.07-.98 2.9-.46 4.96-.46 2.07 0 3.88-.52 4.96.46.65.59 1.02 1.3 1.02 2.07 0 3.19-2.68 3.35-5.98 3.35zM5.49 9.01c-.66 0-1.2.8-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.54-1.78-1.2-1.78zm5.02 0c-.66 0-1.2.79-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.53-1.78-1.2-1.78z"/></svg>
    </include-fragment>
  </details-menu>
</details>

      <div class="BtnGroup float-right">
        <a href="/sslinux/DevOps/find/master"
              class="js-pjax-capture-input btn btn-sm BtnGroup-item"
              data-pjax
              data-hotkey="t">
          Find file
        </a>
        <clipboard-copy for="blob-path" class="btn btn-sm BtnGroup-item">
          Copy path
        </clipboard-copy>
      </div>
      <div id="blob-path" class="breadcrumb">
        <span class="repo-root js-repo-root"><span class="js-path-segment"><a data-pjax="true" href="/sslinux/DevOps"><span>DevOps</span></a></span></span><span class="separator">/</span><span class="js-path-segment"><a data-pjax="true" href="/sslinux/DevOps/tree/master/Bash"><span>Bash</span></a></span><span class="separator">/</span><strong class="final-path">Shell.md</strong>
      </div>
    </div>


    
  <div class="commit-tease">
      <span class="float-right">
        <a class="commit-tease-sha" href="/sslinux/DevOps/commit/cfae07da60d10c2a15de9dc0b5f27ee2970a6c53" data-pjax>
          cfae07d
        </a>
        <relative-time datetime="2016-09-12T05:31:04Z">Sep 12, 2016</relative-time>
      </span>
      <div>
        <img class="avatar" width="20" height="20" alt="" src="https://camo.githubusercontent.com/4830cdf4d57dbc05a33242d4e776db6d5e6d679c/68747470733a2f2f312e67726176617461722e636f6d2f6176617461722f65343439376238626464663765356636343363353462336532316531643866663f643d68747470732533412532462532466769746875622e6769746875626173736574732e636f6d253246696d6167657325324667726176617461727325324667726176617461722d757365722d3432302e706e6726723d6726733d313430" data-canonical-src="https://1.gravatar.com/avatar/e4497b8bddf7e5f643c54b3e21e1d8ff?d=https%3A%2F%2Fgithub.githubassets.com%2Fimages%2Fgravatars%2Fgravatar-user-420.png&amp;r=g&amp;s=140" />
        <span class="user-mention">kalaguiyin</span>
          <a data-pjax="true" title="format again" class="message" href="/sslinux/DevOps/commit/cfae07da60d10c2a15de9dc0b5f27ee2970a6c53">format again</a>
      </div>

    <div class="commit-tease-contributors">
      
<details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark float-left mr-2" id="blob_contributors_box">
  <summary
      class="btn-link"
      aria-haspopup="dialog"
      
      
      >
    
    <span><strong>1</strong> contributor</span>
  </summary>
  <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast " aria-label="Users who have contributed to this file">
    <div class="Box-header">
      <button class="Box-btn-octicon btn-octicon float-right" type="button" aria-label="Close dialog" data-close-dialog>
        <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
      </button>
      <h3 class="Box-title">Users who have contributed to this file</h3>
    </div>
    
        <ul class="list-style-none overflow-auto">
            <li class="Box-row">
              <a class="link-gray-dark no-underline" href="/sslinux">
                <img class="avatar mr-2" alt="" src="https://avatars3.githubusercontent.com/u/18586288?s=40&amp;v=4" width="20" height="20" />
                sslinux
</a>            </li>
        </ul>

  </details-dialog>
</details>
      
    </div>
  </div>




    <div class="file ">
      
<div class="file-header">

  <div class="file-actions">


    <div class="BtnGroup">
      <a id="raw-url" class="btn btn-sm BtnGroup-item" href="/sslinux/DevOps/raw/master/Bash/Shell.md">Raw</a>
        <a class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b" href="/sslinux/DevOps/blame/master/Bash/Shell.md">Blame</a>
      <a rel="nofollow" class="btn btn-sm BtnGroup-item" href="/sslinux/DevOps/commits/master/Bash/Shell.md">History</a>
    </div>



        <button type="button" class="btn-octicon disabled tooltipped tooltipped-nw"
          aria-label="You must be signed in to make or propose changes">
          <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
        </button>
        <button type="button" class="btn-octicon btn-octicon-danger disabled tooltipped tooltipped-nw"
          aria-label="You must be signed in to make or propose changes">
          <svg class="octicon octicon-trashcan" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
        </button>
  </div>

  <div class="file-info">
      2308 lines (1676 sloc)
      <span class="file-info-divider"></span>
    53.6 KB
  </div>
</div>

      
  <div id=readme class="readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content" itemprop="text"><h1><a id="user-content-bash基础特性及shell脚本编程" class="anchor" aria-hidden="true" href="#bash基础特性及shell脚本编程"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Bash基础特性及shell脚本编程</h1>
<h2><a id="user-content-目录" class="anchor" aria-hidden="true" href="#目录"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-目录">目录</span></h2>
<ul>
<li><a href="#01%E5%91%BD%E4%BB%A4%E5%8E%86%E5%8F%B2">1、命令历史</a></li>
<li><a href="#02%E5%91%BD%E4%BB%A4%E8%A1%A5%E5%85%A8">2、命令补全</a></li>
<li><a href="#03%E8%B7%AF%E5%BE%84%E8%A1%A5%E5%85%A8">3、路径补全</a></li>
<li><a href="#04%E5%91%BD%E4%BB%A4%E8%A1%8C%E5%B1%95%E5%BC%80">4、命令行展开</a></li>
<li><a href="#05%E5%91%BD%E4%BB%A4%E7%9A%84%E6%89%A7%E8%A1%8C%E7%8A%B6%E6%80%81%E7%BB%93%E6%9E%9C">5、命令的执行状态结果</a></li>
<li><a href="#06%E5%91%BD%E4%BB%A4%E5%88%AB%E5%90%8D">6、命令别名</a></li>
<li><a href="#07%E9%80%9A%E9%85%8D%E7%AC%A6glob">7、通配符glob</a></li>
<li><a href="#08bash%E5%BF%AB%E6%8D%B7%E9%94%AE">8、bash快捷键</a></li>
<li><a href="#09bash%E7%9A%84io%E9%87%8D%E5%AE%9A%E5%90%91%E5%8F%8A%E7%AE%A1%E9%81%93">9、bash的IO重定向及管道</a></li>
<li><a href="#10shell%E7%BC%96%E7%A8%8B%E7%8E%AF%E5%A2%83">10、shell编程环境</a></li>
<li><a href="#11bash%E5%8F%98%E9%87%8F%E7%B1%BB%E5%9E%8B">11、bash变量类型</a></li>
<li><a href="#12bash%E7%9A%84%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6">12、bash的配置文件</a></li>
<li><a href="#13bash%E4%B8%AD%E7%9A%84%E7%AE%97%E6%9C%AF%E8%BF%90%E7%AE%97%E7%AC%A6">13、bash中的算术运算符</a></li>
<li><a href="#14bash%E6%9D%A1%E4%BB%B6%E6%B5%8B%E8%AF%95">14、bash条件测试</a></li>
<li><a href="#15bash%E8%84%9A%E6%9C%AC%E7%BC%96%E7%A8%8B%E4%B9%8B%E7%94%A8%E6%88%B7%E4%BA%A4%E4%BA%92">15、bash脚本之用户交互</a></li>
<li><a href="#16%E6%B5%81%E7%A8%8B%E6%8E%A7%E5%88%B6">16、流程控制</a>
<ul>
<li><a href="#if%E8%AF%AD%E5%8F%A5">if语句</a></li>
<li><a href="#for%E5%BE%AA%E7%8E%AF">for循环</a></li>
<li><a href="#while%E5%BE%AA%E7%8E%AF">while循环</a></li>
<li><a href="#until%E5%BE%AA%E7%8E%AF">until循环</a></li>
<li><a href="#%E5%BE%AA%E7%8E%AF%E6%8E%A7%E5%88%B6%E8%AF%AD%E5%8F%A5">循环控制语句</a></li>
<li><a href="#%E5%88%9B%E5%BB%BA%E6%AD%BB%E5%BE%AA%E7%8E%AF">创建死循环</a></li>
<li><a href="#case%E8%AF%AD%E5%8F%A5">case语句</a></li>
</ul>
</li>
<li><a href="#%E5%87%BD%E6%95%B0">17、函数</a></li>
<li><a href="#18%E6%95%B0%E7%BB%84">18、数组</a></li>
<li><a href="#19bash%E7%9A%84%E5%AD%97%E7%AC%A6%E4%B8%B2%E5%A4%84%E7%90%86%E5%B7%A5%E5%85%B7">19、bash的字符串处理工具</a></li>
<li><a href="#20%E3%80%81%E8%84%9A%E6%9C%AC%E7%9A%84%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6">20、脚本的配置文件</a></li>
</ul>
<h2><a id="user-content-01命令历史" class="anchor" aria-hidden="true" href="#01命令历史"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-01命令历史">01命令历史</span></h2>
<p>（1） 使用命令：history</p>
<p>（2） 环境变量：</p>
<pre><code>    a) HISTSIZE：命令历史缓冲区中记录的条数，默认为1000；

    b) HISTFILE：记录当前登录用户在logout时历史命令存放文件；

    c) HISTFILESIZE：命令历史文件记录历史的条数，默认为1000；
</code></pre>
<p>(3)  操作命令历史：</p>
<pre><code>    a) history –d OFFSET 删除指定行的命令历史；

    b) history –c 清空命令历史缓冲区中的命令；

    c) history # 显示历史中最近的#条命令；

    d) history –a 手动追加当前会话缓冲区中的命令至历史文件中；
</code></pre>
<p>(4) 调用历史中的命令：</p>
<pre><code>    a) !# : 重复执行第#条命令；

    b) !! : 重复执行上一条(最近一条命令；)

    c) !string : 重复执行最近一次以指定字符串开头的命令；

    d) 调用上一条命令的最后一个参数：

         i. !$

         ii. ESC, ．
</code></pre>
<p>（5） 控制命令历史的记录方式：</p>
<pre><code>    环境变量：HISTCONTROL

    三个值：

        ignoredups：忽略重复的命令；所谓重复，一定是连续且完全相同，包括选项和参数；

        ignorespace：忽略所有以空白开头的命令，不记录；

        ignoreboth：忽略上述两项，既忽略重复的命令，也忽略空白开头的命令；
</code></pre>
<ul>
<li>
<p>修改环境变量的方式：</p>
<pre><code>   export 变量名=“VALUE”

   或： VARNAME=“VALUE” export VARNAME
</code></pre>
</li>
</ul>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-02命令补全" class="anchor" aria-hidden="true" href="#02命令补全"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-02命令补全">02命令补全</span></h2>
<p>内部命令：直接通过shell补全；
外部命令：bash根据PATH环境变量定义的路径，自左而右地在每个路径搜寻以给定命令命名的文件，第一次找到即为要执行的命令；</p>
<ul>
<li>Note: 在第一次通过PATH搜寻到命令后，会将其存入hash缓存中，下次使用不再搜寻PATH，从hash中查找；</li>
</ul>
<div class="highlight highlight-source-shell"><pre>[root@sslinux <span class="pl-k">~</span>]<span class="pl-c"><span class="pl-c">#</span> hash</span>
hits <span class="pl-c1">command</span>
 1 /usr/sbin/ifconfig
 1 /usr/bin/vim
 1 /usr/bin/ls</pre></div>
<p>Tab键补全：
若用户给出的字符在命令搜索路径中有且仅有一条命令与之相匹配，则Tab键直接补全；</p>
<p>若用户输入的字符在命令搜索路径中有多条命令与之相匹配，则再次Tab键可以将这些命令列出；</p>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-03路径补全" class="anchor" aria-hidden="true" href="#03路径补全"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-03路径补全">03路径补全</span></h2>
<p>以用户输入的字符串作为路径开头，并在其指定路径的上级目录下搜索以指定字符串开头的文件名；</p>
<pre><code>如果唯一，则直接补全；     

否则，再次Tab，列出所有符合条件的路径及文件；  
</code></pre>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-04命令行展开" class="anchor" aria-hidden="true" href="#04命令行展开"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-04命令行展开">04命令行展开</span></h2>
<p>1）~ ：展开为用户的主目录；</p>
<div class="highlight highlight-source-shell"><pre>[root@sslinux log]<span class="pl-c"><span class="pl-c">#</span> pwd</span>
/var/log
[root@sslinux log]<span class="pl-c"><span class="pl-c">#</span> cd ~</span>
[root@sslinux <span class="pl-k">~</span>]<span class="pl-c"><span class="pl-c">#</span> pwd</span>
/root</pre></div>
<p>2）~USERNAME ： 展开为指定用户的主目录；</p>
<div class="highlight highlight-source-shell"><pre>[root@sslinux <span class="pl-k">~</span>]<span class="pl-c"><span class="pl-c">#</span> pwd</span>
/root
[root@sslinux <span class="pl-k">~</span>]<span class="pl-c"><span class="pl-c">#</span> cd ~sslinux</span>
[root@sslinux sslinux]<span class="pl-c"><span class="pl-c">#</span> pwd</span>
/home/sslinux</pre></div>
<p>3） {} ： 可承载一个以逗号分隔的列表，并将其展开为多个路径；</p>
<div class="highlight highlight-source-shell"><pre>[root@localhost test]<span class="pl-c"><span class="pl-c">#</span> ls</span>
[root@localhost test]<span class="pl-c"><span class="pl-c">#</span> mkdir -pv ./tmp/{a,b}/shell</span>
mkdir: created directory <span class="pl-s"><span class="pl-pds">`</span>./tmp<span class="pl-s"><span class="pl-pds">'</span></span></span>
<span class="pl-s"><span class="pl-s">mkdir: created directory `./tmp/a<span class="pl-pds">'</span></span></span>
<span class="pl-s">mkdir: created directory <span class="pl-pds">`</span></span>./tmp/a/shell<span class="pl-s"><span class="pl-pds">'</span></span>
<span class="pl-s">mkdir: created directory `./tmp/b<span class="pl-pds">'</span></span>
mkdir: created directory <span class="pl-s"><span class="pl-pds">`</span>./tmp/b/shell<span class="pl-s"><span class="pl-pds">'</span></span></span>
<span class="pl-s"><span class="pl-s">[root@localhost test]# mkdir -pv ./tmp/{tom,johnson}/hi</span></span>
<span class="pl-s"><span class="pl-s">[root@localhost test]# tree .</span></span>
<span class="pl-s"><span class="pl-s"></span></span>
<span class="pl-s"><span class="pl-s">└── tmp</span></span>
<span class="pl-s"><span class="pl-s"> ├── a</span></span>
<span class="pl-s"><span class="pl-s"> │ └── shell</span></span>
<span class="pl-s"><span class="pl-s"> ├── b</span></span>
<span class="pl-s"><span class="pl-s"> │ └── shell</span></span>
<span class="pl-s"><span class="pl-s"> ├── johnson</span></span>
<span class="pl-s"><span class="pl-s"> │ └── hi</span></span>
<span class="pl-s"><span class="pl-s"> └── tom</span></span>
<span class="pl-s"><span class="pl-s"> └── hi</span></span>
<span class="pl-s"><span class="pl-s">9 directories, 0 files</span></span></pre></div>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-05命令的执行状态结果" class="anchor" aria-hidden="true" href="#05命令的执行状态结果"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-05命令的执行状态结果">05命令的执行状态结果</span></h2>
<p>表示命令是否成功执行；</p>
<p>bash使用特殊变量$?保存最近一条命令的执行状态结果；</p>
<ul>
<li>
<p>环境变量$?的取值：</p>
<pre><code>0 ： 成功；
</code></pre>
<p>1-255：失败，1,127,255为系统保留；</p>
</li>
<li>
<p>程序执行有两类结果：</p>
<p>程序的返回值；程序自身执行的输出结果；</p>
<p>程序的执行状态结果；$?</p>
</li>
</ul>
<div class="highlight highlight-source-shell"><pre>[root@localhost test]<span class="pl-c"><span class="pl-c">#</span> ls /etc/sysconfig/</span>

[root@localhost test]<span class="pl-c"><span class="pl-c">#</span> echo $?</span>

0    <span class="pl-c"><span class="pl-c">#</span>程序的执行状态结果；执行成功；</span>

[root@localhost test]<span class="pl-c"><span class="pl-c">#</span> ls /etc/sysconfig/NNNN</span>

ls: cannot access /etc/sysconfig/NNNN: No such file or directory    <span class="pl-c"><span class="pl-c">#</span>程序自身的执行结果；</span>

[root@localhost test]<span class="pl-c"><span class="pl-c">#</span> echo $?</span>

2    <span class="pl-c"><span class="pl-c">#</span>执行失败；</span>
</pre></div>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-06命令别名" class="anchor" aria-hidden="true" href="#06命令别名"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-06命令别名">06命令别名</span></h2>
<ul>
<li>通过alias命令实现：</li>
</ul>
<p>a、alias ： 显示当前shell进程所有可用的命令别名；</p>
<p>b、定义别名，格式为： alias NAME='VALUE'</p>
<pre><code>定义别名NAME，其执行相当于执行命令VALUE，VALUE中可包含命令、选项以及参数；仅当前会话有效，不建议使用；
</code></pre>
<p>c、通过修改配置文件定义命令别名：</p>
<pre><code>当前用户：~/.bashrc
全局用户：/etc/bashrc
</code></pre>
<ul>
<li>Bash进程重新读取配置文件：</li>
</ul>
<div class="highlight highlight-source-shell"><pre>    <span class="pl-c1">source</span> /path/to/config_file 

    <span class="pl-c1">.</span> /path/to/config_file</pre></div>
<ul>
<li>撤销别名： unalias</li>
</ul>
<pre><code>    unalias [-a] name [name...]
</code></pre>
<ul>
<li>
<p>Note:</p>
<p>对于定义了别名的命令，要使用原命令，可通过\COMMAND的方式使用；</p>
</li>
<li>
<p>Example:</p>
</li>
</ul>
<div class="highlight highlight-source-shell"><pre>[root@sslinux sslinux]<span class="pl-c"><span class="pl-c">#</span> alias</span>
<span class="pl-c1">alias</span> cp=<span class="pl-s"><span class="pl-pds">'</span>cp -i<span class="pl-pds">'</span></span>
<span class="pl-c1">alias</span> egrep=<span class="pl-s"><span class="pl-pds">'</span>egrep --color=auto<span class="pl-pds">'</span></span>
<span class="pl-c1">alias</span> fgrep=<span class="pl-s"><span class="pl-pds">'</span>fgrep --color=auto<span class="pl-pds">'</span></span>
<span class="pl-c1">alias</span> grep=<span class="pl-s"><span class="pl-pds">'</span>grep --color=auto<span class="pl-pds">'</span></span>
<span class="pl-c1">alias</span> l.=<span class="pl-s"><span class="pl-pds">'</span>ls -d .* --color=auto<span class="pl-pds">'</span></span>
<span class="pl-c1">alias</span> ll=<span class="pl-s"><span class="pl-pds">'</span>ls -l --color=auto<span class="pl-pds">'</span></span>
<span class="pl-c1">alias</span> ls=<span class="pl-s"><span class="pl-pds">'</span>ls --color=auto<span class="pl-pds">'</span></span>
<span class="pl-c1">alias</span> mv=<span class="pl-s"><span class="pl-pds">'</span>mv -i<span class="pl-pds">'</span></span>
<span class="pl-c1">alias</span> rm=<span class="pl-s"><span class="pl-pds">'</span>rm -i<span class="pl-pds">'</span></span>
<span class="pl-c1">alias</span> which=<span class="pl-s"><span class="pl-pds">'</span>alias | /usr/bin/which --tty-only --read-alias --show-dot --show-tilde<span class="pl-pds">'</span></span>
[root@sslinux sslinux]<span class="pl-c"><span class="pl-c">#</span> grep alias /root/.bashrc</span>
<span class="pl-c"><span class="pl-c">#</span> User specific aliases and functions</span>
<span class="pl-c1">alias</span> rm=<span class="pl-s"><span class="pl-pds">'</span>rm -i<span class="pl-pds">'</span></span>
<span class="pl-c1">alias</span> cp=<span class="pl-s"><span class="pl-pds">'</span>cp -i<span class="pl-pds">'</span></span>
<span class="pl-c1">alias</span> mv=<span class="pl-s"><span class="pl-pds">'</span>mv -i<span class="pl-pds">'</span></span></pre></div>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-07通配符glob" class="anchor" aria-hidden="true" href="#07通配符glob"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-07通配符glob">07通配符glob</span></h2>
<p>Bash中用于文件名"通配"</p>
<ul>
<li>
<p>通配符： *,?,[]</p>
<ol>
<li>
<ul>
<li>任意长度的任意字符；</li>
</ul>
<p>a * b</p>
</li>
</ol>
</li>
</ul>
<div class="highlight highlight-source-shell"><pre>[root@sslinux sslinux]<span class="pl-c"><span class="pl-c">#</span> ls -ld /etc/au*</span>
drwxr-x---. 3 root root 41 Sep 3 22:05 /etc/audisp
drwxr-x---. 3 root root 79 Sep 3 22:09 /etc/audit</pre></div>
<ol start="2">
<li>
<p>? 任意单个字符；</p>
<pre><code> 	a?b
</code></pre>
</li>
</ol>
<div class="highlight highlight-source-shell"><pre>[root@sslinux sslinux]<span class="pl-c"><span class="pl-c">#</span> ls -ld /etc/*d?t</span>
drwxr-x---. 3 root root 79 Sep 3 22:09 /etc/audit</pre></div>
<ol start="3">
<li>
<p>[]   匹配指定范围内的任意单个字符；</p>
<pre><code>[0-9]    [a-z]   不区分大小写；
[admin]    可以是区间形式的，也可以是离散形式的；
</code></pre>
</li>
</ol>
<div class="highlight highlight-source-shell"><pre>[root@sslinux sslinux]<span class="pl-c"><span class="pl-c">#</span> ls -ld /etc/[ab]*</span>
drwxr-xr-x. 2 root root 4096 Sep 3 22:05 /etc/alternatives
drwxr-xr-x. 2 root root 33 Sep 3 22:04 /etc/avahi
drwxr-xr-x. 2 root root 33 Sep 3 22:04 /etc/bash_completion.d
-rw-r--r--. 1 root root 2835 Oct 29 2014 /etc/bashrc
drwxr-xr-x. 2 root root 6 Mar 6 2015 /etc/binfmt.d</pre></div>
<ol start="4">
<li>[^] 匹配指定范围以外的任意单个字符；</li>
</ol>
<pre><code>        [^0-9] : 单个非数字的任意字符；
</code></pre>
<ul>
<li>专用字符结合：(表示一类字符中的单个)</li>
</ul>
<p>[:digit:] 任意单个数字，相当于[0-9];</p>
<p>[:lower:] 任意单个小写字母；</p>
<p>[:upper:] 任意单个大写字母；</p>
<p>[:alpha:] 任意单个大小写字母；</p>
<p>[:alnum:] 任意单个数字或字母；</p>
<p>[:space:] 任意空白字符；</p>
<p>[:punct:] 任意单个特殊字符；</p>
<ul>
<li>Note：</li>
</ul>
<p>在使用[]应用专用字符集合时，外层也需要嵌套[]。</p>
<p>Example：</p>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#</span> ls -d /etc/*[[:digit:]]*[[:lower:]]</span></pre></div>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-08bash快捷键" class="anchor" aria-hidden="true" href="#08bash快捷键"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-08bash快捷键">08bash快捷键</span></h2>
<h3><a id="user-content-编辑命令" class="anchor" aria-hidden="true" href="#编辑命令"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>编辑命令：</h3>
<ul>
<li>Ctrl + a ：移到命令行首</li>
<li>Ctrl + e ：移到命令行尾</li>
<li>Ctrl + f ：按字符前移（右向）</li>
<li>Ctrl + b ：按字符后移（左向）</li>
<li>Alt + f ：按单词前移（右向）</li>
<li>Alt + b ：按单词后移（左向）</li>
<li>Ctrl + xx：在命令行首和光标之间移动</li>
<li>Ctrl + u ：从光标处删除至命令行首</li>
<li>Ctrl + k ：从光标处删除至命令行尾</li>
<li>Ctrl + w ：从光标处删除至字首</li>
<li>Alt + d ：从光标处删除至字尾</li>
<li>Ctrl + d ：删除光标处的字符</li>
<li>Ctrl + h ：删除光标前的字符</li>
<li>Ctrl + y ：粘贴至光标后</li>
<li>Alt + c ：从光标处更改为首字母大写的单词</li>
<li>Alt + u ：从光标处更改为全部大写的单词</li>
<li>Alt + l ：从光标处更改为全部小写的单词</li>
<li>Ctrl + t ：交换光标处和之前的字符</li>
<li>Alt + t ：交换光标处和之前的单词</li>
<li>Alt + Backspace：与 Ctrl + w 相同类似，分隔符有些差别</li>
</ul>
<h3><a id="user-content-重新执行命令" class="anchor" aria-hidden="true" href="#重新执行命令"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>重新执行命令：</h3>
<ul>
<li>Ctrl + r：逆向搜索命令历史</li>
<li>Ctrl + g：从历史搜索模式退出</li>
<li>Ctrl + p：历史中的上一条命令</li>
<li>Ctrl + n：历史中的下一条命令</li>
<li>Alt + .：使用上一条命令的最后一个参数</li>
</ul>
<h3><a id="user-content-控制命令" class="anchor" aria-hidden="true" href="#控制命令"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>控制命令：</h3>
<ul>
<li>Ctrl + l：清屏</li>
<li>Ctrl + o：执行当前命令，并选择上一条命令</li>
<li>Ctrl + s：阻止屏幕输出</li>
<li>Ctrl + q：允许屏幕输出</li>
<li>Ctrl + c：终止命令</li>
<li>Ctrl + z：挂起命令</li>
</ul>
<h3><a id="user-content-bang--命令" class="anchor" aria-hidden="true" href="#bang--命令"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Bang (!) 命令</h3>
<ul>
<li>!!：执行上一条命令</li>
<li>!blah：执行最近的以 blah 开头的命令，如 !ls</li>
<li>!blah:p：仅打印输出，而不执行</li>
<li>!$：上一条命令的最后一个参数，与 Alt + . 相同</li>
<li>!$:p：打印输出 !$ 的内容</li>
<li>!*：上一条命令的所有参数</li>
<li>!<em>:p：打印输出 !</em> 的内容</li>
<li>^blah：删除上一条命令中的 blah</li>
<li>^blah^foo：将上一条命令中的 blah 替换为 foo</li>
<li>^blah^foo^：将上一条命令中所有的 blah 都替换为 foo</li>
</ul>
<h2><a id="user-content-友情提示" class="anchor" aria-hidden="true" href="#友情提示"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>友情提示：</h2>
<pre><code>以上介绍的大多数 Bash 快捷键仅当在 emacs 编辑模式时有效，

若你将 Bash 配置为 vi 编辑模式，那将遵循 vi 的按键绑定。

Bash 默认为 emacs 编辑模式。

如果你的 Bash 不在 emacs 编辑模式，可通过 set-o emacs 设置。

^S、^Q、^C、^Z 是由终端设备处理的，可用 stty 命令设置。
</code></pre>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-09bash的io重定向及管道" class="anchor" aria-hidden="true" href="#09bash的io重定向及管道"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-09bash的io重定向及管道">09bash的io重定向及管道</span></h2>
<p>打开的文件都有一个fd：file descriptor(文件描述符)</p>
<pre><code>标准输入：keyboard，0

标准输出：monitor，1

标准错误输出：monitor，2
</code></pre>
<p>###I/O重定向：改变标准位置；</p>
<ul>
<li>
<p>输出重定向：</p>
<p>COMMAND &gt; NEW_POS 覆盖重定向，目标文件中的原有内容会被清除；</p>
<p>COMMAND &gt;&gt; NEW_POS 追加重定向，新内容会被追加到目标文件尾部；</p>
</li>
<li>
<p>Note：</p>
<p>为了在输出重定向时防止覆盖原有文件，建议使用以下设置：</p>
<p>set –C ： 禁止将内容覆盖输出(&gt;)至已有文件中,追加输出不受影响；</p>
<p>此时，若确定要将重定向的内容覆盖原有文件，可使用 &gt;| 强制覆盖；</p>
</li>
<li>
<p>Example:</p>
</li>
</ul>
<div class="highlight highlight-source-shell"><pre>[root@localhost test1]<span class="pl-c"><span class="pl-c">#</span> echo "It's dangerous" &gt; ./result.txt #输出到文件；</span>
[root@localhost test1]<span class="pl-c"><span class="pl-c">#</span> cat result.txt</span>
It<span class="pl-s"><span class="pl-pds">'</span>s dangerous</span>
<span class="pl-s">[root@localhost test1]# set –C #禁止将内容覆盖输出到已有文件；</span>
<span class="pl-s">[root@localhost test1]# echo "It<span class="pl-pds">'</span></span>s very dangerous<span class="pl-s"><span class="pl-pds">"</span> &gt; ./result.txt</span>
<span class="pl-s">-bash: ./result.txt: cannot overwrite existing file #提示不能覆盖已存在文件；</span>
<span class="pl-s">[root@localhost test1]# echo <span class="pl-pds">"</span></span>It<span class="pl-s"><span class="pl-pds">'</span>s very dangerous" &gt;| ./result.txt #强制覆盖</span>
<span class="pl-s">[root@localhost test1]#</span>
<span class="pl-s">[root@localhost test1]# set +C #取消禁止覆盖输出到已有文件；</span>
<span class="pl-s">[root@localhost test1]# echo "It<span class="pl-pds">'</span></span>s very dangerous<span class="pl-s"><span class="pl-pds">"</span> &gt; ./result.txt</span>
<span class="pl-s">[root@localhost test1]#</span></pre></div>
<ul>
<li>
<p>错误输出：</p>
<p>2&gt; : 覆盖重定向错误输出数据流；</p>
<p>2&gt;&gt; ：追加重定向错误输出数据流；</p>
</li>
</ul>
<div class="highlight highlight-source-shell"><pre>[root@localhost test1]<span class="pl-c"><span class="pl-c">#</span> lss -l /etc/ 2&gt; ./error.txt</span>
[root@localhost test1]<span class="pl-c"><span class="pl-c">#</span> cat error.txt</span>
-bash: lss: <span class="pl-c1">command</span> not found
[root@localhost test1]<span class="pl-c"><span class="pl-c">#</span> cat /etc/passwd.error 2&gt;&gt; ./error.txt</span>
[root@localhost test1]<span class="pl-c"><span class="pl-c">#</span> cat error.txt</span>
-bash: lss: <span class="pl-c1">command</span> not found
cat: /etc/passwd.error: No such file or directory</pre></div>
<p>将标准输出和标准错误输出各自重定向至不同位置：</p>
<pre><code> COMMAND &gt; /path/to/file.out 2&gt; /path/to/error.out
</code></pre>
<ul>
<li>Example:</li>
</ul>
<pre><code># cat /etc/passwd &gt; ./file.out 2&gt; ./error.out
</code></pre>
<ul>
<li>
<p>合并输出：</p>
<p>合并标准输出和错误输出为同一个数据流进行重定向；</p>
<pre><code>   &amp;&gt; 合并覆盖重定向；

   &amp;&gt;&gt; 合并追加重定向；
</code></pre>
<p>格式为：</p>
<pre><code>   COMMAND &gt; /path/to/file.out 2&gt; &amp;1

   COMMAND &gt;&gt; /path/to/file.out 2&gt;&gt; &amp;1
</code></pre>
<p>Example:</p>
</li>
</ul>
<div class="highlight highlight-source-shell"><pre>    [root@localhost test1]<span class="pl-c"><span class="pl-c">#</span> ls -l /etc/ &gt; ./file.out 2&gt;&amp;1</span>
    [root@localhost test1]<span class="pl-c"><span class="pl-c">#</span> ls -l /etc/ &amp;&gt; file.out</span>
    [root@localhost test1]<span class="pl-c"><span class="pl-c">#</span> ls -l /etcc/ &amp;&gt; file.out</span>
    [root@localhost test1]<span class="pl-c"><span class="pl-c">#</span> cat file.out</span>
    ls: cannot access /etcc/: No such file or directory</pre></div>
<ul>
<li>输入重定向： &lt;</li>
</ul>
<div class="highlight highlight-source-shell"><pre>     HERE Documentation：&lt;&lt;

     <span class="pl-c"><span class="pl-c">#</span> cat &lt;&lt; EOF</span>

     <span class="pl-c"><span class="pl-c">#</span> cat &gt; /path/to/somefile &lt;&lt; EOF</span></pre></div>
<p>Example: 输入重定向，输入完成后显示内容到标准输出上；</p>
<div class="highlight highlight-source-shell"><pre>[root@localhost test1]<span class="pl-c"><span class="pl-c">#</span> cat &lt;&lt; EOF</span>
<span class="pl-k">&gt;</span> my name is kalaguiyin.
<span class="pl-k">&gt;</span> I<span class="pl-s"><span class="pl-pds">'</span>m a tibetan.</span>
<span class="pl-s">&gt; I come from Sichuan Provence.</span>
<span class="pl-s">&gt; EOF</span>
<span class="pl-s">my name is kalaguiyin.</span>
<span class="pl-s">I<span class="pl-pds">'</span></span>m a tibetan.
I come from Sichuan Provence.</pre></div>
<p>Example：从标准输入读取输入并重定向到文件。</p>
<div class="highlight highlight-source-shell"><pre>[root@localhost test1]<span class="pl-c"><span class="pl-c">#</span> cat &gt; hello.txt &lt;&lt; EOF </span>
<span class="pl-k">&gt;</span> this is a <span class="pl-c1">test</span> file.
<span class="pl-k">&gt;</span> 中华人民共和国。
<span class="pl-k">&gt;</span> EOF
[root@localhost test1]<span class="pl-c"><span class="pl-c">#</span> cat hello.txt</span>
this is a <span class="pl-c1">test</span> file.
中华人民共和国。</pre></div>
<ul>
<li>
<p>管道：</p>
<p>COMMAND1 | COMMAND2 | COMMAND3 | …..</p>
<p>作用：前一个命令的执行结果将作为后一个命令执行的参数；</p>
<p>Note:</p>
<pre><code>      最后一个命令会在当前shell进程的子shell进程中执行；
</code></pre>
</li>
</ul>
<div class="highlight highlight-source-shell"><pre>[root@sslinux]<span class="pl-c"><span class="pl-c">#</span> cat /etc/passwd | sort -t: -k3 -n | cut -d: -f1</span>
root
bin
daemon
adm
lp
polkitd
sslinux</pre></div>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-10shell编程环境" class="anchor" aria-hidden="true" href="#10shell编程环境"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-10shell编程环境">10shell编程环境</span></h2>
<ul>
<li>
<p>编程基础知识：</p>
<p>1、程序编程风格：</p>
<pre><code>  过程式：以指令为中心，数据服务于指令；

  对象式：以数据为中心，指令服务于数据；
</code></pre>
<p>shell程序，提供了编程能力，解释执行，shell就是一解释器；</p>
<p>2、程序的执行方式：</p>
<pre><code>  计算机：运行二进制命令；

  编程语言：

      低级：汇编；

      高级：

          编译型语言：高级语言 --&gt;编译器 --&gt; 目标代码；

          解释型语言：高级语言 --&gt;解释器 --&gt; 机器代码；
</code></pre>
<p>3、过程式编程的三种结构；</p>
<pre><code>  顺序执行；

  循环执行；

  选择执行；
</code></pre>
<p>4、shell编程：过程式语言，由解释器解释执行；</p>
<pre><code>  编程语言的基本结构：

     数据存储： 变量、数组；

     表达式；

     语句；
</code></pre>
<p>5、shell脚本：文本文件；</p>
<pre><code>  首行特定格式：

      #!/bin/bash   --&gt; shebang

      魔数：magic number，程序的执行入口，告知本程序由哪一个解释器解释执行；
</code></pre>
<p>6、运行脚本的两种方式：</p>
<pre><code>  a、 给予执行权限，通过具体的文件路径指定文件执行；

  b、 直接运行解释器，将脚本作为解释器程序的参数运行；
</code></pre>
<ul>
<li>Example:</li>
</ul>
</li>
</ul>
<div class="highlight highlight-source-shell"><pre>    [root@localhost test1]<span class="pl-c"><span class="pl-c">#</span> vim test.sh</span>
    [root@localhost test1]<span class="pl-c"><span class="pl-c">#</span> bash test.sh</span>
    hello,girl
    [root@localhost test1]<span class="pl-c"><span class="pl-c">#</span> chmod +x test.sh</span>
    [root@localhost test1]<span class="pl-c"><span class="pl-c">#</span> ./test.sh</span>
    hello,girl</pre></div>
<ul>
<li>
<p>Bash编程：</p>
<p>bash是弱类型编程，变量默认为字符型；</p>
<p>把所有要存储的数据统统当做字符进行存储；</p>
<p>变量不需要事先声明，可以在调用时直接赋值使用，参与运算会自动进行隐式类型转换；</p>
<p>不支持浮点数；</p>
</li>
<li>
<p>逻辑运算：</p>
<p>与：&amp;&amp; 同为1则为1，否则为0；</p>
<p>或：|| 同为0则为0，否则为1；</p>
<p>非：取反，!0为1，!1为0；</p>
<p>短路与运算：双目运算符前面的结果为0，则结果一定为0，后面的不执行；</p>
<p>短路或运算：双目运算符前面的结果为1，则结果一定为1，后面的不执行；</p>
</li>
</ul>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-11bash变量类型" class="anchor" aria-hidden="true" href="#11bash变量类型"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-11bash变量类型">11bash变量类型</span></h2>
<p>变量类型决定了变量的数据存储格式、存储空间大小以及变量能参与的运算种类；</p>
<ul>
<li>
<p>强弱类型语言的区别：</p>
<p>强类型：定义变量时必须执行类型、参与运算必须符合类型要求；调用未声明变量会产生错误；</p>
<p>弱类型：无需指定类型，默认均为字符型；参与运算会自动进行隐式类型转换；变量无需事先定义即可直接调用；</p>
</li>
<li>
<p>Bash中的变量的种类：</p>
</li>
</ul>
<p>根据变量的生效范围等标准划分：</p>
<p>1、本地变量：生效范围为当前shell进程；对当前shell之外的其他shell进程，包括当前shell的子shell进程均无效；</p>
<p>2、环境变量：生效范围为当前shell进程及其子进程；</p>
<p>3、局部变量：生效范围为当前shell进程中某代码片断(通常指函数)</p>
<p>4、位置变量：$1, $2, ...来表示，用于让脚本在脚本代码中调用通过命令行传递给它的参数；</p>
<p>4、特殊变量：$?, $0, $*, $@, $#</p>
<pre><code>     $? : 上一条命令的执行状态结果；
     $0 : 命令本身
     $* : 传递给脚本的所有参数；
     $@ : 传递给脚本的所有参数；
     $# : 传递给脚本的参数的个数；
</code></pre>
<h2><a id="user-content-本地变量" class="anchor" aria-hidden="true" href="#本地变量"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>本地变量：</h2>
<p>1、变量赋值：name='VALUE'</p>
<pre><code>a) 在赋值时，VALUE可以使用以下引用：

   【1】可以是直接字符串；name="username"
   【2】变量引用：name=“$username”
   【3】命令引用：name=`COMMAND`,name=$(COMMAND)
</code></pre>
<p>2、 变量引用：${name},花括号可省略：$name</p>
<pre><code>引号引用：

     " " ： 弱引用，其中的变量引用会被替换为变量值；

     ' ' ： 强引用，其中的变量不会被替换为变量值，而保持原字符串；
</code></pre>
<p>查看所有已定义的变量： #set</p>
<p>销毁变量： # unset name</p>
<h2><a id="user-content-环境变量" class="anchor" aria-hidden="true" href="#环境变量"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>环境变量：</h2>
<pre><code>1、变量声明、赋值：
    export name=VALUE
    declare -x name=VALUE
2、变量引用：
    $name
    ${name}
3、显示所有环境变量：
    export
    env
    printenv
4、销毁环境变量：
    unset name
</code></pre>
<ul>
<li>Bash中内建的环境变量：
PATH，SHELL，UID，HISTSIZE, HOME, PWD, OLD, HISTFILE, PS1</li>
</ul>
<h2><a id="user-content-只读变量" class="anchor" aria-hidden="true" href="#只读变量"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>只读变量：</h2>
<p>相当于常量，变量值不可变，不能再进行赋值运算；</p>
<p>声明只读变量的格式：</p>
<pre><code>readonly name
declare –r name   
</code></pre>
<h2><a id="user-content-位置变量" class="anchor" aria-hidden="true" href="#位置变量"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>位置变量：</h2>
<p>在脚本代码中调用通过命令行传递给脚本的参数；</p>
<pre><code>$1,$2,…. : 对应调用第1、第2等参数；

$0: 命令本身；

$*: 传递给脚本的所有参数；

$@: 传递给脚本的所有参数；

$#: 传递给脚本的参数的个数；
</code></pre>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-12bash的配置文件" class="anchor" aria-hidden="true" href="#12bash的配置文件"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-12bash的配置文件">12bash的配置文件</span></h2>
<p>按生效范围划分，存在两类配置文件：</p>
<p>1、全局配置：</p>
<pre><code>/etc/profile
    /etc/profile.d/*.sh
/etc/bashrc
</code></pre>
<p>2、用户配置：</p>
<pre><code>~/.bash_profile
~/.bashrc
</code></pre>
<p>按功能划分：也存在两类；</p>
<p>1、profile类：为交互式登录的shell提供配置；</p>
<pre><code>交互式登录shell：直接通过终端输入账号密码登录；

使用“su - UserName”或“su -l UserName”切换的用户
</code></pre>
<div class="highlight highlight-source-shell"><pre>    作用于全局：/etc/profile，/etc/profile.d/<span class="pl-k">*</span>.sh

    作用于个人：~/.bash_profile
</pre></div>
<ul>
<li>
<p>功用：</p>
<p>（1）用于定义环境变量；</p>
<p>（2）运行命令或脚本；</p>
</li>
<li>
<p>配置文件加载顺序：(相同参数，后加载的生效)</p>
<pre><code>   /etc/profile --&gt; 
   /etc/profile.d/*.sh --&gt; 
   ~/.bash_profile --&gt; 
   ~/.bashrc --&gt; 
   /etc/bashrc
</code></pre>
</li>
</ul>
<p>2、bashrc类：为非交互式登录的shell提供配置：</p>
<ul>
<li>
<p>非交互式Shell：</p>
<pre><code>   su UserName 
   图形界面下打开的终端
   执行脚本
</code></pre>
</li>
</ul>
<div class="highlight highlight-source-shell"><pre>    作用于全局：/etc/bashrc
    作用于个人：~/.bashrc</pre></div>
<ul>
<li>
<p>功用：</p>
<p>（1）	定义命令别名；</p>
<p>（2）	定义本地变量；</p>
</li>
<li>
<p>配置文件加载顺序：（相同参数，后加载的生效）</p>
<p>~/.bashrc --&gt; /etc/bashrc --&gt; /etc/profile.d/*.sh</p>
</li>
<li>
<p>编辑配置文件后让定义的新配置生效的方式：</p>
<p>(1) 重新启动shell进程；</p>
<p>(2) 使用source或点命令(　．)进程；</p>
</li>
</ul>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-13bash中的算术运算符" class="anchor" aria-hidden="true" href="#13bash中的算术运算符"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-13bash中的算术运算符">13bash中的算术运算符</span></h2>
<p>+，-，*，/，%，**</p>
<p>实现算术运算的方式：</p>
<pre><code>(1) let var=算术表达式
(2) var=$[算术表达式]
(3) var=$((算术表达式))
(4) var=$(expr arg1 arg2 arg3...)
</code></pre>
<p>乘法符号在有些场景中需要转义；</p>
<ul>
<li>
<p>bash内建随机数生成器：$RANDOM</p>
</li>
<li>
<p>增强型赋值：
+=，-=，*=，/=，%=</p>
<p>let varOPERvalue：</p>
<pre><code>  例如：letcount+=1
</code></pre>
</li>
<li>
<p>自增，自减：</p>
<p>let var+=1</p>
<pre><code>  let var++
</code></pre>
<p>let var-=1</p>
<pre><code>  let var--
</code></pre>
</li>
<li>
<p>Example:</p>
</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
spaceline1=<span class="pl-s"><span class="pl-pds">$(</span>grep <span class="pl-s"><span class="pl-pds">"</span>^[[:space:]]*$<span class="pl-pds">"</span></span> <span class="pl-smi">$1</span> <span class="pl-k">|</span> wc -l<span class="pl-pds">)</span></span>
spaceline2=<span class="pl-s"><span class="pl-pds">$(</span>grep <span class="pl-s"><span class="pl-pds">"</span>^[[:space:]]*$<span class="pl-pds">"</span></span> <span class="pl-smi">$2</span> <span class="pl-k">|</span> wc -l<span class="pl-pds">)</span></span>
<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>The sum of space line:$[<span class="pl-smi">$spaceline1</span>+<span class="pl-smi">$spaceline2</span>]<span class="pl-pds">"</span></span></pre></div>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-14bash条件测试" class="anchor" aria-hidden="true" href="#14bash条件测试"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-14bash条件测试">14bash条件测试</span></h2>
<p>判断某需求是否满足，需要有测试机制来实现；</p>
<ul>
<li>
<p>Note：专用的测试表达式需要由测试命令辅助完成测试过程；</p>
</li>
<li>
<p>测试命令：</p>
</li>
</ul>
<p>test EXPRESSION</p>
<p>[ EXPRESSION ]</p>
<p>[[ EXPRESSION ]]</p>
<pre><code>Note: EXPRESSION前后必须有空白字符，否则报错；
</code></pre>
<h2><a id="user-content-bash的测试类型" class="anchor" aria-hidden="true" href="#bash的测试类型"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Bash的测试类型：</h2>
<ul>
<li>数值测试：</li>
</ul>
<p>-gt : 是否大于； &gt;</p>
<p>-ge：是否大于等于； &gt;=</p>
<p>-eq：是否等于 ==</p>
<p>-ne：是否不能于 !=</p>
<p>-lt ：是否小于 &lt;</p>
<p>-le ：是否小于等于； &lt;=</p>
<ul>
<li>字符串测试：</li>
</ul>
<div class="highlight highlight-source-shell"><pre>     == <span class="pl-c1">:</span> 是否等于；

     <span class="pl-k">&gt;</span>: 是否大于；

     <span class="pl-k">&lt;</span>: 是否小于；

     <span class="pl-k">!</span>= ： 是否不等于；

     =<span class="pl-k">~</span> ：左侧字符串是否能够被右侧的PATTERN所匹配；

     - Note：此表达式一般用于[[ ]]中；

     -z “STRING” <span class="pl-c1">:</span> 测试字符串是否为空，空则为真，不空则为假；

     -n “STRING” ：测试字符串是否不空，不空则为真，空则为假；</pre></div>
<p>Note：在字符串比较时用到的操作数都应该使用引号；</p>
<h2><a id="user-content-文件测试" class="anchor" aria-hidden="true" href="#文件测试"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>文件测试：</h2>
<ul>
<li>
<p>(a) 存在性测试：</p>
<p>-a FILE</p>
<p>-e FILE：文件存在性测试，存在为真，否则为假；</p>
</li>
<li>
<p>(b) 存在性及类别测试</p>
<p>-b FILE ：是否存在且为块设备文件；</p>
<p>-c FILE ：是否存在且为字符设备文件；</p>
<p>-d FILE ：是否存在且为目录文件；</p>
<p>-f FILE ：是否存在且为普通文件；</p>
<p>-h FILE 或 –L FILE：是否存在且为符号链接文件；</p>
<p>-p FILE：是否存在且为命名管道文件；</p>
<p>-S FILE ：是否存在且为套接字文件；</p>
</li>
<li>
<p>(c) 文件权限测试：</p>
<p>-r FILE：是否存在且可读</p>
<p>-w FILE: 是否存在且可写</p>
<p>-x FILE: 是否存在且可执行</p>
</li>
<li>
<p>(d) 文件特殊权限测试：</p>
<p>-g FILE：是否存在且拥有sgid权限；</p>
<p>-u FILE：是否存在且拥有suid权限；</p>
<p>-k FILE：是否存在且拥有sticky权限；</p>
</li>
<li>
<p>(e) 文件大小测试：</p>
<p>-s FILE：是否存在且非空；</p>
</li>
<li>
<p>(f) 文件是否打开：</p>
<p>-t fd：fd表示文件描述符是否已经打开且与某终端相关</p>
<p>-N FILE：文件自从上一次被读取之后是否被修改过；</p>
<p>-O FILE：当前有效用户是否为文件属主；</p>
<p>-G FILE：当前有效用户是否为文件属组；</p>
</li>
<li>
<p>(g) 双目测试：</p>
<p>FILE1 –ef FILE2 ： FILE1与FILE2是否指向同一个设备上的相同inode；</p>
<p>FILE1 –nt FILE2 ：FILE是否新于FILE2；</p>
<p>FILE1 –ot FILE2 ：FILE1是否旧于FILE2；</p>
</li>
<li>
<p>(h) 组合测试条件：</p>
</li>
</ul>
<p>完成逻辑运算：</p>
<pre><code> 第一种方式：

         COMMAND1 &amp;&amp; COMMAND2

         COMMAND1 || COMMAND2

         !COMMAND

     eg：[ -e FILE ] &amp;&amp; [ -r FILE ] 文件是否存在且是否有读权限；


 第二种方式：

         EXPRESSION1 –a EXPRESSION2

         EXPRESSION1 –o EXPRESSION2

         !EXPRESSION

 必须使用测试命令进行；
</code></pre>
<ul>
<li>Example：</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#</span> [ -z "$hostName" -o "$hostName"=="localhost.localdomain" ] &amp;&amp; hostname www.studyhard.com</span>
<span class="pl-c"><span class="pl-c">#</span> -z判断hostName是否为空，-o表示或者，即：hostName为空或者值为localhot.localdomain的时候，使用hostname命令修改主机名；</span>
[root@localhost kalaguiyin]<span class="pl-c"><span class="pl-c">#</span> hostname</span>
www.studyhard.com</pre></div>
<ul>
<li>Example:</li>
</ul>
<div class="highlight highlight-source-shell"><pre>[root@kalaguiyin <span class="pl-k">~</span>]<span class="pl-c"><span class="pl-c">#</span> [ -f /bin/cat -a -x /bin/cat ] &amp;&amp; cat /etc/fstab</span>
<span class="pl-c"><span class="pl-c">#</span>判断文件/bin/cat是否存在且是否有可执行权限，&amp;&amp;是短路与，如果前面执行结果为真则使用cat命令#查看文件；</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span> /etc/fstab</span>
<span class="pl-c"><span class="pl-c">#</span> Created by anaconda on Fri Jul 3 03:08:29 2015</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span> Accessible filesystems, by reference, are maintained under '/dev/disk'</span>
<span class="pl-c"><span class="pl-c">#</span> See man pages fstab(5), findfs(8), mount(8) and/or blkid(8) for more info</span>
<span class="pl-c"><span class="pl-c">#</span></span>
/dev/mapper/centos-root / xfs defaults 0 0
UUID=3d04d82b-c52b-4184-8d64-1826db6e2eac /boot xfs defaults 0 0
/dev/mapper/centos-home /home xfs defaults 0 0
/dev/mapper/centos-swap swap swap defaults 0 0</pre></div>
<ul>
<li>快速查找选项定义的方法：</li>
</ul>
<p>man bash --&gt; /^[[:space:]]*-f</p>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#</span> [ -f /bin/cat -a -x /bin/cat ] &amp;&amp; cat /etc/fstab </span>
<span class="pl-c"><span class="pl-c">#</span>如果文件存在且有执行权限，就用它查看文件内容；</span></pre></div>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-15bash脚本编程之用户交互" class="anchor" aria-hidden="true" href="#15bash脚本编程之用户交互"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-15bash脚本编程之用户交互">15bash脚本编程之用户交互</span></h2>
<ul>
<li>
<p>read命令：</p>
<p>read [option]… [name….]</p>
<pre><code>   -p “prompt” 提示符；

   -t TIMEOUT 用户输入超时时间；
</code></pre>
</li>
<li>
<p>检测脚本中的语法错误：</p>
<pre><code>   bash –n /path/to/some_script
</code></pre>
</li>
<li>
<p>调试执行，查看执行流程：</p>
<pre><code>   bash –x /path/to/some_script
</code></pre>
</li>
<li>
<p>Example:</p>
</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>Description: Test read command's grammer.</span>
<span class="pl-c1">read</span> -t 50 -p <span class="pl-s"><span class="pl-pds">"</span>Enter a disk special file:<span class="pl-pds">"</span></span> diskfile <span class="pl-c"><span class="pl-c">#</span>将用户输入的内容赋值给diskfile变量</span>
[ <span class="pl-k">-z</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$diskfile</span><span class="pl-pds">"</span></span> ] <span class="pl-k">&amp;&amp;</span> <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Fool<span class="pl-pds">"</span></span> <span class="pl-k">&amp;&amp;</span> <span class="pl-c1">exit</span> 1
<span class="pl-c"><span class="pl-c">#</span>判断diskfile的值是否为空，如果为空则输出，并退出；</span>
<span class="pl-k">if</span> fdisk -l <span class="pl-k">|</span> grep <span class="pl-s"><span class="pl-pds">"</span>^Disk <span class="pl-smi">$diskfile</span><span class="pl-pds">"</span></span> <span class="pl-k">&amp;</span><span class="pl-k">&gt;</span> /dev/null<span class="pl-k">;</span><span class="pl-k">then</span>
 fdisk -l <span class="pl-smi">$diskfile</span>
<span class="pl-k">else</span>
 <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Wrong disk special file.<span class="pl-pds">"</span></span>
 <span class="pl-c1">exit</span> 2
<span class="pl-k">fi</span></pre></div>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-16流程控制" class="anchor" aria-hidden="true" href="#16流程控制"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-16流程控制">16流程控制</span></h2>
<h3><a id="user-content-if语句" class="anchor" aria-hidden="true" href="#if语句"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-if语句">if语句</span></h3>
<pre><code>if语句：
     CONDITION：
     bash命令：
</code></pre>
<p>用命令的执行状态结果：</p>
<pre><code> 成功：true，即执行状态结果值为0时；

 失败：false，即执行状态结果为1-255时；
</code></pre>
<p>成功或失败的定义：取决于用到的命令；</p>
<ul>
<li>单分支if：</li>
</ul>
<pre><code> if CONDITION；then
     if-true(条件为真时的执行语句集合)
 fi
</code></pre>
<ul>
<li>Example:</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span>if单分支语句测试；</span>
<span class="pl-k">if</span> [ <span class="pl-smi">$UID</span> <span class="pl-k">-eq</span> 0 ]<span class="pl-k">;</span><span class="pl-k">then</span>
     <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>It's amdinistrator.<span class="pl-pds">"</span></span>
<span class="pl-k">fi</span></pre></div>
<ul>
<li>双分支if：</li>
</ul>
<pre><code> if CONDITION;then
     if-true
 else
     if-false
 fi
</code></pre>
<ul>
<li>Example:</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>if双分支语句测试；</span>
<span class="pl-k">if</span> [ <span class="pl-smi">$UID</span> <span class="pl-k">-eq</span> 0 ]<span class="pl-k">;</span><span class="pl-k">then</span>
 <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>It's administrator.<span class="pl-pds">"</span></span>
<span class="pl-k">else</span>
 <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>It's Comman User.<span class="pl-pds">"</span></span>
<span class="pl-k">fi</span></pre></div>
<ul>
<li>多分支if：</li>
</ul>
<pre><code> if CONDITION1；then
     if-true
 elif CONDITION2;then
     if-true
 elif CONDITION3;then
     if-true
 ….
 else
     all-false
 fi
</code></pre>
<p>逐条件进行判断，第一次遇为“真”条件时，执行其分支，而后结束；</p>
<ul>
<li>Exmaple:用户键入文件路径，脚本来判断文件类型；</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>if语句多分支语句；</span>
<span class="pl-c1">read</span> -t 20 -p <span class="pl-s"><span class="pl-pds">"</span>Enter a file path:<span class="pl-pds">"</span></span> filename

<span class="pl-k">if</span> [ <span class="pl-k">-z</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$filename</span><span class="pl-pds">"</span></span> ]<span class="pl-k">;</span><span class="pl-k">then</span> <span class="pl-c"><span class="pl-c">#</span>判断变量是否为空；</span>
 <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Usage:Enter a file path.<span class="pl-pds">"</span></span>
 <span class="pl-c1">exit</span> 2
<span class="pl-k">fi</span>

<span class="pl-k">if</span> [ <span class="pl-k">!</span> <span class="pl-k">-e</span> <span class="pl-smi">$filename</span> ]<span class="pl-k">;</span><span class="pl-k">then</span> <span class="pl-c"><span class="pl-c">#</span>判断用户输入的文件是否存在；</span>
 <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>No such file.<span class="pl-pds">"</span></span>
 <span class="pl-c1">exit</span> 3
<span class="pl-k">fi</span>

<span class="pl-k">if</span> [ <span class="pl-k">-f</span> <span class="pl-smi">$filename</span> ]<span class="pl-k">;</span><span class="pl-k">then</span> <span class="pl-c"><span class="pl-c">#</span>判断是否为普通文件；</span>
 <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>A common file.<span class="pl-pds">"</span></span>
<span class="pl-k">elif</span> [ <span class="pl-k">-d</span> <span class="pl-smi">$filename</span> ]<span class="pl-k">;</span><span class="pl-k">then</span> <span class="pl-c"><span class="pl-c">#</span>判断是否为目录；</span>
 <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>A directory<span class="pl-pds">"</span></span>
<span class="pl-k">elif</span> [ <span class="pl-k">-L</span> <span class="pl-smi">$filename</span> ]<span class="pl-k">;</span><span class="pl-k">then</span> <span class="pl-c"><span class="pl-c">#</span>判断是否为链接文件；</span>
 <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>A symbolic file.<span class="pl-pds">"</span></span>
<span class="pl-k">else</span>
 <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Other type.<span class="pl-pds">"</span></span>
<span class="pl-k">fi</span></pre></div>
<h3><a id="user-content-for循环" class="anchor" aria-hidden="true" href="#for循环"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-for循环">for循环</span></h3>
<p>循环体：要执行的代码，可能要执行n遍；</p>
<p>循环需具备进入循环的条件和退出循环的条件；</p>
<ul>
<li>for循环：</li>
</ul>
<pre><code> for 变量名 in 列表；do
     循环体
 done
</code></pre>
<ul>
<li>
<p>执行机制：</p>
<p>依次将列表中的元素赋值给“变量”；每次赋值后即执行一次循环体；直到列表中的元素耗尽，循环结束；</p>
</li>
<li>
<p>EXAMPLE：添加10个用户，用户名为：user1-user10：密码同用户名；</p>
</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>for循环，使用列表；</span>
<span class="pl-c"><span class="pl-c">#</span>添加10个用户，user1-user10</span>

<span class="pl-k">if</span> [ <span class="pl-k">!</span> <span class="pl-smi">$UID</span> <span class="pl-k">-eq</span> 0 ]<span class="pl-k">;</span><span class="pl-k">then</span> <span class="pl-c"><span class="pl-c">#</span>判断执行脚本的是否为root用户，若不是则直接退出；</span>
	<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Only root can use this script.<span class="pl-pds">"</span></span>
	<span class="pl-c1">exit</span> 1
<span class="pl-k">fi</span>

<span class="pl-k">for</span> <span class="pl-smi">i</span> <span class="pl-k">in</span> {1..10}<span class="pl-k">;</span><span class="pl-k">do</span>
	<span class="pl-k">if</span> id user<span class="pl-smi">$i</span> <span class="pl-k">&amp;</span><span class="pl-k">&gt;</span> /dev/null<span class="pl-k">;</span><span class="pl-k">then</span>	<span class="pl-c"><span class="pl-c">#</span>判断用户是否已经存在；</span>
		<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>user<span class="pl-smi">$i</span> exists<span class="pl-pds">"</span></span>
	<span class="pl-k">else</span>
		useradd user<span class="pl-smi">$i</span>
		<span class="pl-k">if</span> [ <span class="pl-smi">$?</span> <span class="pl-k">-eq</span> 0 ]<span class="pl-k">;</span><span class="pl-k">then</span>   <span class="pl-c"><span class="pl-c">#</span>判断前一条命令是否执行成功；</span>
			<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>user<span class="pl-smi">$i</span><span class="pl-pds">"</span></span> <span class="pl-k">|</span> passwd --stdin user<span class="pl-smi">$i</span> <span class="pl-k">&amp;</span><span class="pl-k">&gt;</span> /dev/null
			<span class="pl-c"><span class="pl-c">#</span>passwd命令从标准输入获得命令，即管道前命令的执行结果；</span>
		<span class="pl-k">fi</span>
	<span class="pl-k">fi</span>
<span class="pl-k">done</span></pre></div>
<ul>
<li>
<p>列表生成方式：</p>
<p>(1) 直接给出列表 for i in {kalaguiyin johnson rechard}</p>
<p>(2) 整数列表</p>
<pre><code>  (a) {start..end}

  (b) $(seq [start [step]] end)
</code></pre>
<p>(3) 返回列表的命令</p>
<pre><code>  $(COMMAND) --&gt; 如：$(ls /var)
</code></pre>
<p>(4) glob</p>
<pre><code>  /etc/rc.d/rc3.d/K*
</code></pre>
<p>(5) 变量引用</p>
<pre><code>  $@ , $*  --&gt;所有向脚本传递的参数；
</code></pre>
</li>
<li>
<p>Example：判断某路径下所有文件的类型：</p>
</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>for循环使用命令返回列表；</span>

<span class="pl-k">for</span> <span class="pl-smi">file</span> <span class="pl-k">in</span> <span class="pl-s"><span class="pl-pds">$(</span>ls /var<span class="pl-pds">)</span></span><span class="pl-k">;</span><span class="pl-k">do</span> <span class="pl-c"><span class="pl-c">#</span>使用命令生成列表；</span>
 <span class="pl-k">if</span> [ <span class="pl-k">-f</span> /var/<span class="pl-smi">$file</span> ]<span class="pl-k">;</span><span class="pl-k">then</span>
     <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Common file.<span class="pl-pds">"</span></span>
 <span class="pl-k">elif</span> [ <span class="pl-k">-L</span> /var/<span class="pl-smi">$file</span> ]<span class="pl-k">;</span><span class="pl-k">then</span>
     <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Symbolic file.<span class="pl-pds">"</span></span>
 <span class="pl-k">elif</span> [ <span class="pl-k">-d</span> /var/<span class="pl-smi">$file</span> ]<span class="pl-k">;</span><span class="pl-k">then</span>
     <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Directory.<span class="pl-pds">"</span></span>
 <span class="pl-k">else</span>
     <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Other type<span class="pl-pds">"</span></span>
 <span class="pl-k">fi</span>
<span class="pl-k">done</span></pre></div>
<ul>
<li>Example：使用for循环统计关于tcp端口监听状态；</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>使用for循环过滤netstat命令中关于tcp的信息；</span>
<span class="pl-k">declare</span> -i estab=0
<span class="pl-k">declare</span> -i listen=0
<span class="pl-k">declare</span> -i other=0

<span class="pl-k">for</span> <span class="pl-smi">state</span> <span class="pl-k">in</span> <span class="pl-s"><span class="pl-pds">$(</span> netstat -tan <span class="pl-k">|</span> grep <span class="pl-s"><span class="pl-pds">"</span>^tcp\&gt;<span class="pl-pds">"</span></span> <span class="pl-k">|</span> awk <span class="pl-s"><span class="pl-pds">'</span>{print $NF}<span class="pl-pds">'</span></span><span class="pl-pds">)</span></span><span class="pl-k">;</span><span class="pl-k">do</span>

 <span class="pl-k">if</span> [ <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$state</span><span class="pl-pds">"</span></span> <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">'</span>ESTABLISHED<span class="pl-pds">'</span></span> ]<span class="pl-k">;</span><span class="pl-k">then</span>
     <span class="pl-c1">let</span> estab++
 <span class="pl-k">elif</span> [ <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$state</span><span class="pl-pds">"</span></span> <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">'</span>LISTEN<span class="pl-pds">'</span></span> ]<span class="pl-k">;</span><span class="pl-k">then</span>
     <span class="pl-c1">let</span> listen++
 <span class="pl-k">else</span>
     <span class="pl-c1">let</span> other++
 <span class="pl-k">fi</span>
<span class="pl-k">done</span>

<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>ESTABLISHED:<span class="pl-smi">$estab</span><span class="pl-pds">"</span></span>
<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>LISTEN:<span class="pl-smi">$listen</span><span class="pl-pds">"</span></span>
<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Unknow:<span class="pl-smi">$other</span><span class="pl-pds">"</span></span></pre></div>
<ul>
<li>Example: 通过ping命令探测192.168.0.1-254范围内的所有主机的在线状态；</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>通过ping命令探测192.168.0.1-254范围内的所有主机的在线状态；</span>
net=<span class="pl-s"><span class="pl-pds">'</span>192.168.0<span class="pl-pds">'</span></span>
uphosts=0
donwhosts=0

<span class="pl-k">for</span> <span class="pl-smi">i</span> <span class="pl-k">in</span> {1..254}<span class="pl-k">;</span><span class="pl-k">do</span>
 ping -c 1 -w 1 <span class="pl-smi">${net}</span>.<span class="pl-smi">${i}</span> <span class="pl-k">&amp;</span><span class="pl-k">&gt;</span> /dev/null
 <span class="pl-k">if</span> [ <span class="pl-smi">$?</span> <span class="pl-k">-eq</span> 0 ]<span class="pl-k">;</span><span class="pl-k">then</span>
     <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">${net}</span>.<span class="pl-smi">${i}</span> is up.<span class="pl-pds">"</span></span>
     <span class="pl-c1">let</span> uphosts++
 <span class="pl-k">else</span>
     <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">${net}</span>.<span class="pl-smi">${i}</span> is down.<span class="pl-pds">"</span></span>
     <span class="pl-c1">let</span> downhosts++
 <span class="pl-k">fi</span>
<span class="pl-k">done</span>

<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Up hosts:<span class="pl-smi">$uphosts</span>.<span class="pl-pds">"</span></span>
<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Down hosts:<span class="pl-smi">$downhosts</span>.<span class="pl-pds">"</span></span></pre></div>
<h3><a id="user-content-while循环" class="anchor" aria-hidden="true" href="#while循环"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-while循环">while循环</span></h3>
<p>语法：</p>
<pre><code> while CONDITION；do
     循环体
 done
</code></pre>
<pre><code>CONDITION：循环控制条件；进入循环之前，先做一次判断；
每一次循环之后会再次做判断；条件为“true”，则执行一次循环；
直到条件测试状态为“false”终止循环；

因此：CONDTION一般应该有循环控制变量；
而此变量的值会在循环体不断地被修正，直到最终条件为false，结束循环。
</code></pre>
<ul>
<li>Example：用while求100以内所有正整数之和：</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span>使用while求100以内正整数之和；</span>
<span class="pl-k">declare</span> -i sum=0
<span class="pl-k">declare</span> -i i=1
<span class="pl-k">while</span> [ <span class="pl-smi">$i</span> <span class="pl-k">-le</span> 100 ]<span class="pl-k">;</span><span class="pl-k">do</span>
 <span class="pl-c1">let</span> sum+=<span class="pl-smi">$i</span>
 <span class="pl-c1">let</span> i++
<span class="pl-k">done</span>
<span class="pl-c1">echo</span> <span class="pl-smi">$i</span>
<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Summary:<span class="pl-smi">$sum</span>.<span class="pl-pds">"</span></span></pre></div>
<ul>
<li>Example：用while添加10个用户，user1-user10；</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>使用while循环添加10个用户；</span>
<span class="pl-k">declare</span> -i i=1
<span class="pl-k">declare</span> -i users=0

<span class="pl-k">while</span> [ <span class="pl-smi">$i</span> <span class="pl-k">-le</span> 10 ]<span class="pl-k">;</span><span class="pl-k">do</span>
 <span class="pl-k">if</span> <span class="pl-k">!</span> id user<span class="pl-smi">$i</span> <span class="pl-k">&amp;</span><span class="pl-k">&gt;</span> /dev/null<span class="pl-k">;</span><span class="pl-k">then</span>
     useradd user<span class="pl-smi">$i</span>
     <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Add user: user<span class="pl-smi">$i</span><span class="pl-pds">"</span></span>
     <span class="pl-c1">let</span> users++
 <span class="pl-k">fi</span>
 <span class="pl-c1">let</span> i++
<span class="pl-k">done</span>
<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Add <span class="pl-smi">$users</span> users.<span class="pl-pds">"</span></span></pre></div>
<ul>
<li>Example：使用while循环ping指定网络内的所有主机；</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>使用while循环ping指定网段内的所有主机；</span>
<span class="pl-k">declare</span> -i i=1
<span class="pl-k">declare</span> -i uphosts=0
<span class="pl-k">declare</span> -i downhosts=0
net=<span class="pl-s"><span class="pl-pds">'</span>172.16.250<span class="pl-pds">'</span></span>

<span class="pl-k">while</span> [ <span class="pl-smi">$i</span> <span class="pl-k">-le</span> 254 ]<span class="pl-k">;</span><span class="pl-k">do</span>
 <span class="pl-k">if</span> ping -c 1 -w 1 <span class="pl-smi">${net}</span>.<span class="pl-smi">${i}</span> <span class="pl-k">&amp;</span><span class="pl-k">&gt;</span> /dev/null<span class="pl-k">;</span><span class="pl-k">then</span>
     <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">${net}</span>.<span class="pl-smi">$i</span> is up.<span class="pl-pds">"</span></span>
     <span class="pl-c1">let</span> uphosts++
 <span class="pl-k">else</span>
     <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">${net}</span>.<span class="pl-smi">$i</span> is down.<span class="pl-pds">"</span></span>
     <span class="pl-c1">let</span> downhosts++
 <span class="pl-k">fi</span>
 <span class="pl-c1">let</span> i++
<span class="pl-k">done</span>

<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Up hosts:<span class="pl-smi">$uphosts</span>.<span class="pl-pds">"</span></span>
<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Down hosts:<span class="pl-smi">$downhosts</span>.<span class="pl-pds">"</span></span></pre></div>
<ul>
<li>Example：使用for循环打印九九乘法表；</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span>使用for循环打印九九乘法表；</span>

<span class="pl-k">for</span> <span class="pl-smi">j</span> <span class="pl-k">in</span> {1..9}<span class="pl-k">;</span><span class="pl-k">do</span>
 <span class="pl-k">for</span> <span class="pl-smi">i</span> <span class="pl-k">in</span> <span class="pl-s"><span class="pl-pds">$(</span>seq 1 <span class="pl-smi">$j</span><span class="pl-pds">)</span></span><span class="pl-k">;</span><span class="pl-k">do</span>
     <span class="pl-c1">echo</span> -e -n <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">${i}</span>X<span class="pl-smi">${j}</span>=$[<span class="pl-smi">$i</span>*<span class="pl-smi">$j</span>]\t<span class="pl-pds">"</span></span>
 <span class="pl-k">done</span>
 <span class="pl-c1">echo</span>
<span class="pl-k">done</span></pre></div>
<ul>
<li>Example：使用while循环打印九九乘法表；</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-k">declare</span> -i i=1
<span class="pl-k">declare</span> -i j=1

<span class="pl-k">while</span> [ <span class="pl-smi">$j</span> <span class="pl-k">-le</span> 9 ]<span class="pl-k">;</span><span class="pl-k">do</span>
 <span class="pl-k">while</span> [ <span class="pl-smi">$i</span> <span class="pl-k">-le</span> <span class="pl-smi">$j</span> ]<span class="pl-k">;</span><span class="pl-k">do</span>
     <span class="pl-c1">echo</span> -e -n <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">${i}</span>X<span class="pl-smi">${j}</span>=$[<span class="pl-smi">$i</span>*<span class="pl-smi">$j</span>]\t<span class="pl-pds">"</span></span>
     <span class="pl-c1">let</span> i++
 <span class="pl-k">done</span>

 <span class="pl-c1">echo</span>
 <span class="pl-c1">let</span> i=1
 <span class="pl-c1">let</span> j++
<span class="pl-k">done</span></pre></div>
<ul>
<li>Example：利用RANDOM生成10个随机数字，输出这10个数字，并显示其中的最大者和最小者；</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>利用RANDOM生成10个随机数，输出，并求最大值和最小值；</span>
<span class="pl-k">declare</span> -i max=0
<span class="pl-k">declare</span> -i min=0
<span class="pl-k">declare</span> -i i=1

<span class="pl-k">while</span> [ <span class="pl-smi">$i</span> <span class="pl-k">-le</span> 9 ]<span class="pl-k">;</span><span class="pl-k">do</span>
	rand=<span class="pl-smi">$RANDOM</span>
	<span class="pl-c1">echo</span> <span class="pl-smi">$rand</span>
	
	<span class="pl-k">if</span> [ <span class="pl-smi">$i</span> <span class="pl-k">-eq</span> 1 ]<span class="pl-k">;</span><span class="pl-k">then</span>
		max=<span class="pl-smi">$rand</span>
		min=<span class="pl-smi">$rand</span>
	<span class="pl-k">fi</span>

	<span class="pl-k">if</span> [ <span class="pl-smi">$rand</span> <span class="pl-k">-gt</span> <span class="pl-smi">$max</span> ]<span class="pl-k">;</span><span class="pl-k">then</span>
		max=<span class="pl-smi">$rand</span>
	<span class="pl-k">fi</span>
	<span class="pl-k">if</span> [ <span class="pl-smi">$rand</span> <span class="pl-k">-lt</span> <span class="pl-smi">$min</span> ]<span class="pl-k">;</span><span class="pl-k">then</span>
		min=<span class="pl-smi">$rand</span>
	<span class="pl-k">fi</span>
	<span class="pl-c1">let</span> i++
<span class="pl-k">done</span>

<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>MAX:<span class="pl-smi">$max</span>.<span class="pl-pds">"</span></span>
<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>MIN:<span class="pl-smi">$min</span>.<span class="pl-pds">"</span></span>
</pre></div>
<h3><a id="user-content-until循环" class="anchor" aria-hidden="true" href="#until循环"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-until循环">until循环</span></h3>
<pre><code>until CONDITION；do
    循环体
done
#进入条件：false
#退出条件：true

</code></pre>
<pre><code>while CONDITION；do
    循环体
done
#进入条件：CONDITION为true；
#退出条件：CONDITION为false；
</code></pre>
<ul>
<li>Example：用until求100以内所有正整数之和：</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>利用until循环求100以内所有正整数之和；</span>
<span class="pl-k">declare</span> -i i=1
<span class="pl-k">declare</span> -i sum=0

<span class="pl-k">until</span> [ <span class="pl-smi">$i</span> <span class="pl-k">-gt</span> 100 ]<span class="pl-k">;</span><span class="pl-k">do</span>
	<span class="pl-c1">let</span> sum+=<span class="pl-smi">$i</span>
	<span class="pl-c1">let</span> i++
<span class="pl-k">done</span>
<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>100以内所有正整数之和为：<span class="pl-pds">"</span></span>
<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Sum:<span class="pl-smi">$sum</span><span class="pl-pds">"</span></span>
</pre></div>
<ul>
<li>Example：用until循环打印九九乘法表；</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>使用until循环打印九九乘法表；</span>

<span class="pl-k">declare</span> -i j=1
<span class="pl-k">declare</span> -i i=1

<span class="pl-k">until</span> [ <span class="pl-smi">$j</span> <span class="pl-k">-gt</span> 9 ]<span class="pl-k">;</span><span class="pl-k">do</span>
	<span class="pl-k">until</span> [ <span class="pl-smi">$i</span> <span class="pl-k">-gt</span> <span class="pl-smi">$j</span> ]<span class="pl-k">;</span><span class="pl-k">do</span>
		<span class="pl-c1">echo</span> -n -e <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">${i}</span>X<span class="pl-smi">${j}</span>=$[<span class="pl-smi">$i</span>*<span class="pl-smi">$j</span>]\t<span class="pl-pds">"</span></span>
		<span class="pl-c1">let</span> i++
	<span class="pl-k">done</span>
	<span class="pl-c1">echo</span>
	<span class="pl-c1">let</span> i=1
	<span class="pl-c1">let</span> j++
<span class="pl-k">done</span>
</pre></div>
<h3><a id="user-content-循环控制语句" class="anchor" aria-hidden="true" href="#循环控制语句"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-循环控制语句">循环控制语句</span></h3>
<p>循环控制语句，用于循环体中；</p>
<ul>
<li>1.continue [N] : 提前结束第N层的本轮循环，而直接进入下一轮判断；</li>
</ul>
<pre><code>while CONDITION1；do
    COMMAND1
    …..
    if CONDITION2;then
	continue
    fi
    COMMANDn
    ….
done
</code></pre>
<ul>
<li>2.break [N] : 提前结束循环；</li>
</ul>
<pre><code>while CONDITION1;do
    CMD1
    ….
    if CONDITION2;then
        break
    fi
    CMDn
    …
done

</code></pre>
<ul>
<li>Example:求100以内所有偶数之和：要求循环遍历100以内的所有正整数；</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>求100以内所有偶数之和，使用continue跳过奇数；</span>
<span class="pl-k">declare</span> -i i=0
<span class="pl-k">declare</span> -i sum=0

<span class="pl-k">until</span> [ <span class="pl-smi">$i</span> <span class="pl-k">-gt</span> 100 ]<span class="pl-k">;</span><span class="pl-k">do</span>
	<span class="pl-c1">let</span> i++
	<span class="pl-k">if</span> [ $[<span class="pl-smi">$i</span>%2] <span class="pl-k">-eq</span> 1 ]<span class="pl-k">;</span><span class="pl-k">then</span>
		<span class="pl-k">continue</span>
	<span class="pl-k">fi</span>
	<span class="pl-c1">let</span> sum+=<span class="pl-smi">$i</span>
<span class="pl-k">done</span>

<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Even sum:<span class="pl-smi">$sum</span><span class="pl-pds">"</span></span>
</pre></div>
<h3><a id="user-content-创建死循环" class="anchor" aria-hidden="true" href="#创建死循环"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-创建死循环">创建死循环</span></h3>
<pre><code>while true;do
	循环体
done
</code></pre>
<pre><code>until false；do
	循环体
done

</code></pre>
<ul>
<li>Example：每隔3秒钟到系统上获取已经登录的用户信息；如果用户输入的用户名登录了，则记录于日志中，并退出；</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>用while造成死循环，在系统上每隔3秒判断一次用户输入的用户名是否登录；</span>
<span class="pl-c1">read</span> -p <span class="pl-s"><span class="pl-pds">"</span>Enter a user name:<span class="pl-pds">"</span></span> username

<span class="pl-k">while</span> <span class="pl-c1">true</span><span class="pl-k">;</span><span class="pl-k">do</span>
	<span class="pl-k">if</span> who <span class="pl-k">|</span> grep <span class="pl-s"><span class="pl-pds">"</span>^<span class="pl-smi">$username</span><span class="pl-pds">"</span></span> <span class="pl-k">&amp;</span><span class="pl-k">&gt;</span> /dev/null<span class="pl-k">;</span><span class="pl-k">then</span>
		<span class="pl-c1">break</span>
	<span class="pl-k">fi</span>
	sleep 3
<span class="pl-k">done</span>

<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$username</span> logggen on.<span class="pl-pds">"</span></span> <span class="pl-k">&gt;&gt;</span> /tmp/user.log
</pre></div>
<ul>
<li>Example：使用until实现上述功能：</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>用until造成死循环，循环判断用户输入的用户名是否登录；</span>
<span class="pl-c1">read</span> -p <span class="pl-s"><span class="pl-pds">"</span>Enter a user name:<span class="pl-pds">"</span></span> username
<span class="pl-k">until</span> who <span class="pl-k">|</span> grep <span class="pl-s"><span class="pl-pds">"</span>^<span class="pl-smi">$username</span><span class="pl-pds">"</span></span> <span class="pl-k">&amp;</span><span class="pl-k">&gt;</span> /dev/null<span class="pl-k">;</span><span class="pl-k">do</span>
	sleep 3
<span class="pl-k">done</span>
<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$username</span> logged on.<span class="pl-pds">"</span></span> <span class="pl-k">&gt;&gt;</span> /tmp/user.log</pre></div>
<h3><a id="user-content-while循环的特殊用法遍历文件的每一行" class="anchor" aria-hidden="true" href="#while循环的特殊用法遍历文件的每一行"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>while循环的特殊用法：（遍历文件的每一行）</h3>
<pre><code>	while read line;do
		循环体
	done &lt; /PATH/FROM/SOMEFILE
</code></pre>
<p>依次读取/PATH/FROM/SOMEFILE文件中的每一行，且将该行赋值给变量line；</p>
<ul>
<li>Example:依次读取/etc/passwd文件中的每一行，找出其ID号为偶数的所有用户，显示其用户名、ID号及默认shell；</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span>while循环的特殊用法，读取指定文件的每一行并赋值给变量；</span>

<span class="pl-k">while</span> <span class="pl-c1">read</span> line<span class="pl-k">;</span><span class="pl-k">do</span>
	<span class="pl-k">if</span> [ $[<span class="pl-s"><span class="pl-pds">`</span>echo <span class="pl-smi">$line</span> <span class="pl-k">|</span> cut -d: -f3<span class="pl-pds">`</span></span> % 2] <span class="pl-k">-eq</span> 0 ]<span class="pl-k">;</span><span class="pl-k">then</span>
		<span class="pl-c1">echo</span> -e -n <span class="pl-s"><span class="pl-pds">"</span>username:<span class="pl-s"><span class="pl-pds">`</span>echo <span class="pl-smi">$line</span> <span class="pl-k">|</span> cut -d: -f1<span class="pl-pds">`</span></span>\t<span class="pl-pds">"</span></span>
		<span class="pl-c1">echo</span> -e -n <span class="pl-s"><span class="pl-pds">"</span>uid: <span class="pl-s"><span class="pl-pds">`</span>echo <span class="pl-smi">$line</span> <span class="pl-k">|</span> cut -d: -f3<span class="pl-pds">`</span></span>\t<span class="pl-pds">"</span></span>
		<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>SHELL:<span class="pl-s"><span class="pl-pds">`</span>echo <span class="pl-smi">$line</span> <span class="pl-k">|</span> cut -d: -f7<span class="pl-pds">`</span></span><span class="pl-pds">"</span></span>
	<span class="pl-k">fi</span>
<span class="pl-k">done</span> <span class="pl-k">&lt;</span> /etc/passwd
</pre></div>
<h3><a id="user-content-for循环的特殊格式" class="anchor" aria-hidden="true" href="#for循环的特殊格式"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>for循环的特殊格式：</h3>
<pre><code>	for ((控制变量初始化；条件判断表达式；控制变量的修正表达式))；do
		循环体
	done
</code></pre>
<p>此种格式和C语言等的格式是一样一样的，只是多了一对括号；</p>
<p>控制变量初始化：仅在运行到循环代码段时执行一次；</p>
<p>控制变量的修正表达式：每轮循环结束会先进行控制变量修正运算，而后再在条件判断；</p>
<ul>
<li>Example：求100以内所有正整数之和：</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>for循环，类似C语言格式，求100以内正整数之和；</span>

<span class="pl-k">declare</span> -i sum=0

<span class="pl-k">for</span> <span class="pl-s"><span class="pl-pds">((</span>i<span class="pl-k">=</span><span class="pl-c1">1</span>;i<span class="pl-k">&lt;=</span><span class="pl-c1">100</span>;i<span class="pl-k">++</span><span class="pl-pds">))</span></span><span class="pl-k">;</span><span class="pl-k">do</span>
	<span class="pl-c1">let</span> sum+=<span class="pl-smi">$i</span>
<span class="pl-k">done</span>

<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Sum:<span class="pl-smi">$sum</span>.<span class="pl-pds">"</span></span>
</pre></div>
<ul>
<li>Example：打印九九乘法表；</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>用类似于C语言风格的for循环打印九九乘法表；</span>

for<span class="pl-s"><span class="pl-pds">((</span>j<span class="pl-k">=</span><span class="pl-c1">1</span>;j<span class="pl-k">&lt;=</span><span class="pl-c1">9</span>;j<span class="pl-k">++</span><span class="pl-pds">))</span></span><span class="pl-k">;</span><span class="pl-k">do</span>
	for<span class="pl-s"><span class="pl-pds">((</span>i<span class="pl-k">=</span><span class="pl-c1">1</span>;i<span class="pl-k">&lt;=</span>j;i<span class="pl-k">++</span><span class="pl-pds">))</span></span><span class="pl-k">;</span><span class="pl-k">do</span>
		<span class="pl-c1">echo</span> -e -n <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">${i}</span>X<span class="pl-smi">${j}</span>=$[<span class="pl-smi">$i</span>*<span class="pl-smi">$j</span>]\t<span class="pl-pds">"</span></span>
	<span class="pl-k">done</span>
	<span class="pl-c1">echo</span>
<span class="pl-k">done</span>
</pre></div>
<h3><a id="user-content-练习写一个脚本完成以下任务" class="anchor" aria-hidden="true" href="#练习写一个脚本完成以下任务"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>练习：写一个脚本，完成以下任务：</h3>
<p>(1)	显示一个如下菜单：</p>
<pre><code>    cpu) show cpu information;
    mem) show memory information;
    disk) show disk information;
    quit) quit
</code></pre>
<p>(2)	提示用户选择选项；</p>
<p>(3)	显示用户选择的内容；</p>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>根据用户的选择，给用户显示相应的硬件信息；</span>

cat <span class="pl-s"><span class="pl-k">&lt;&lt;</span> <span class="pl-k">EOF</span></span>
<span class="pl-s">cpu) show cpu information;</span>
<span class="pl-s">mem) show memory information;</span>
<span class="pl-s">disk) show disk information;</span>
<span class="pl-s">quit) quit</span>
<span class="pl-s">#####################################</span>
<span class="pl-s"><span class="pl-k">EOF</span></span>

<span class="pl-c1">read</span> -p <span class="pl-s"><span class="pl-pds">"</span>Enter a option:<span class="pl-pds">"</span></span> option
<span class="pl-k">while</span> [ <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$option</span><span class="pl-pds">"</span></span> <span class="pl-k">!=</span> <span class="pl-s"><span class="pl-pds">'</span>cpu<span class="pl-pds">'</span></span> <span class="pl-k">-a</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$option</span><span class="pl-pds">"</span></span> <span class="pl-k">!=</span> <span class="pl-s"><span class="pl-pds">'</span>mem<span class="pl-pds">'</span></span> <span class="pl-k">-a</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$option</span><span class="pl-pds">"</span></span> <span class="pl-k">!=</span> <span class="pl-s"><span class="pl-pds">'</span>disk<span class="pl-pds">'</span></span> <span class="pl-k">-a</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$option</span><span class="pl-pds">"</span></span> <span class="pl-k">!=</span> <span class="pl-s"><span class="pl-pds">'</span>quit<span class="pl-pds">'</span></span> ]<span class="pl-k">;</span><span class="pl-k">do</span>
	<span class="pl-c1">read</span> -p <span class="pl-s"><span class="pl-pds">"</span>Wrong option,please Enter again:<span class="pl-pds">"</span></span> option
<span class="pl-k">done</span>

<span class="pl-k">if</span> [ <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$option</span><span class="pl-pds">"</span></span> <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">'</span>cpu<span class="pl-pds">'</span></span> ]<span class="pl-k">;</span><span class="pl-k">then</span>
	lscpu
<span class="pl-k">elif</span> [ <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$option</span><span class="pl-pds">"</span></span> <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">'</span>mem<span class="pl-pds">'</span></span> ]<span class="pl-k">;</span><span class="pl-k">then</span>
	cat /proc/meminfo
<span class="pl-k">elif</span> [ <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$option</span><span class="pl-pds">"</span></span> <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">'</span>disk<span class="pl-pds">'</span></span> ]<span class="pl-k">;</span><span class="pl-k">then</span>
	fdisk -l
<span class="pl-k">else</span>
	<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Quit<span class="pl-pds">"</span></span>
	<span class="pl-c1">exit</span> 0
<span class="pl-k">fi</span>
</pre></div>
<h3><a id="user-content-case语句" class="anchor" aria-hidden="true" href="#case语句"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-case语句">case语句</span></h3>
<pre><code>case 变量引用 in
PAT1)
		分支1
		；；
PAT2）
		分支2
		；；
….
*)
		默认分支
		；；
esac
</code></pre>
<p>case支持glob风格的通配符：</p>
<pre><code>    *: 任意长度任意字符；
    ?: 任意单个字符；
    []：指定范围内的任意单个字符；
    a|b: a或b
</code></pre>
<p>Example：使用case语句改写前一个练习：</p>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
cat <span class="pl-s"><span class="pl-k">&lt;&lt;</span> <span class="pl-k">EOF</span></span>
<span class="pl-s">cpu) show cpu information;</span>
<span class="pl-s">mem) show memory information;</span>
<span class="pl-s">disk) show disk information;</span>
<span class="pl-s">quit) quit</span>
<span class="pl-s">============================</span>
<span class="pl-s"><span class="pl-k">EOF</span></span>
<span class="pl-c1">read</span> -p <span class="pl-s"><span class="pl-pds">"</span>Enter a option: <span class="pl-pds">"</span></span> option
<span class="pl-k">while</span> [ <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$option</span><span class="pl-pds">"</span></span> <span class="pl-k">!=</span> <span class="pl-s"><span class="pl-pds">'</span>cpu<span class="pl-pds">'</span></span> <span class="pl-k">-a</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$option</span><span class="pl-pds">"</span></span> <span class="pl-k">!=</span> <span class="pl-s"><span class="pl-pds">'</span>mem<span class="pl-pds">'</span></span> <span class="pl-k">-a</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$option</span><span class="pl-pds">"</span></span> <span class="pl-k">!=</span> <span class="pl-s"><span class="pl-pds">'</span>disk<span class="pl-pds">'</span></span> <span class="pl-k">-a</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$option</span><span class="pl-pds">"</span></span> <span class="pl-k">!=</span> <span class="pl-s"><span class="pl-pds">'</span>quit<span class="pl-pds">'</span></span> ]<span class="pl-k">;</span> <span class="pl-k">do</span>
    <span class="pl-c1">read</span> -p <span class="pl-s"><span class="pl-pds">"</span>Wrong option, Enter again: <span class="pl-pds">"</span></span> option
<span class="pl-k">done</span>

<span class="pl-k">case</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$option</span><span class="pl-pds">"</span></span> <span class="pl-k">in</span>
cpu)
	lscpu 
	;;
mem)
	cat /proc/meminfo
	;;
disk)
	fdisk -l
	;;
<span class="pl-k">*</span>)
	<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Quit...<span class="pl-pds">"</span></span>
	<span class="pl-c1">exit</span> 0
	;;
<span class="pl-k">esac</span>
</pre></div>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-17函数" class="anchor" aria-hidden="true" href="#17函数"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-17函数">17函数</span></h2>
<pre><code>函数的作用：
过程式编程：为实现代码重用
 	模块化编程
 	结构化编程；
</code></pre>
<ul>
<li>语法一：</li>
</ul>
<pre><code>function f_name {
	…函数体…..
}
</code></pre>
<ul>
<li>语法二：</li>
</ul>
<pre><code>f_name() {
	…函数….
}
</code></pre>
<ul>
<li>
<p>函数调用：函数只有被调用才会执行：</p>
<p>调用：给定函数名</p>
<pre><code>  函数名出现的地方，会被自动替换为函数代码；
</code></pre>
</li>
<li>
<p>函数的生命周期：被调用时创建，返回时终止；</p>
<p>return命令返回自定义状态结果；</p>
<pre><code>  0：成功

  1-255：失败
</code></pre>
</li>
<li>
<p>Example：通过函数，创建10个用户；</p>
</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>通过调用函数添加10个用户；</span>

<span class="pl-k">function</span> <span class="pl-en">adduser</span> {
	<span class="pl-k">if</span> id <span class="pl-smi">$username</span> <span class="pl-k">&amp;</span><span class="pl-k">&gt;</span> /dev/null<span class="pl-k">;</span><span class="pl-k">then</span>
		<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$username</span> exists.<span class="pl-pds">"</span></span>
		<span class="pl-k">return</span> 1
	<span class="pl-k">else</span>
		useradd <span class="pl-smi">$username</span>
		[ <span class="pl-smi">$?</span> <span class="pl-k">-eq</span> 0 ] <span class="pl-k">&amp;&amp;</span> <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Add <span class="pl-smi">$username</span> finished.<span class="pl-pds">"</span></span> <span class="pl-k">&amp;&amp;</span> <span class="pl-k">return</span> 0
	<span class="pl-k">fi</span>
}

<span class="pl-k">for</span> <span class="pl-smi">i</span> <span class="pl-k">in</span> {1..10}<span class="pl-k">;</span><span class="pl-k">do</span>
	username=myuser<span class="pl-smi">$i</span>
	adduser
<span class="pl-k">done</span></pre></div>
<ul>
<li>Example：编写一个服务脚本：</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span> chkconfig: - 88 12</span>
<span class="pl-c"><span class="pl-c">#</span> description: test service script</span>
prog=<span class="pl-s"><span class="pl-pds">$(</span>basename <span class="pl-smi">$0</span><span class="pl-pds">)</span></span>
lockfile=/var/lock/subsys/<span class="pl-smi">$prog</span>
<span class="pl-en">start</span>() {
	<span class="pl-k">if</span> [ <span class="pl-k">-e</span> <span class="pl-smi">$lockfile</span> ]<span class="pl-k">;</span><span class="pl-k">then</span>
		<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$prog</span> is already running.<span class="pl-pds">"</span></span>
		<span class="pl-k">return</span> 0
	<span class="pl-k">else</span> 
		touch <span class="pl-smi">$lockfile</span>
		[ <span class="pl-smi">$?</span> <span class="pl-k">-eq</span> 0 ] <span class="pl-k">&amp;&amp;</span> <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Starting <span class="pl-smi">$prog</span> finished.<span class="pl-pds">"</span></span>
	<span class="pl-k">fi</span>
}
<span class="pl-en">stop</span>() {
	<span class="pl-k">if</span> [ <span class="pl-k">-e</span> <span class="pl-smi">$lockfile</span> ]<span class="pl-k">;</span><span class="pl-k">then</span>
		rm -f <span class="pl-smi">$lockfile</span> <span class="pl-k">&amp;&amp;</span> <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Stop <span class="pl-smi">$prog</span> ok.<span class="pl-pds">"</span></span>
	<span class="pl-k">else</span>
		<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$prog</span> is stopped yet.<span class="pl-pds">"</span></span>
	<span class="pl-k">fi</span>
}
<span class="pl-en">status</span>() {
	<span class="pl-k">if</span> [ <span class="pl-k">-e</span> <span class="pl-smi">$lockfile</span> ]<span class="pl-k">;</span><span class="pl-k">then</span>
		<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$prog</span> is running.<span class="pl-pds">"</span></span>
	<span class="pl-k">else</span>
		<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$prog</span> is stopped.<span class="pl-pds">"</span></span>
	<span class="pl-k">fi</span>
}
<span class="pl-en">usage</span>() {
	<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Usage:<span class="pl-smi">$prog</span> {start | stop | restart | status}<span class="pl-pds">"</span></span>
}
<span class="pl-k">if</span> [ <span class="pl-smi">$#</span> <span class="pl-k">-lt</span> 1 ]<span class="pl-k">;</span><span class="pl-k">then</span>
	usage
	<span class="pl-c1">exit</span> 1
<span class="pl-k">fi</span>

<span class="pl-k">case</span> <span class="pl-smi">$1</span> <span class="pl-k">in</span>
start)
	start
	;;
stop)
	stop
	;;
restart)
	stop
	start
	;;
status)
	status
	;;
<span class="pl-k">*</span>)
	usage
<span class="pl-k">esac</span></pre></div>
<h3><a id="user-content-函数返回值" class="anchor" aria-hidden="true" href="#函数返回值"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>函数返回值：</h3>
<p>函数的执行结果返回值：</p>
<pre><code>(1)	使用echo或print命令进行输出；

(2)	函数体中调用命令的执行结果；
</code></pre>
<p>函数的退出状态码：</p>
<pre><code>(1)	默认取决于函数体中执行的最后一条命令的退出状态码；

(2)	自定义退出状态码；

	使用return关键字；
</code></pre>
<p>函数可以接受参数：</p>
<pre><code>	传递参数给函数：调用函数时，在函数名后面以空白分隔给定参数列表即可；
</code></pre>
<p>例如：“testfunc arg1 arg2 …”</p>
<pre><code>在函数体当中，可使用$1,$2,….调用这些参数；还可以使用$@,$*,$#等特殊变量；
</code></pre>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>使用带参数的函数添加10个用户；</span>

<span class="pl-k">function</span> <span class="pl-en">adduser</span> {			<span class="pl-c"><span class="pl-c">#</span>一个可接受参数的函数</span>
	<span class="pl-k">if</span> [ <span class="pl-smi">$#</span> <span class="pl-k">-lt</span> 1 ]<span class="pl-k">;</span><span class="pl-k">then</span>
		<span class="pl-k">return</span> 2   <span class="pl-c"><span class="pl-c">#</span> 2: no arguments</span>
	<span class="pl-k">fi</span>
	
	<span class="pl-k">if</span> id <span class="pl-smi">$1</span> <span class="pl-k">&amp;</span><span class="pl-k">&gt;</span> /dev/null<span class="pl-k">;</span><span class="pl-k">then</span>
		<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-smi">$1</span> exists.<span class="pl-pds">"</span></span>
		<span class="pl-k">return</span> 1<span class="pl-k">;</span>
	<span class="pl-k">else</span>
		useradd <span class="pl-smi">$1</span>
		[ <span class="pl-smi">$?</span> <span class="pl-k">-eq</span> 0 ] <span class="pl-k">&amp;&amp;</span> <span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Add <span class="pl-smi">$1</span> finished.<span class="pl-pds">"</span></span> <span class="pl-k">&amp;&amp;</span> <span class="pl-k">return</span> 0
	<span class="pl-k">fi</span>	
}

<span class="pl-k">while</span> <span class="pl-c1">true</span><span class="pl-k">;</span><span class="pl-k">do</span>		<span class="pl-c"><span class="pl-c">#</span>死循环，直到输入的值为quit是退出；</span>
	<span class="pl-c1">read</span> -t 20 -p <span class="pl-s"><span class="pl-pds">"</span>Please input your username(quit to cancel):<span class="pl-pds">"</span></span> username
	<span class="pl-k">if</span> [ <span class="pl-smi">$username</span> <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">"</span>quit<span class="pl-pds">"</span></span> ]<span class="pl-k">;</span><span class="pl-k">then</span>
		<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Quit.<span class="pl-pds">"</span></span>
		<span class="pl-c1">exit</span> 0
	<span class="pl-k">else</span>
		adduser <span class="pl-smi">$username</span>
	<span class="pl-k">fi</span>
<span class="pl-k">done</span></pre></div>
<ul>
<li>
<p>变量作用域：</p>
<p>本地变量：当前shell进程，为了执行脚本会启动专用的shell进程；因此，本地变量的作用范围是当前shell脚本程序文件；</p>
<p>局部变量：函数的生命周期：函数结束时变量被自动销毁；</p>
<pre><code>  如果函数中有局部变量，其名称同本地变量无关；
</code></pre>
</li>
</ul>
<p>在函数中定义局部变量的方法：</p>
<pre><code>	local NAME=VALUE
</code></pre>
<p>函数递归：函数直接或间接调用自身；</p>
<ul>
<li>Example:求N的阶乘：</li>
</ul>
<pre><code>N！=N（N-1）(N-2)….1
	N(N-1)!=N(N-1)(N-2)!
</code></pre>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>利用函数递归求N的阶乘；</span>

<span class="pl-en">fact</span>() {
	<span class="pl-k">if</span> [ <span class="pl-smi">$1</span> <span class="pl-k">-eq</span> 0 <span class="pl-k">-o</span> <span class="pl-smi">$1</span> <span class="pl-k">-eq</span> 1 ]<span class="pl-k">;</span><span class="pl-k">then</span>
		<span class="pl-c1">echo</span> 1
	<span class="pl-k">else</span>
		<span class="pl-c1">echo</span> $[<span class="pl-smi">$1</span><span class="pl-k">*</span><span class="pl-s"><span class="pl-pds">$(</span>fact $[<span class="pl-smi">$1</span>-1]<span class="pl-pds">)</span></span>]
	<span class="pl-k">fi</span>
}
fact 5</pre></div>
<ul>
<li>Example:求n阶斐波拉契数列：</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>函数递归：求n阶斐波拉契数列的第n项；</span>

<span class="pl-en">fab</span>() {
	<span class="pl-k">if</span> [ <span class="pl-smi">$1</span> <span class="pl-k">-eq</span> 1 ]<span class="pl-k">;</span><span class="pl-k">then</span>
		<span class="pl-c1">echo</span> 1
	<span class="pl-k">elif</span> [ <span class="pl-smi">$1</span> <span class="pl-k">-eq</span> 2 ]<span class="pl-k">;</span><span class="pl-k">then</span>
		<span class="pl-c1">echo</span> 1
	<span class="pl-k">else</span>
		<span class="pl-c1">echo</span> $[<span class="pl-s"><span class="pl-pds">$(</span>fab $[<span class="pl-smi">$1</span>-1]<span class="pl-pds">)</span></span>+<span class="pl-s"><span class="pl-pds">$(</span>fab $[<span class="pl-smi">$1</span>-2]<span class="pl-pds">)</span></span>]
	<span class="pl-k">fi</span>
}

fab 7</pre></div>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-18数组" class="anchor" aria-hidden="true" href="#18数组"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-18数组">18数组</span></h2>
<h3><a id="user-content-数组" class="anchor" aria-hidden="true" href="#数组"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>数组：</h3>
<pre><code>变量：存储单个元素的内存空间；
</code></pre>
<pre><code>	数组：存储多个元素的连续的内存空间；
		数组名
		索引：编号从0开始，属于数值索引；
			注意：索引页可支持使用自定义的格式，而不仅仅是数值格式；
				bash的数组支持稀疏格式；
</code></pre>
<ul>
<li>
<p>引用数组中的元素： ${ARRAY_NAME[INDEX]}</p>
</li>
<li>
<p>声明数组：</p>
<p>declare –a ARRAY_NAME</p>
<p>declare –A ARRAY_NAME : 关联数组；</p>
</li>
<li>
<p>数组元素的赋值：</p>
<p>(1)	一次只赋值一个元素；</p>
<pre><code>  ARRAY_NAME[INDEX]=VALUE
</code></pre>
</li>
</ul>
<pre><code>	例如：
			weekdays[0]="Sunday"
			weekdays[4]="Thursday"
</code></pre>
<pre><code>(2)	一次赋值全部元素：

		ARRAY_NAME=("VAL1" "VAL2" "VAL3" ...)

(3)	只赋值特定元素：

		ARRAY_NAME=([0]="VAL1" [3]="VAL2" ...)

(4)	read -a ARRAY 
</code></pre>
<ul>
<li>
<p>引用数组元素：${ARRAY_NAME[INDEX]}</p>
<p>注意：省略[INDEX]表示引用下标为0的元素；</p>
</li>
<li>
<p>数组的长度(数组中元素的个数)：</p>
<p>${#ARRAY_NAME[*]}</p>
<p>${#ARRAY_NAME[@]}</p>
</li>
<li>
<p>Example:生成10个随机数保存于数组中，并找出其最大值和最小值：</p>
</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>生成10个随机数保存于数组中；</span>

<span class="pl-k">declare</span> -a rand
<span class="pl-k">declare</span> -i max=0
<span class="pl-k">declare</span> -i min=0

<span class="pl-k">for</span> <span class="pl-smi">i</span> <span class="pl-k">in</span> {0..9}<span class="pl-k">;</span><span class="pl-k">do</span>
	rand[<span class="pl-smi">$i</span>]=<span class="pl-smi">$RANDOM</span>
	<span class="pl-k">if</span> [ <span class="pl-smi">$i</span> <span class="pl-k">-eq</span> 1 ]<span class="pl-k">;</span><span class="pl-k">then</span>
		max=<span class="pl-smi">${rand[$i]}</span>
		min=<span class="pl-smi">${rand[$i]}</span>
	<span class="pl-k">fi</span>
	<span class="pl-c1">echo</span> <span class="pl-smi">${rand[$i]}</span>
	[ <span class="pl-smi">${rand[$i]}</span> <span class="pl-k">-gt</span> <span class="pl-smi">$max</span> ] <span class="pl-k">&amp;&amp;</span> max=<span class="pl-smi">${rand[$i]}</span>
	[ <span class="pl-smi">${rand[$i]}</span> <span class="pl-k">-lt</span> <span class="pl-smi">$min</span> ] <span class="pl-k">&amp;&amp;</span> min=<span class="pl-smi">${rand[$i]}</span>
<span class="pl-k">done</span>

<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Max:<span class="pl-smi">$max</span><span class="pl-pds">"</span></span>
<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Min:<span class="pl-smi">$min</span><span class="pl-pds">"</span></span></pre></div>
<ul>
<li>Example：写一个脚本：定义一个数组，数组中的元素是/var/log目录下所有以.log结尾的文件；要统计其下标为偶数的文件中的行数之和；</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c"><span class="pl-c">#</span>定义一个数组，数组中的元素是/var/log目录下所有以.log结尾的文件；</span>
<span class="pl-c"><span class="pl-c">#</span>要统计其下标为偶数的文件中的行数之和；</span>

<span class="pl-k">declare</span> -a files
files=(/var/log/<span class="pl-k">*</span>.log)
<span class="pl-k">declare</span> -i lines=0

<span class="pl-k">for</span> <span class="pl-smi">i</span> <span class="pl-k">in</span> <span class="pl-s"><span class="pl-pds">$(</span>seq 0 $[<span class="pl-smi">${<span class="pl-k">#</span>files[*]}</span>-1]<span class="pl-pds">)</span></span><span class="pl-k">;</span><span class="pl-k">do</span>
	<span class="pl-k">if</span> [ $[<span class="pl-smi">$i</span>%2] <span class="pl-k">-eq</span> 0 ]<span class="pl-k">;</span><span class="pl-k">then</span>
		<span class="pl-c1">let</span> lines+=<span class="pl-s"><span class="pl-pds">$(</span>wc -l <span class="pl-smi">${files[$i]}</span> <span class="pl-k">|</span> cut -d<span class="pl-s"><span class="pl-pds">'</span> <span class="pl-pds">'</span></span> -f1<span class="pl-pds">)</span></span>
	<span class="pl-k">fi</span>
<span class="pl-k">done</span> 

<span class="pl-c1">echo</span> <span class="pl-s"><span class="pl-pds">"</span>Lines:<span class="pl-smi">$lines</span>.<span class="pl-pds">"</span></span></pre></div>
<h3><a id="user-content-引用数组中的元素" class="anchor" aria-hidden="true" href="#引用数组中的元素"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>引用数组中的元素：</h3>
<ul>
<li>
<p>所有元素：${ARRAY[@]} , ${ARRAY[*]}</p>
</li>
<li>
<p>数组切片：${ARRAY[@]:offset:number}</p>
<pre><code>  offset:要跳过的元素个数；

  number：要取出的元素个数，取偏移量之后的所有元素：${ARRAY[@]:offset};
</code></pre>
</li>
<li>
<p>向数组中追加元素：ARRAY[${ARRAY[*]}]</p>
</li>
<li>
<p>删除数组中的某元素：unset ARRAY[INDEX]</p>
</li>
<li>
<p>关联数组：</p>
</li>
</ul>
<div class="highlight highlight-source-shell"><pre>	<span class="pl-k">declare</span> –A ARRAY_NAME
	ARRAY_NAME=([index_name1]=’val1’ [index_name2]=’val2’ ….)</pre></div>
<div class="highlight highlight-source-shell"><pre>[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> declare -a array</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> #声明一个数组，不是必要的</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> array=(0 1 2)</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> array=([0]=0 [1]=1 [2]=v2)</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> array[0]=5</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo $array</span>
5
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span></span></pre></div>
<div class="highlight highlight-source-shell"><pre>[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> #以空白作为分隔符拆分字符串为数组</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> str="1 2 3"</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> array=($str)</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo $array</span>
1
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span></span></pre></div>
<div class="highlight highlight-source-shell"><pre>[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> #使用其他分隔符拆分字符串为数组，需指定IFS</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> IFS=: array=($PATH)</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo $array</span>
/usr/local/sbin</pre></div>
<ul>
<li>
<p>引用数组元素：
$array  ${array}  ${array[0]}  #第0个元素</p>
<p>${array[n]}  #第n个元素（n从0开始计算）</p>
</li>
<li>
<p>引用整个数组：
${array[*]}  ${array[@]}   这两种方式等同，会把数组展开。</p>
<p>${array[*]}  表示把数组拼接在一起的整个字符串，如果作为参数传递，会把整个字符串作为一个参数。</p>
<p>${array[@]}  如果作为参数传递，表示把数组中每个元素作为一个参数，数组有多少个元素，就会展开成多少个参数。</p>
</li>
<li>
<p>计算数组元素长度；</p>
<p>${#array[*]}</p>
<p>${#array[@]}</p>
<pre><code>  不是 ${#array}，

  因为它等同于 ${#array[0]}
</code></pre>
</li>
<li>
<p>遍历数组：
for i in "${array[@]}";do
echo $i;
done</p>
</li>
</ul>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-19bash的字符串处理工具" class="anchor" aria-hidden="true" href="#19bash的字符串处理工具"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-19bash的字符串处理工具">19bash的字符串处理工具</span></h2>
<h3><a id="user-content-字符串切片" class="anchor" aria-hidden="true" href="#字符串切片"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>字符串切片：</h3>
<ul>
<li>
<p>${var:offset:number}</p>
<p>取字符串最右侧的几个字符：${var: -lengh}</p>
<p>Note：冒号后面必须有一空白字符；</p>
</li>
</ul>
<h3><a id="user-content-基于模式取子串" class="anchor" aria-hidden="true" href="#基于模式取子串"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>基于模式取子串：</h3>
<ul>
<li>
<p>${var#*word}：其中word可以是指定的任意字符；</p>
<p>功能：自左而右，查找var变量所存储的字符串中，第一次出现的word, 删除字符串开头至第一次出现word字符之间的所有字符；</p>
</li>
<li>
<p>${var##*word}：其中word可以是指定的任意字符；</p>
<p>功能：自左而右，查找var变量所存储的字符串中出现的word，删除字符串开头至最后一次由word指定的字符之间的所有内容；</p>
</li>
</ul>
<div class="highlight highlight-source-shell"><pre><span class="pl-c"><span class="pl-c">#</span>bash基于模式取子串；</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> file="/var/log/messages"</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo ${file#*/}</span>
var/log/messages
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo ${file##*/}</span>
messages</pre></div>
<ul>
<li>
<p>${var%word*}：其中word可以是指定的任意字符；</p>
<p>功能：自右而左，查找var变量所存储的字符串中，第一次出现的word, 删除字符串最后一个字符向左至第一次出现word字符之间的所有字符；</p>
</li>
<li>
<p>${var%%word*}：其中word可以是指定的任意字符；</p>
<p>功能：自右而左，查找var变量所存储的字符串中出现的word,，只不过删除字符串最右侧的字符向左至最后一次出现word字符之间的所有字符；</p>
</li>
</ul>
<div class="highlight highlight-source-shell"><pre>[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> file="/var/log/messages" #从右至左，匹配‘/ ’</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo ${file%/*}</span>
/var/log
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo ${file%%/*}    # 双%匹配并删除后为空；</span>

[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span></span></pre></div>
<ul>
<li>Example：url=<a href="http://www.google.com:80,%E5%88%86%E5%88%AB%E5%8F%96%E5%87%BA%E5%8D%8F%E8%AE%AE%E5%92%8C%E7%AB%AF%E5%8F%A3%EF%BC%9B" rel="nofollow">http://www.google.com:80,分别取出协议和端口；</a></li>
</ul>
<div class="highlight highlight-source-shell"><pre>[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> url=http://www.google.com:80</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo ${url##*:}    #取端口号</span>
80
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo ${url%%:*}   #取协议</span>
http
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span></span></pre></div>
<h3><a id="user-content-查找替换" class="anchor" aria-hidden="true" href="#查找替换"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>查找替换：</h3>
<pre><code>${var/pattern/substi}：查找var所表示的字符串中，第一次被pattern所匹配到的字符串，以substi替换之；

${var//pattern/substi}: 查找var所表示的字符串中，所有能被pattern所匹配到的字符串，以substi替换之；

${var/#pattern/substi}：查找var所表示的字符串中，行首被pattern所匹配到的字符串，以substi替换之；

${var/%pattern/substi}：查找var所表示的字符串中，行尾被pattern所匹配到的字符串，以substi替换之；
</code></pre>
<div class="highlight highlight-source-shell"><pre>[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> var=$(head -n 1 /etc/passwd)</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo $var</span>
root x 0 0 root /root /bin/bash
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo ${var/root/ROOT}  #替换第一次匹配到的root为ROOT</span>
ROOT x 0 0 root /root /bin/bash
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo ${var//root/ROOT}  #替换所有匹配到的root为ROOT</span>
ROOT x 0 0 ROOT /ROOT /bin/bash</pre></div>
<div class="highlight highlight-source-shell"><pre>[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> useradd bash -s /bin/bash</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> cat /etc/passwd | grep "^bash.*bash$"</span>
bash:x:1029:1029::/home/bash:/bin/bash
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> line=$(cat /etc/passwd | grep "^bash.*bash$")</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo $line</span>
bash x 1029 1029  /home/bash /bin/bash
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo ${line/#bash/BASH}	#替换行首的bash为BASH</span>
BASH x 1029 1029  /home/bash /bin/bash
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo ${line/%bash/BASH}	#替换行尾的bash为BASH</span>
bash x 1029 1029  /home/bash /bin/BASH</pre></div>
<h3><a id="user-content-查找并删除" class="anchor" aria-hidden="true" href="#查找并删除"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>查找并删除：</h3>
<pre><code>${var/pattern}：查找var所表示的字符串中，删除第一次被pattern所匹配到的字符串

${var//pattern}：查找var所表示的字符串中，删除所有被pattern所匹配到的字符串；

${var/#pattern}：查找var所表示的字符串中，删除行首被pattern所匹配到的字符串；

${var/%pattern}：查找var所表示的字符串中，删除行尾被pattern所匹配到的字符串；
</code></pre>
<ul>
<li>Example：</li>
</ul>
<div class="highlight highlight-source-shell"><pre>[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> line=$(tail -n 1 /etc/passwd)</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo $line</span>
bash x 1029 1029  /home/bash /bin/bash
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo ${line/bash}  #查找并删除第一次匹配到的bash</span>
 x 1029 1029  /home/bash /bin/bash
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo ${line//bash}	#查找并删除所有匹配到的bash</span>
 x 1029 1029  /home/ /bin/
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo ${line/#bash}	#查找并删除匹配到的行首的bash</span>
 x 1029 1029  /home/bash /bin/bash
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo ${line/%bash}   #查找并删除匹配到的行尾bash</span>
bash x 1029 1029  /home/bash /bin/</pre></div>
<h3><a id="user-content-字符大小写转换" class="anchor" aria-hidden="true" href="#字符大小写转换"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>字符大小写转换：</h3>
<pre><code>${var^^}：把var中的所有小写字母转换为大写；

${var,,}：把var中的所有大写字母转换为小写；
</code></pre>
<ul>
<li>Example：</li>
</ul>
<div class="highlight highlight-source-shell"><pre>[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> line=$(tail -n 1 /etc/fstab)		#将文件最后一行的值赋值给变量</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo ${line^^}		#全部转换为大写后输出</span>
/DEV/MAPPER/CENTOS-SWAP SWAP                    SWAP    DEFAULTS        0 0
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> line=`echo ${line^^}`	#将转换为大写后的值在赋值给变量；</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo $line			#确认目前变量的值全为大写字母；</span>
/DEV/MAPPER/CENTOS-SWAP SWAP                    SWAP    DEFAULTS        0 0
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo ${line,,}		#全部转换为大写后输出；</span>
/dev/mapper/centos-swap swap                    swap    defaults        0 0</pre></div>
<h3><a id="user-content-变量赋值" class="anchor" aria-hidden="true" href="#变量赋值"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>变量赋值：</h3>
<pre><code>${var:-value}：如果var为空或未设置，那么返回value；否则，则返回var的值；

${var:=value}：如果var为空或未设置，那么返回value，并将value赋值给var；否则，则返回var的值；
</code></pre>
<ul>
<li>Example：</li>
</ul>
<div class="highlight highlight-source-shell"><pre>[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo $test		#变量值为空；</span>

[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo ${test:-helloworld}	#  :- 仅返回设定值，不修改；</span>
helloworld
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo $test      #变量的值依然为空；</span>

[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo ${test:=helloworld}   #  :=  返回设定值，并赋值给变量；</span>
helloworld
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo $test			# 变量值已修改；</span>
helloworld</pre></div>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
<h2><a id="user-content-20脚本的配置文件" class="anchor" aria-hidden="true" href="#20脚本的配置文件"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a><span id="user-content-20s脚本的配置文件">20脚本的配置文件</span></h2>
<p>###步骤：</p>
<ul>
<li>(1) 定义文本文件，每行定义“name=value”</li>
<li>(2) 在脚本中source此文件即可</li>
</ul>
<div class="highlight highlight-source-shell"><pre>[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> touch /tmp/config.test #创建配置文件；</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> echo "name=kalaguiyin" &gt;&gt; /tmp/config.test #在配置文件中定义变量；</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> vim script_configureFile.sh		#编写脚本，导入配置文件；如内容所示；</span>
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> bash script_configureFile.sh 	#脚本执行结果；</span>
kalaguiyin
[root@kalaguiyin scripts]<span class="pl-c"><span class="pl-c">#</span> cat script_configureFile.sh </span>
<span class="pl-c"><span class="pl-c">#!</span>/bin/bash</span>
<span class="pl-c"><span class="pl-c">#</span></span>
<span class="pl-c1">source</span> /tmp/config.test		<span class="pl-c"><span class="pl-c">#</span>导入配置文件，脚本自身并未定义变量；</span>

<span class="pl-c1">echo</span> <span class="pl-smi">$name</span>				<span class="pl-c"><span class="pl-c">#</span>引用的是配置文件中的变量name</span></pre></div>
<p><a href="#%E7%9B%AE%E5%BD%95">返回目录</a></p>
</article>
  </div>

    </div>

  

  <details class="details-reset details-overlay details-overlay-dark">
    <summary data-hotkey="l" aria-label="Jump to line"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump" aria-label="Jump to line">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-jump-to-line-form Box-body d-flex" action="" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
        <button type="submit" class="btn" data-close-dialog>Go</button>
</form>    </details-dialog>
  </details>



  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </div>
  </div>
  

  </div>

        
<div class="footer container-lg px-3" role="contentinfo">
  <div class="position-relative d-flex flex-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap ">
      <li class="mr-3">&copy; 2019 <span title="0.23958s from unicorn-76fdc6675f-9k5t2">GitHub</span>, Inc.</li>
        <li class="mr-3"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
        <li class="mr-3"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
        <li class="mr-3"><a data-ga-click="Footer, go to security, text:security" href="https://github.com/security">Security</a></li>
        <li class="mr-3"><a href="https://githubstatus.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a data-ga-click="Footer, go to help, text:help" href="https://help.github.com">Help</a></li>
    </ul>

    <a aria-label="Homepage" title="GitHub" class="footer-octicon mr-lg-4" href="https://github.com">
      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
   <ul class="list-style-none d-flex flex-wrap ">
        <li class="mr-3"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub</a></li>
        <li class="mr-3"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing</a></li>
      <li class="mr-3"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
        <li class="mr-3"><a href="https://github.blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>

    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
    </button>
    You can’t perform that action at this time.
  </div>


    <script crossorigin="anonymous" integrity="sha512-47ZXWJASen/yLysPiEpAb7/WvHBIHIRKo+7W5g0YYFiInTWqpjYBHTpeHut0QWEf51gExNhSEy55XQmxrZ+0xA==" type="application/javascript" src="https://github.githubassets.com/assets/compat-742699bf681282d2e3cf809d2b9de73a.js"></script>
    <script crossorigin="anonymous" integrity="sha512-ZwVwxq7XuYTJgo+RvKEmeGyrm1OTN2Du77YWAfdEiJo9lZbmFO252M4KaMRyDZ3O0bw1OYpF/rJCyQ3g/aa0yA==" type="application/javascript" src="https://github.githubassets.com/assets/frameworks-5e5334deb0beba2b22d055907f8e10a4.js"></script>
    
    <script crossorigin="anonymous" async="async" integrity="sha512-n64WRGgMGbhSA6jDawWo/zYeN7OKj91fLPYDIkXABKJVYFZPoy0GE6gRH/Rx9MMN1+1Ye2sSWeXugFJgWeAFyg==" type="application/javascript" src="https://github.githubassets.com/assets/github-af60d4020201a149bf8daba312a12266.js"></script>
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner d-none">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark" open>
    <summary aria-haspopup="dialog" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
        <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
      </button>
      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

  <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box box-shadow-large" style="width:360px;">
  </div>
</div>

<div id="hovercard-aria-description" class="sr-only">
  Press h to open a hovercard with more details.
</div>

  <div aria-live="polite" class="js-global-screen-reader-notice sr-only"></div>

  </body>
</html>

