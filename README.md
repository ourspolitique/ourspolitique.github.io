Skip to content
 
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@ourspolitique 
1
0 0 suenyu/suenyu.github.io
 Code  Issues 0  Pull requests 0  Projects 0  Wiki  Security  Insights
suenyu.github.io/index.html
@suenyu suenyu Site updated: 2019-06-25 11:26:07
f8ff803 4 days ago
3643 lines (1586 sloc)  97 KB
    
<!DOCTYPE html>












  


<html class="theme-next mist use-motion" lang="zh-CN">
<head><meta name="generator" content="Hexo 3.8.0">
  <meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=2">
<meta name="theme-color" content="#222">


















  
  
  <link rel="stylesheet" href="/lib/fancybox/source/jquery.fancybox.css">




  
  
  
  

  
    
    
  

  

  

  

  

  
    
    
    <link rel="stylesheet" href="https://fonts.loli.net/css?family=Noto Serif SC:300,300italic,400,400italic,700,700italic&subset=latin,latin-ext">
  






<link rel="stylesheet" href="/lib/font-awesome/css/font-awesome.min.css?v=4.6.2">

<link rel="stylesheet" href="/css/main.css?v=7.1.2">


  <link rel="apple-touch-icon" sizes="180x180" href="/images/apple-touch-icon-next.png?v=7.1.2">


  <link rel="icon" type="image/png" sizes="32x32" href="/images/favicon-32x32-next.png?v=7.1.2">


  <link rel="icon" type="image/png" sizes="16x16" href="/images/favicon-16x16-next.png?v=7.1.2">


  <link rel="mask-icon" href="/images/logo.svg?v=7.1.2" color="#222">







<script id="hexo.configurations">
  var NexT = window.NexT || {};
  var CONFIG = {
    root: '/',
    scheme: 'Mist',
    version: '7.1.2',
    sidebar: {"position":"left","display":"post","offset":12,"onmobile":true,"dimmer":true},
    back2top: true,
    back2top_sidebar: false,
    fancybox: true,
    fastclick: false,
    lazyload: false,
    tabs: true,
    motion: {"enable":true,"async":false,"transition":{"post_block":"fadeIn","post_header":"slideDownIn","post_body":"slideDownIn","coll_header":"slideLeftIn","sidebar":"slideUpIn"}},
    algolia: {
      applicationID: '',
      apiKey: '',
      indexName: '',
      hits: {"per_page":10},
      labels: {"input_placeholder":"Search for Posts","hits_empty":"We didn't find any results for the search: ${query}","hits_stats":"${hits} results found in ${time} ms"}
    }
  };
</script>


  




  <meta property="og:type" content="website">
<meta property="og:title" content="无余说">
<meta property="og:url" content="https://suenyu.github.io/index.html">
<meta property="og:site_name" content="无余说">
<meta property="og:locale" content="zh-CN">
<meta name="twitter:card" content="summary">
<meta name="twitter:title" content="无余说">



  <link rel="alternate" href="/atom.xml" title="无余说" type="application/atom+xml">



  
  
  <link rel="canonical" href="https://suenyu.github.io/">



<script id="page.configurations">
  CONFIG.page = {
    sidebar: "",
  };
</script>

  <title>无余说</title>
  












  <noscript>
  <style>
  .use-motion .motion-element,
  .use-motion .brand,
  .use-motion .menu-item,
  .sidebar-inner,
  .use-motion .post-block,
  .use-motion .pagination,
  .use-motion .comments,
  .use-motion .post-header,
  .use-motion .post-body,
  .use-motion .collection-title { opacity: initial; }
  .use-motion .logo,
  .use-motion .site-title,
  .use-motion .site-subtitle {
    opacity: initial;
    top: initial;
  }
  .use-motion .logo-line-before i { left: initial; }
  .use-motion .logo-line-after i { right: initial; }
  </style>
</noscript>

</head>

<body itemscope itemtype="http://schema.org/WebPage" lang="zh-CN">

  
  
    
  

  <div class="container sidebar-position-left 
  page-home">
    <div class="headband"></div>

    <header id="header" class="header" itemscope itemtype="http://schema.org/WPHeader">
      <div class="header-inner"><div class="site-brand-wrapper">
  <div class="site-meta">
    

    <div class="custom-logo-site-title">
      <a href="/" class="brand" rel="start">
        <span class="logo-line-before"><i></i></span>
        <span class="site-title">无余说</span>
        <span class="logo-line-after"><i></i></span>
      </a>
    </div>
    
    
  </div>

  <div class="site-nav-toggle">
    <button aria-label="切换导航栏">
      <span class="btn-bar"></span>
      <span class="btn-bar"></span>
      <span class="btn-bar"></span>
    </button>
  </div>
</div>



<nav class="site-nav">
  
    <ul id="menu" class="menu">
      
        
        
        
          
          <li class="menu-item menu-item-home menu-item-active">

    
    
    
      
    

    

    <a href="/" rel="section"><i class="menu-item-icon fa fa-fw fa-home"></i> <br>首页</a>

  </li>
        
        
        
          
          <li class="menu-item menu-item-about">

    
    
    
      
    

    

    <a href="/about/" rel="section"><i class="menu-item-icon fa fa-fw fa-user"></i> <br>关于</a>

  </li>
        
        
        
          
          <li class="menu-item menu-item-tags">

    
    
    
      
    

    

    <a href="/tags/" rel="section"><i class="menu-item-icon fa fa-fw fa-tags"></i> <br>标签</a>

  </li>
        
        
        
          
          <li class="menu-item menu-item-categories">

    
    
    
      
    

    

    <a href="/categories/" rel="section"><i class="menu-item-icon fa fa-fw fa-th"></i> <br>分类</a>

  </li>
        
        
        
          
          <li class="menu-item menu-item-archives">

    
    
    
      
    

    

    <a href="/archives/" rel="section"><i class="menu-item-icon fa fa-fw fa-archive"></i> <br>归档</a>

  </li>

      
      
        <li class="menu-item menu-item-search">
          
            <a href="javascript:;" class="popup-trigger">
          
            
              <i class="menu-item-icon fa fa-search fa-fw"></i> <br>搜索</a>
        </li>
      
    </ul>
  

  
    

  

  
    <div class="site-search">
      
  <div class="popup search-popup local-search-popup">
  <div class="local-search-header clearfix">
    <span class="search-icon">
      <i class="fa fa-search"></i>
    </span>
    <span class="popup-btn-close">
      <i class="fa fa-times-circle"></i>
    </span>
    <div class="local-search-input-wrapper">
      <input autocomplete="off" placeholder="搜索..." spellcheck="false" type="text" id="local-search-input">
    </div>
  </div>
  <div id="local-search-result"></div>
</div>



    </div>
  
</nav>



  



</div>
    </header>

    


    <main id="main" class="main">
      <div class="main-inner">
        <div class="content-wrap">
          
          <div id="content" class="content">
            
  <section id="posts" class="posts-expand">
    
      

  

  
  
  

  

  <article class="post post-type-normal" itemscope itemtype="http://schema.org/Article">
  
  
  
  <div class="post-block">
    <link itemprop="mainEntityOfPage" href="https://suenyu.github.io/2019/06/25/words/">

    <span hidden itemprop="author" itemscope itemtype="http://schema.org/Person">
      <meta itemprop="name" content="suen">
      <meta itemprop="description" content>
      <meta itemprop="image" content="/images/avatar.gif">
    </span>

    <span hidden itemprop="publisher" itemscope itemtype="http://schema.org/Organization">
      <meta itemprop="name" content="无余说">
    </span>

    
      <header class="post-header">

        
        
          <h1 class="post-title" itemprop="name headline">
                
                
                <a href="/2019/06/25/words/" class="post-title-link" itemprop="url">每个词，都是你</a>
              
            
          </h1>
        

        <div class="post-meta">
          <span class="post-time">

            
            
            

            
              <span class="post-meta-item-icon">
                <i class="fa fa-calendar-o"></i>
              </span>
              
                <span class="post-meta-item-text">发表于</span>
              

              
                
              

              <time title="创建时间：2019-06-25 08:56:15 / 修改时间：10:43:40" itemprop="dateCreated datePublished" datetime="2019-06-25T08:56:15+08:00">2019-06-25</time>
            

            
              

              
            
          </span>

          

          
            
            
              
              <span class="post-comments-count">
                <span class="post-meta-divider">|</span>
                <span class="post-meta-item-icon">
                  <i class="fa fa-comment-o"></i>
                </span>
            
                <span class="post-meta-item-text">评论数：</span>
                <a href="/2019/06/25/words/#comments" itemprop="discussionUrl">
                  <span class="post-comments-count valine-comment-count" data-xid="/2019/06/25/words/" itemprop="commentCount"></span>
                </a>
              </span>
            
          

          
          
            <span id="/2019/06/25/words/" class="leancloud_visitors" data-flag-title="每个词，都是你">
              <span class="post-meta-divider">|</span>
              <span class="post-meta-item-icon">
                <i class="fa fa-eye"></i>
              </span>
              
                <span class="post-meta-item-text">阅读次数：</span>
              
                <span class="leancloud-visitors-count"></span>
            </span>
          

          

          
            <div class="post-symbolscount">
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-file-word-o"></i>
                </span>
                
                  <span class="post-meta-item-text">本文字数：</span>
                
                <span title="本文字数">3.2k</span>
              

              
                <span class="post-meta-divider">|</span>
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-clock-o"></i>
                </span>
                
                  <span class="post-meta-item-text">阅读时长 &asymp;</span>
                
                <span title="阅读时长">8 分钟</span>
              
            </div>
          

          

        </div>
      </header>
    

    
    
    
    <div class="post-body" itemprop="articleBody">

      
      

      
        
          
            <h2 id="原始材料梳理"><a href="#原始材料梳理" class="headerlink" title="原始材料梳理"></a>原始材料梳理</h2><p>Kyle Kashuv  @KyleKashuv  Jun 17 2019<br><img src="/images/kyle0.png" class="[kk]" width="998" height="912"><br>1/ THREAD: Harvard rescinded my acceptance.</p>
<p>Three months after being admitted to Harvard Class of 2023, Harvard has decided to rescind my admission over texts and comments made nearly two years ago, months prior to the shooting.</p>
<p>I have some thoughts. Here’s what happened.</p>
<p>2/ A few weeks ago, I was made aware of egregious and callous comments classmates and I made privately years ago - when I was 16 years old, months before the shooting - in an attempt to be as extreme and shocking as possible.</p>
<p>I immediately apologized.</p>
<p>Here is my apology:</p>
<img src="/images/kyle1.jpg" class="[kk]" width="882" height="356">
<p>3/ After I issued this apology, speculative articles were written, my peers used the opportunity to attack me, and my life was once again reduced to a headline.</p>
<p>It sent me into one of the darkest spirals of my life.</p>
<p>4/ After the story broke, former peers &amp; political opponents began contacting Harvard urging them to rescind me. Harvard then sent this letter stating that Harvard “reserves the right to withdraw an offer of admission” and requested a written explanation within 72 hours.<br><img src="/images/kyle2.jpg" class="[kk]" width="386" height="490"></p>
<p>5/ I responded to the letter with a full explanation, apology, and requested documents.<br><img src="/images/kyle3.jpg" class="[kk]"><br><img src="/images/kyle4.jpg" class="[kk]"></p>
<p>6/ I also sent an email to the Office of Diversity and Inclusion to seek guidance on how to right this wrong and work with them once I was on campus.<br><img src="/images/kyle5.jpg" class="[kk]"><br><img src="/images/kyle6.jpg" class="[kk]"></p>
<p>7/ Harvard decided to rescind my admission with the following letter.<br><img src="/images/kyle7.jpg" class="[kk]"></p>
<p>8/ Somewhat ironically, the Office of Diversity and Inclusion sent me this response regarding my apology: </p>
<p>“Thank you for your email. We appreciate your thoughtful reflections and look forward to connecting with you upon your matriculation in the fall of 2020…”<br><img src="/images/kyle8.jpg" class="[kk]"></p>
<p>9/ After receiving Harvard’s letter revoking my acceptance, I responded by asking for the opportunity to have an in-person meeting to make my case face to face and work towards any possible path of reconciliation.</p>
<p>Harvard responded by declining my meeting request.<br><img src="/images/kyle9.jpg" class="[kk]"><br><img src="/images/kyle10.jpg" class="[kk]"></p>
<p>10/ Harvard deciding that someone can’t grow, especially after a life-altering event like the shooting, is deeply concerning. If any institution should understand growth, it’s Harvard, which is looked to as the pinnacle of higher education despite its checkered past.</p>
<p>11/ Throughout its history, Harvard’s faculty has included slave owners, segregationists, bigots and antisemites. If Harvard is suggesting that growth isn’t possible and that our past defines our future, then Harvard is an inherently racist institution.</p>
<p>But I don’t believe that.</p>
<p>12/ I believe that institutions and people can grow. I’ve said that repeatedly. </p>
<p>In the end, this isn’t about me, it’s about whether we live in a society in which forgiveness is possible or mistakes brand you as irredeemable, as Harvard has decided for me.</p>
<p>13/ So what now? I’m figuring it out. </p>
<p>I had given up huge scholarships in order to go to Harvard, and the deadline for accepting other college offers has ended.</p>
<p>I’m exploring all options at the moment.</p>
<h3 id="已曝光出来的言论"><a href="#已曝光出来的言论" class="headerlink" title="已曝光出来的言论"></a><a href="https://www.huffpost.com/entry/parkland-teen-kyle-kashuv-apologizes-racist-remarks_n_5ce6908be4b09b23e65ead62?guccounter=1" target="_blank" rel="noopener">已曝光出来的言论</a></h3><img src="/images/kyle11.jpg" class="[kk]">
<img src="/images/kyle12.jpg" class="[kk]">
<img src="/images/kyle13.jpg" class="[kk]">
<h3 id="如何"><a href="#如何" class="headerlink" title="如何"></a>如何</h3><p>各主流媒体已不乏专门文章，国内也已有一两篇观察文章。<br>即便没有2017以及2013年的类似案例，招生自主，哈佛更改这个最终决定的可能性应该完全不存在。</p>
<p>前两年，附中有类似事情做过内部讨论。<br>没有意外，之后，还会有类似事情继续发生，无论这里那里。</p>
<p>13则申辩解释，前一半够正确够精致，后一半也够气急败坏。<br>但当这件事发生的那一刻起，再正确的解释其实也已经基本失效。</p>
<p>16岁的你我，每一处的的每一个词，都在呈现并且定义；人当然会变，但发生过的，却也一直存在；<br>选择，对应结果；变好变坏，对应之后的结果。</p>
<p>在北大附中，很多事情，一直指向这一点。</p>

          
        
      
    </div>

    

    
    
    

    <div>
  
</div>

<div>
    
</div>


    

    
      
    
    

    

    <footer class="post-footer">
      

      

      

      
      
        <div class="post-eof"></div>
      
    </footer>
  </div>
  
  
  
  </article>


    
      

  

  
  
  

  

  <article class="post post-type-normal" itemscope itemtype="http://schema.org/Article">
  
  
  
  <div class="post-block">
    <link itemprop="mainEntityOfPage" href="https://suenyu.github.io/2019/06/23/week25/">

    <span hidden itemprop="author" itemscope itemtype="http://schema.org/Person">
      <meta itemprop="name" content="suen">
      <meta itemprop="description" content>
      <meta itemprop="image" content="/images/avatar.gif">
    </span>

    <span hidden itemprop="publisher" itemscope itemtype="http://schema.org/Organization">
      <meta itemprop="name" content="无余说">
    </span>

    
      <header class="post-header">

        
        
          <h1 class="post-title" itemprop="name headline">
                
                
                <a href="/2019/06/23/week25/" class="post-title-link" itemprop="url">第25周分享</a>
              
            
          </h1>
        

        <div class="post-meta">
          <span class="post-time">

            
            
            

            
              <span class="post-meta-item-icon">
                <i class="fa fa-calendar-o"></i>
              </span>
              
                <span class="post-meta-item-text">发表于</span>
              

              
                
              

              <time title="创建时间：2019-06-23 08:30:13 / 修改时间：10:14:54" itemprop="dateCreated datePublished" datetime="2019-06-23T08:30:13+08:00">2019-06-23</time>
            

            
              

              
            
          </span>

          
            <span class="post-category">
            
              <span class="post-meta-divider">|</span>
            
              <span class="post-meta-item-icon">
                <i class="fa fa-folder-o"></i>
              </span>
              
                <span class="post-meta-item-text">分类于</span>
              
              
                <span itemprop="about" itemscope itemtype="http://schema.org/Thing"><a href="/categories/每周分享/" itemprop="url" rel="index"><span itemprop="name">每周分享</span></a></span>

                
                
              
            </span>
          

          
            
            
              
              <span class="post-comments-count">
                <span class="post-meta-divider">|</span>
                <span class="post-meta-item-icon">
                  <i class="fa fa-comment-o"></i>
                </span>
            
                <span class="post-meta-item-text">评论数：</span>
                <a href="/2019/06/23/week25/#comments" itemprop="discussionUrl">
                  <span class="post-comments-count valine-comment-count" data-xid="/2019/06/23/week25/" itemprop="commentCount"></span>
                </a>
              </span>
            
          

          
          
            <span id="/2019/06/23/week25/" class="leancloud_visitors" data-flag-title="第25周分享">
              <span class="post-meta-divider">|</span>
              <span class="post-meta-item-icon">
                <i class="fa fa-eye"></i>
              </span>
              
                <span class="post-meta-item-text">阅读次数：</span>
              
                <span class="leancloud-visitors-count"></span>
            </span>
          

          

          
            <div class="post-symbolscount">
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-file-word-o"></i>
                </span>
                
                  <span class="post-meta-item-text">本文字数：</span>
                
                <span title="本文字数">1.8k</span>
              

              
                <span class="post-meta-divider">|</span>
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-clock-o"></i>
                </span>
                
                  <span class="post-meta-item-text">阅读时长 &asymp;</span>
                
                <span title="阅读时长">5 分钟</span>
              
            </div>
          

          

        </div>
      </header>
    

    
    
    
    <div class="post-body" itemprop="articleBody">

      
      

      
        
          
            <h2 id="教育创新的学校们"><a href="#教育创新的学校们" class="headerlink" title="教育创新的学校们"></a>教育创新的学校们</h2><p>读到<a href="https://mp.weixin.qq.com/s?__biz=MjM5NjAwODI2OQ==&amp;mid=2653382823&amp;idx=1&amp;sn=3d6a1e6687f61cdf3e0ed7958e8f0c9f&amp;chksm=bd3c10858a4b99939ebf45aa745f309c6ee4f6807a565446953bf7fc197a1f5730249f95ba5f&amp;mpshare=1&amp;scene=1&amp;srcid=0623QLE0C1iqZRnjXzKftyWM&amp;pass_ticket=cVzzRnejBdefQeh5gP7i444NHyHQJKxX5COknBA%2BIsH3%2BAZkZ3OcHFQ7FPxSHLZr#rd" target="_blank" rel="noopener">走出应试与素质教育的两难困境，这所中学只做了一件事</a>，看一些人，在考试成绩与反抗畸形教育的深坑内挣扎，泉源在号称教育创新的队伍内，还是比较显赫的，但，半夜投诉、队伍重组、出入于PBL深坑……这些，在北大附中十年改革史上，在在皆有。</p>
<p>关于人，他们走到这里：</p>
<blockquote>
<p>这是一个借助课程中心的设计优势强制推动的过程。<br>“一开始主要分享PBL相关理论常识，除了零星三四位老师有学习意向，其他老师基本属于应付——‘我知道这个东西好，但是没办法实施。’”<br>这句话不经意间，道出了泉源的另一个潜藏危机——这群公立学校的资深教师，虽然厌倦了传统高中的教学模式，但他们的身体仍然留在传统的习惯里，对教学创新本能地感到麻烦，不自信，甚至尚未起步就开始怀疑。<br>“项目式学习对学生的评价方式迥异，它要求老师价值观的彻底转型。”在李斌看来，这是一场对老师而言难度大于学生的转型，“老师不再是学习进程的领导者，他需要了解学生的学习状态，并在关键环节给与支持。这种角色转换，对习惯传统教学节奏的教师而言是一个革命性的要求。”</p>
</blockquote>
<p>关于事，他们走到这里：</p>
<blockquote>
<p>如何通过精心设计，巧妙的把高中课标课程内容更集约地融入项目，使孩子们在锻炼相关能力的同时，能生动高效地学习课标课程，和高考完美接轨，成了这一阶段的核心任务。</p>
</blockquote>
<p>显然，这背后，如果是不断不得不割舍关键词的过程，那么此刻唯一剩下的词，也只能是———求生。<br>当然，这一切，可以理解，且依旧值得尊重。</p>
<p>从国外不得不关闭学校的altschool，到国内求生求新的泉源、一土、探月……，都不乏光芒；但，无论依托平台或应用的技术流，抑或依托百年前的PBL或芬兰最新的Phenomenon-based learning学术流，在整个教育场域，本质上属于微商的这些学校，并不能改变公立学校的什么。国内对教育的大气候，也决定了这类学校的生存注定是深坑夹缝。<br>值得尊敬，但，大势如此。</p>
<h2 id="从公立学校内部突围"><a href="#从公立学校内部突围" class="headerlink" title="从公立学校内部突围"></a>从公立学校内部突围</h2><p>我一直认为，博雅学院做的事情，就是从内部突围。<br>这里是北大附中，这里有一个在基础教育界做出什么事情都会被认为正常的校长，这里有突围的可能。<br>无论最初的google生态，还是现在的Microsoft生态，技术是先锋，2017年至2019年的此刻，大势已定，不必再刻意经营。<br>之后一年，PBL，就是新的突围点。</p>
<p>之所以突围，和泉源的起因无不同：</p>
<blockquote>
<p>“做着做着觉得这种教育不对”</p>
</blockquote>
<p>不对的点，说到底只有一件：学习，在学校，不是人主动想做的事情。</p>
<p>不得不先说明，这一点，其实是教育理念的选择。<br>确实有并不主动的人被体制成功培养做出了很多值得赞许的事情，但，这不是我选择的理想教育。<br>衡水中学做的选择，和北大附中的选择，都值得尊重；前提是，每个人每个学校在自己选择的路上，做到无所顾忌做到死磕到底。<br>北大附中的培养目标，最先就是个性鲜明，都被动了，还鲜明什么？<br>北大附中现状，学习，在学校，是大家主动想做的事情吗？<br>我的判断：显然不是。<br>所以，无论学校结构性调整还是学院单点突破，直面这个不对，全力解决这个不对，就是我们要做的事情。<br>这个注定没有答案，注定会一直在路上。</p>
<p>每天每天，被固定的群体在固定的地点按照固定的进度完成固定的任务去获取固定的评价……<br>背后是国家要求、学校规定、家长期待……<br>是吧？</p>
<p>如果没有了国家课标，没有了学校规定，没有了高考，我们开出的这些课程，有多少还会被学生选择？<br>不追问到这个极端，就永远没有办法直面我们所谓课程所谓学科所谓项目的价值。</p>
<h2 id="项目的坑"><a href="#项目的坑" class="headerlink" title="项目的坑"></a>项目的坑</h2><p>项目和课程究竟有什么不同？项目主管们写了总结，理解程度不一。<br>说到底，对现有框架、时空做突破的项目，要用更动态更个性化的方式，不断让更多人有自主去学的意识和自己去学的能力。</p>
<p>这和某一学科框架无关，和如何让人体会学习的意义有关，这天然决定了我们必须面对学科不需要面对的问题：</p>
<blockquote>
<p>如何实现“低控制力下的自主学习”</p>
</blockquote>
<p>回顾开头的文章，之所以我会判断其只剩下了求生，正是因为泉源已经离开了这一点。</p>
<ul>
<li>如何用学习自身的价值与快乐实现学生自我驱动而非你不得不高考所以你爱听不听爱学不学；</li>
<li>如何在学生没有外部高压时引导其学会规划个人时间进度学习进度；</li>
</ul>
<p>这个，只有硬杠，没有退路。</p>
<p>也因此，作为项目主管，面对化理念为实际的各类繁琐，面对确认项目设计处处落地而不虚飘，就只能是必须。<br>PBL和git背后，说到底，是这个思路。</p>
<p>没错，这需要有教育理想，同时，也需要有将理想折中到现实的韧性。</p>
<p>泉源会死吗？也许；<br>我们的项目会吗？也许；</p>
<img src="/images/busy.jpg" class="[busy]" width="600" height="479">

          
        
      
    </div>

    

    
    
    

    <div>
  
</div>

<div>
    
</div>


    

    
      
    
    

    

    <footer class="post-footer">
      

      

      

      
      
        <div class="post-eof"></div>
      
    </footer>
  </div>
  
  
  
  </article>


    
      

  

  
  
  

  

  <article class="post post-type-normal" itemscope itemtype="http://schema.org/Article">
  
  
  
  <div class="post-block">
    <link itemprop="mainEntityOfPage" href="https://suenyu.github.io/2019/06/15/week24/">

    <span hidden itemprop="author" itemscope itemtype="http://schema.org/Person">
      <meta itemprop="name" content="suen">
      <meta itemprop="description" content>
      <meta itemprop="image" content="/images/avatar.gif">
    </span>

    <span hidden itemprop="publisher" itemscope itemtype="http://schema.org/Organization">
      <meta itemprop="name" content="无余说">
    </span>

    
      <header class="post-header">

        
        
          <h1 class="post-title" itemprop="name headline">
                
                
                <a href="/2019/06/15/week24/" class="post-title-link" itemprop="url">第24周分享</a>
              
            
          </h1>
        

        <div class="post-meta">
          <span class="post-time">

            
            
            

            
              <span class="post-meta-item-icon">
                <i class="fa fa-calendar-o"></i>
              </span>
              
                <span class="post-meta-item-text">发表于</span>
              

              
                
              

              <time title="创建时间：2019-06-15 09:13:17 / 修改时间：09:52:53" itemprop="dateCreated datePublished" datetime="2019-06-15T09:13:17+08:00">2019-06-15</time>
            

            
              

              
            
          </span>

          
            <span class="post-category">
            
              <span class="post-meta-divider">|</span>
            
              <span class="post-meta-item-icon">
                <i class="fa fa-folder-o"></i>
              </span>
              
                <span class="post-meta-item-text">分类于</span>
              
              
                <span itemprop="about" itemscope itemtype="http://schema.org/Thing"><a href="/categories/每周分享/" itemprop="url" rel="index"><span itemprop="name">每周分享</span></a></span>

                
                
              
            </span>
          

          
            
            
              
              <span class="post-comments-count">
                <span class="post-meta-divider">|</span>
                <span class="post-meta-item-icon">
                  <i class="fa fa-comment-o"></i>
                </span>
            
                <span class="post-meta-item-text">评论数：</span>
                <a href="/2019/06/15/week24/#comments" itemprop="discussionUrl">
                  <span class="post-comments-count valine-comment-count" data-xid="/2019/06/15/week24/" itemprop="commentCount"></span>
                </a>
              </span>
            
          

          
          
            <span id="/2019/06/15/week24/" class="leancloud_visitors" data-flag-title="第24周分享">
              <span class="post-meta-divider">|</span>
              <span class="post-meta-item-icon">
                <i class="fa fa-eye"></i>
              </span>
              
                <span class="post-meta-item-text">阅读次数：</span>
              
                <span class="leancloud-visitors-count"></span>
            </span>
          

          

          
            <div class="post-symbolscount">
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-file-word-o"></i>
                </span>
                
                  <span class="post-meta-item-text">本文字数：</span>
                
                <span title="本文字数">494</span>
              

              
                <span class="post-meta-divider">|</span>
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-clock-o"></i>
                </span>
                
                  <span class="post-meta-item-text">阅读时长 &asymp;</span>
                
                <span title="阅读时长">1 分钟</span>
              
            </div>
          

          

        </div>
      </header>
    

    
    
    
    <div class="post-body" itemprop="articleBody">

      
      

      
        
          
            <p>在这个北大附中，更新是一种力量，每年45678月的结构化更新，更是。<br>在很多学校10年都不一定能变的事情，在这里，1年可能都算长时间了。<br>改与不改，都是利弊相生；<br>所以，无非选择。</p>
<p>不是每个人都适应，但结构化这个词就意味着，当你有你的计划，这个世界另有计划时，要么，你改变世界，要么，你改变你的计划。<br>一直有人没看懂，也一直有人装没看懂。</p>
<p>博雅之内，从课程到项目，不止看懂，并要不断从0到1。<br>博雅之外，有些人真不懂，那就按学院要求做就是了。说到底，有些事情，对有些人，解释成本过高。</p>
<table>
<thead>
<tr>
<th style="text-align:center">时间</th>
<th style="text-align:center">一</th>
<th style="text-align:center">二</th>
<th style="text-align:center">三</th>
<th style="text-align:center">四</th>
<th style="text-align:center">五</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center">8：00-9：00</td>
<td style="text-align:center">1</td>
<td style="text-align:center">5</td>
<td style="text-align:center">4</td>
<td style="text-align:center">6</td>
<td style="text-align:center">3</td>
</tr>
<tr>
<td style="text-align:center">9：10-10：10</td>
<td style="text-align:center">2</td>
<td style="text-align:center">6</td>
<td style="text-align:center">3</td>
<td style="text-align:center">5</td>
<td style="text-align:center">4</td>
</tr>
<tr>
<td style="text-align:center">10：20-11：20/50</td>
<td style="text-align:center">⑥</td>
<td style="text-align:center">④</td>
<td style="text-align:center">⑤</td>
<td style="text-align:center">③</td>
<td style="text-align:center">Ⓐ</td>
</tr>
<tr>
<td style="text-align:center">13：30-14：30</td>
<td style="text-align:center">3</td>
<td style="text-align:center">2</td>
<td style="text-align:center"></td>
<td style="text-align:center">1</td>
<td style="text-align:center">5</td>
</tr>
<tr>
<td style="text-align:center">14：40-15：40</td>
<td style="text-align:center">4</td>
<td style="text-align:center">1</td>
<td style="text-align:center"></td>
<td style="text-align:center">2</td>
<td style="text-align:center">6</td>
</tr>
<tr>
<td style="text-align:center">15：50-16：50/17:20</td>
<td style="text-align:center">⑤</td>
<td style="text-align:center">③</td>
<td style="text-align:center">⑥</td>
<td style="text-align:center">④</td>
<td style="text-align:center">Ⓑ</td>
</tr>
</tbody>
</table>
<p>荣誉文凭启动评选，因链接权限，有看到精致利己的辩护，也有看到点透之后的释然，依旧是每个人的选择；<br>但不是每个选择，都值得欣赏。</p>
<p>明天毕业典礼，将要离开的人，有多少，真正来过？</p>

          
        
      
    </div>

    

    
    
    

    <div>
  
</div>

<div>
    
</div>


    

    
      
    
    

    

    <footer class="post-footer">
      

      

      

      
      
        <div class="post-eof"></div>
      
    </footer>
  </div>
  
  
  
  </article>


    
      

  

  
  
  

  

  <article class="post post-type-normal" itemscope itemtype="http://schema.org/Article">
  
  
  
  <div class="post-block">
    <link itemprop="mainEntityOfPage" href="https://suenyu.github.io/2019/06/07/week23/">

    <span hidden itemprop="author" itemscope itemtype="http://schema.org/Person">
      <meta itemprop="name" content="suen">
      <meta itemprop="description" content>
      <meta itemprop="image" content="/images/avatar.gif">
    </span>

    <span hidden itemprop="publisher" itemscope itemtype="http://schema.org/Organization">
      <meta itemprop="name" content="无余说">
    </span>

    
      <header class="post-header">

        
        
          <h1 class="post-title" itemprop="name headline">
                
                
                <a href="/2019/06/07/week23/" class="post-title-link" itemprop="url">第23周分享</a>
              
            
          </h1>
        

        <div class="post-meta">
          <span class="post-time">

            
            
            

            
              <span class="post-meta-item-icon">
                <i class="fa fa-calendar-o"></i>
              </span>
              
                <span class="post-meta-item-text">发表于</span>
              

              
                
              

              <time title="创建时间：2019-06-07 21:58:53" itemprop="dateCreated datePublished" datetime="2019-06-07T21:58:53+08:00">2019-06-07</time>
            

            
              

              
                
                <span class="post-meta-divider">|</span>
                

                <span class="post-meta-item-icon">
                  <i class="fa fa-calendar-check-o"></i>
                </span>
                
                  <span class="post-meta-item-text">更新于</span>
                
                <time title="修改时间：2019-06-09 07:57:38" itemprop="dateModified" datetime="2019-06-09T07:57:38+08:00">2019-06-09</time>
              
            
          </span>

          
            <span class="post-category">
            
              <span class="post-meta-divider">|</span>
            
              <span class="post-meta-item-icon">
                <i class="fa fa-folder-o"></i>
              </span>
              
                <span class="post-meta-item-text">分类于</span>
              
              
                <span itemprop="about" itemscope itemtype="http://schema.org/Thing"><a href="/categories/每周分享/" itemprop="url" rel="index"><span itemprop="name">每周分享</span></a></span>

                
                
              
            </span>
          

          
            
            
              
              <span class="post-comments-count">
                <span class="post-meta-divider">|</span>
                <span class="post-meta-item-icon">
                  <i class="fa fa-comment-o"></i>
                </span>
            
                <span class="post-meta-item-text">评论数：</span>
                <a href="/2019/06/07/week23/#comments" itemprop="discussionUrl">
                  <span class="post-comments-count valine-comment-count" data-xid="/2019/06/07/week23/" itemprop="commentCount"></span>
                </a>
              </span>
            
          

          
          
            <span id="/2019/06/07/week23/" class="leancloud_visitors" data-flag-title="第23周分享">
              <span class="post-meta-divider">|</span>
              <span class="post-meta-item-icon">
                <i class="fa fa-eye"></i>
              </span>
              
                <span class="post-meta-item-text">阅读次数：</span>
              
                <span class="leancloud-visitors-count"></span>
            </span>
          

          

          
            <div class="post-symbolscount">
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-file-word-o"></i>
                </span>
                
                  <span class="post-meta-item-text">本文字数：</span>
                
                <span title="本文字数">2.8k</span>
              

              
                <span class="post-meta-divider">|</span>
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-clock-o"></i>
                </span>
                
                  <span class="post-meta-item-text">阅读时长 &asymp;</span>
                
                <span title="阅读时长">7 分钟</span>
              
            </div>
          

          

        </div>
      </header>
    

    
    
    
    <div class="post-body" itemprop="articleBody">

      
      

      
        
          <h3 id="教育点"><a href="#教育点" class="headerlink" title="教育点"></a>教育点</h3><p><a href="https://www.washingtonpost.com/education/2018/12/12/project-based-learning-is-new-rage-education-never-mind-that-its-century-old/?noredirect=on&amp;utm_term=.4ca6d1ea645d" target="_blank" rel="noopener">《Project-based learning is a new rage in education. Never mind that it’s a century old》</a></p>
<p>2018年邮报的这篇文章，可以用三句话概括：</p>
<ul>
<li>从100年前的“The Project Method”到现在开始流行的PBL，初心都是认为现行教学方式培养不出这个世界需要的人才。</li>
<li>现行教学方式的核心特征，百年前和此刻，都是emphasizing breadth and recall；很多必修，强调在考试时能复现所学。</li>
<li>TPM和PBL的核心特征都在focusing instead on depth and engagement。</li>
</ul>
<p>太阳底下传说是没有新鲜事的，理论翻来，理论翻去，唱罢登场，说是循环进步，但仅在教育范畴内观照，理论迁延也或者如诗词曲，各成高峰而已。</p>
<p>变的从来是时代，教育不得不跟进而已。</p>
<p>也因此，芬兰的Phenomenon-based learning更可贵些，对芬兰或者已经是不得不；但对整个世界而言，这个概念还是引领:<br>
          <!--noindex-->
          
            <div class="post-button text-center">
              <a class="btn" href="/2019/06/07/week23/#more" rel="contents">
                阅读全文 &raquo;
              </a>
            </div>
          
          <!--/noindex-->
        
      
    </p></div>

    

    
    
    

    <div>
  
</div>

<div>
    
</div>


    

    
      
    
    

    

    <footer class="post-footer">
      

      

      

      
      
        <div class="post-eof"></div>
      
    </footer>
  </div>
  
  
  
  </article>


    
      

  

  
  
  

  

  <article class="post post-type-normal" itemscope itemtype="http://schema.org/Article">
  
  
  
  <div class="post-block">
    <link itemprop="mainEntityOfPage" href="https://suenyu.github.io/2019/06/02/week22/">

    <span hidden itemprop="author" itemscope itemtype="http://schema.org/Person">
      <meta itemprop="name" content="suen">
      <meta itemprop="description" content>
      <meta itemprop="image" content="/images/avatar.gif">
    </span>

    <span hidden itemprop="publisher" itemscope itemtype="http://schema.org/Organization">
      <meta itemprop="name" content="无余说">
    </span>

    
      <header class="post-header">

        
        
          <h1 class="post-title" itemprop="name headline">
                
                
                <a href="/2019/06/02/week22/" class="post-title-link" itemprop="url">第22周分享</a>
              
            
          </h1>
        

        <div class="post-meta">
          <span class="post-time">

            
            
            

            
              <span class="post-meta-item-icon">
                <i class="fa fa-calendar-o"></i>
              </span>
              
                <span class="post-meta-item-text">发表于</span>
              

              
                
              

              <time title="创建时间：2019-06-02 09:57:58 / 修改时间：18:23:51" itemprop="dateCreated datePublished" datetime="2019-06-02T09:57:58+08:00">2019-06-02</time>
            

            
              

              
            
          </span>

          
            <span class="post-category">
            
              <span class="post-meta-divider">|</span>
            
              <span class="post-meta-item-icon">
                <i class="fa fa-folder-o"></i>
              </span>
              
                <span class="post-meta-item-text">分类于</span>
              
              
                <span itemprop="about" itemscope itemtype="http://schema.org/Thing"><a href="/categories/每周分享/" itemprop="url" rel="index"><span itemprop="name">每周分享</span></a></span>

                
                
              
            </span>
          

          
            
            
              
              <span class="post-comments-count">
                <span class="post-meta-divider">|</span>
                <span class="post-meta-item-icon">
                  <i class="fa fa-comment-o"></i>
                </span>
            
                <span class="post-meta-item-text">评论数：</span>
                <a href="/2019/06/02/week22/#comments" itemprop="discussionUrl">
                  <span class="post-comments-count valine-comment-count" data-xid="/2019/06/02/week22/" itemprop="commentCount"></span>
                </a>
              </span>
            
          

          
          
            <span id="/2019/06/02/week22/" class="leancloud_visitors" data-flag-title="第22周分享">
              <span class="post-meta-divider">|</span>
              <span class="post-meta-item-icon">
                <i class="fa fa-eye"></i>
              </span>
              
                <span class="post-meta-item-text">阅读次数：</span>
              
                <span class="leancloud-visitors-count"></span>
            </span>
          

          

          
            <div class="post-symbolscount">
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-file-word-o"></i>
                </span>
                
                  <span class="post-meta-item-text">本文字数：</span>
                
                <span title="本文字数">2k</span>
              

              
                <span class="post-meta-divider">|</span>
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-clock-o"></i>
                </span>
                
                  <span class="post-meta-item-text">阅读时长 &asymp;</span>
                
                <span title="阅读时长">5 分钟</span>
              
            </div>
          

          

        </div>
      </header>
    

    
    
    
    <div class="post-body" itemprop="articleBody">

      
      

      
        
          <h3 id="教育点"><a href="#教育点" class="headerlink" title="教育点"></a>教育点</h3><p>偶尔听到初中部眼保健操的音乐，翻检看到2012年眼保健操利弊的讨论，比较明确的结论是，60年前推行时，并无科学依据，反倒类似聊胜于无所以推行，之后形成惯例，漫说动不得，能追问这玩意有没有用的已然是少数。以举国如此的效果，以医学这种显然需要实证的学科，决策的过程，无疑早已寻不到，这背后，无非不扎实不认真，教育部是团队还是团伙呢？<br>高考还有几天，自恢复以来，命题流程官方解析几乎无一可查；对比台湾指考每年公开出的命题相关会议纪要详细解析等，大陆命题组只怕连团伙都还不是。<br>把更多应该被记忆的事情公示出来，是非对错公私利弊，一时即便不清，至少，也给之后一个起点。<br>翻看手机中若干退过多轮的学校事务微信群，就可以知道，即便北大附中，这个记录与公示的路，也还太长。<br>技术问题吗？显然不是。<br>
          <!--noindex-->
          
            <div class="post-button text-center">
              <a class="btn" href="/2019/06/02/week22/#more" rel="contents">
                阅读全文 &raquo;
              </a>
            </div>
          
          <!--/noindex-->
        
      
    </p></div>

    

    
    
    

    <div>
  
</div>

<div>
    
</div>


    

    
      
    
    

    

    <footer class="post-footer">
      

      

      

      
      
        <div class="post-eof"></div>
      
    </footer>
  </div>
  
  
  
  </article>


    
      

  

  
  
  

  

  <article class="post post-type-normal" itemscope itemtype="http://schema.org/Article">
  
  
  
  <div class="post-block">
    <link itemprop="mainEntityOfPage" href="https://suenyu.github.io/2019/05/26/fgfw/">

    <span hidden itemprop="author" itemscope itemtype="http://schema.org/Person">
      <meta itemprop="name" content="suen">
      <meta itemprop="description" content>
      <meta itemprop="image" content="/images/avatar.gif">
    </span>

    <span hidden itemprop="publisher" itemscope itemtype="http://schema.org/Organization">
      <meta itemprop="name" content="无余说">
    </span>

    
      <header class="post-header">

        
        
          <h1 class="post-title" itemprop="name headline">
                
                
                <a href="/2019/05/26/fgfw/" class="post-title-link" itemprop="url">捉鬼</a>
              
            
          </h1>
        

        <div class="post-meta">
          <span class="post-time">

            
            
            

            
              <span class="post-meta-item-icon">
                <i class="fa fa-calendar-o"></i>
              </span>
              
                <span class="post-meta-item-text">发表于</span>
              

              
                
              

              <time title="创建时间：2019-05-26 18:46:10" itemprop="dateCreated datePublished" datetime="2019-05-26T18:46:10+08:00">2019-05-26</time>
            

            
              

              
                
                <span class="post-meta-divider">|</span>
                

                <span class="post-meta-item-icon">
                  <i class="fa fa-calendar-check-o"></i>
                </span>
                
                  <span class="post-meta-item-text">更新于</span>
                
                <time title="修改时间：2019-06-02 14:07:41" itemprop="dateModified" datetime="2019-06-02T14:07:41+08:00">2019-06-02</time>
              
            
          </span>

          
            <span class="post-category">
            
              <span class="post-meta-divider">|</span>
            
              <span class="post-meta-item-icon">
                <i class="fa fa-folder-o"></i>
              </span>
              
                <span class="post-meta-item-text">分类于</span>
              
              
                <span itemprop="about" itemscope itemtype="http://schema.org/Thing"><a href="/categories/internet/" itemprop="url" rel="index"><span itemprop="name">internet</span></a></span>

                
                
              
            </span>
          

          
            
            
              
              <span class="post-comments-count">
                <span class="post-meta-divider">|</span>
                <span class="post-meta-item-icon">
                  <i class="fa fa-comment-o"></i>
                </span>
            
                <span class="post-meta-item-text">评论数：</span>
                <a href="/2019/05/26/fgfw/#comments" itemprop="discussionUrl">
                  <span class="post-comments-count valine-comment-count" data-xid="/2019/05/26/fgfw/" itemprop="commentCount"></span>
                </a>
              </span>
            
          

          
          
            <span id="/2019/05/26/fgfw/" class="leancloud_visitors" data-flag-title="捉鬼">
              <span class="post-meta-divider">|</span>
              <span class="post-meta-item-icon">
                <i class="fa fa-eye"></i>
              </span>
              
                <span class="post-meta-item-text">阅读次数：</span>
              
                <span class="leancloud-visitors-count"></span>
            </span>
          

          

          
            <div class="post-symbolscount">
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-file-word-o"></i>
                </span>
                
                  <span class="post-meta-item-text">本文字数：</span>
                
                <span title="本文字数">950</span>
              

              
                <span class="post-meta-divider">|</span>
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-clock-o"></i>
                </span>
                
                  <span class="post-meta-item-text">阅读时长 &asymp;</span>
                
                <span title="阅读时长">2 分钟</span>
              
            </div>
          

          

        </div>
      </header>
    

    
    
    
    <div class="post-body" itemprop="articleBody">

      
      

      
        
          <p>这个月初，vultr的vps突然没了响应，因为只是备用，一直没在意；周末，回应学生关于sharepoint访问速度问题，顺便捉了下鬼。</p>
<p>tracert结果显示，这个ip确实挂了，因为是纯自用，唯一可推测到的原因，只能是被附带伤害了。<br>这个时间节点，如此的大气候；无解，直接Server Destroy，重建到New York (NJ)</p>
<p><center><img src="/images/vultr.png" class="[NY]" width="600" height="480"></center><br>
          <!--noindex-->
          
            <div class="post-button text-center">
              <a class="btn" href="/2019/05/26/fgfw/#more" rel="contents">
                阅读全文 &raquo;
              </a>
            </div>
          
          <!--/noindex-->
        
      
    </p></div>

    

    
    
    

    <div>
  
</div>

<div>
    
</div>


    

    
      
    
    

    

    <footer class="post-footer">
      

      

      

      
      
        <div class="post-eof"></div>
      
    </footer>
  </div>
  
  
  
  </article>


    
      

  

  
  
  

  

  <article class="post post-type-normal" itemscope itemtype="http://schema.org/Article">
  
  
  
  <div class="post-block">
    <link itemprop="mainEntityOfPage" href="https://suenyu.github.io/2019/05/25/githubsso/">

    <span hidden itemprop="author" itemscope itemtype="http://schema.org/Person">
      <meta itemprop="name" content="suen">
      <meta itemprop="description" content>
      <meta itemprop="image" content="/images/avatar.gif">
    </span>

    <span hidden itemprop="publisher" itemscope itemtype="http://schema.org/Organization">
      <meta itemprop="name" content="无余说">
    </span>

    
      <header class="post-header">

        
        
          <h1 class="post-title" itemprop="name headline">
                
                
                <a href="/2019/05/25/githubsso/" class="post-title-link" itemprop="url">Office365到学校Github的SSO</a>
              
            
          </h1>
        

        <div class="post-meta">
          <span class="post-time">

            
            
            

            
              <span class="post-meta-item-icon">
                <i class="fa fa-calendar-o"></i>
              </span>
              
                <span class="post-meta-item-text">发表于</span>
              

              
                
              

              <time title="创建时间：2019-05-25 15:19:12" itemprop="dateCreated datePublished" datetime="2019-05-25T15:19:12+08:00">2019-05-25</time>
            

            
              

              
                
                <span class="post-meta-divider">|</span>
                

                <span class="post-meta-item-icon">
                  <i class="fa fa-calendar-check-o"></i>
                </span>
                
                  <span class="post-meta-item-text">更新于</span>
                
                <time title="修改时间：2019-05-26 08:55:59" itemprop="dateModified" datetime="2019-05-26T08:55:59+08:00">2019-05-26</time>
              
            
          </span>

          
            <span class="post-category">
            
              <span class="post-meta-divider">|</span>
            
              <span class="post-meta-item-icon">
                <i class="fa fa-folder-o"></i>
              </span>
              
                <span class="post-meta-item-text">分类于</span>
              
              
                <span itemprop="about" itemscope itemtype="http://schema.org/Thing"><a href="/categories/github/" itemprop="url" rel="index"><span itemprop="name">github</span></a></span>

                
                
                  ，
                
              
                <span itemprop="about" itemscope itemtype="http://schema.org/Thing"><a href="/categories/O365/" itemprop="url" rel="index"><span itemprop="name">O365</span></a></span>

                
                
              
            </span>
          

          
            
            
              
              <span class="post-comments-count">
                <span class="post-meta-divider">|</span>
                <span class="post-meta-item-icon">
                  <i class="fa fa-comment-o"></i>
                </span>
            
                <span class="post-meta-item-text">评论数：</span>
                <a href="/2019/05/25/githubsso/#comments" itemprop="discussionUrl">
                  <span class="post-comments-count valine-comment-count" data-xid="/2019/05/25/githubsso/" itemprop="commentCount"></span>
                </a>
              </span>
            
          

          
          
            <span id="/2019/05/25/githubsso/" class="leancloud_visitors" data-flag-title="Office365到学校Github的SSO">
              <span class="post-meta-divider">|</span>
              <span class="post-meta-item-icon">
                <i class="fa fa-eye"></i>
              </span>
              
                <span class="post-meta-item-text">阅读次数：</span>
              
                <span class="leancloud-visitors-count"></span>
            </span>
          

          

          
            <div class="post-symbolscount">
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-file-word-o"></i>
                </span>
                
                  <span class="post-meta-item-text">本文字数：</span>
                
                <span title="本文字数">646</span>
              

              
                <span class="post-meta-divider">|</span>
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-clock-o"></i>
                </span>
                
                  <span class="post-meta-item-text">阅读时长 &asymp;</span>
                
                <span title="阅读时长">2 分钟</span>
              
            </div>
          

          

        </div>
      </header>
    

    
    
    
    <div class="post-body" itemprop="articleBody">

      
      

      
        
          <p>要推Github，就要最大限度解决365账号直接进入Github学校仓库的问题。前两周引入了<a href="https://orgmanager.miguelpiedrafita.com/join/24676035" target="_blank" rel="noopener">第三方加入法</a>，但一则有墙外验证码的坑，一则还是有安全隐患。所以，这个周末，重新想办法。<br>几年前希望学生使用365账号单点进入各类MOOC时，在AZURE有过类似操作，当时实现了365账号直接进入Coursera的效果；于是，开整。<br>
          <!--noindex-->
          
            <div class="post-button text-center">
              <a class="btn" href="/2019/05/25/githubsso/#more" rel="contents">
                阅读全文 &raquo;
              </a>
            </div>
          
          <!--/noindex-->
        
      
    </p></div>

    

    
    
    

    <div>
  
</div>

<div>
    
</div>


    

    
      
    
    

    

    <footer class="post-footer">
      

      

      

      
      
        <div class="post-eof"></div>
      
    </footer>
  </div>
  
  
  
  </article>


    
      

  

  
  
  

  

  <article class="post post-type-normal" itemscope itemtype="http://schema.org/Article">
  
  
  
  <div class="post-block">
    <link itemprop="mainEntityOfPage" href="https://suenyu.github.io/2019/05/24/week21/">

    <span hidden itemprop="author" itemscope itemtype="http://schema.org/Person">
      <meta itemprop="name" content="suen">
      <meta itemprop="description" content>
      <meta itemprop="image" content="/images/avatar.gif">
    </span>

    <span hidden itemprop="publisher" itemscope itemtype="http://schema.org/Organization">
      <meta itemprop="name" content="无余说">
    </span>

    
      <header class="post-header">

        
        
          <h1 class="post-title" itemprop="name headline">
                
                
                <a href="/2019/05/24/week21/" class="post-title-link" itemprop="url">第21周分享</a>
              
            
          </h1>
        

        <div class="post-meta">
          <span class="post-time">

            
            
            

            
              <span class="post-meta-item-icon">
                <i class="fa fa-calendar-o"></i>
              </span>
              
                <span class="post-meta-item-text">发表于</span>
              

              
                
              

              <time title="创建时间：2019-05-24 20:45:16" itemprop="dateCreated datePublished" datetime="2019-05-24T20:45:16+08:00">2019-05-24</time>
            

            
              

              
                
                <span class="post-meta-divider">|</span>
                

                <span class="post-meta-item-icon">
                  <i class="fa fa-calendar-check-o"></i>
                </span>
                
                  <span class="post-meta-item-text">更新于</span>
                
                <time title="修改时间：2019-06-02 14:37:30" itemprop="dateModified" datetime="2019-06-02T14:37:30+08:00">2019-06-02</time>
              
            
          </span>

          
            <span class="post-category">
            
              <span class="post-meta-divider">|</span>
            
              <span class="post-meta-item-icon">
                <i class="fa fa-folder-o"></i>
              </span>
              
                <span class="post-meta-item-text">分类于</span>
              
              
                <span itemprop="about" itemscope itemtype="http://schema.org/Thing"><a href="/categories/每周分享/" itemprop="url" rel="index"><span itemprop="name">每周分享</span></a></span>

                
                
              
            </span>
          

          
            
            
              
              <span class="post-comments-count">
                <span class="post-meta-divider">|</span>
                <span class="post-meta-item-icon">
                  <i class="fa fa-comment-o"></i>
                </span>
            
                <span class="post-meta-item-text">评论数：</span>
                <a href="/2019/05/24/week21/#comments" itemprop="discussionUrl">
                  <span class="post-comments-count valine-comment-count" data-xid="/2019/05/24/week21/" itemprop="commentCount"></span>
                </a>
              </span>
            
          

          
          
            <span id="/2019/05/24/week21/" class="leancloud_visitors" data-flag-title="第21周分享">
              <span class="post-meta-divider">|</span>
              <span class="post-meta-item-icon">
                <i class="fa fa-eye"></i>
              </span>
              
                <span class="post-meta-item-text">阅读次数：</span>
              
                <span class="leancloud-visitors-count"></span>
            </span>
          

          

          
            <div class="post-symbolscount">
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-file-word-o"></i>
                </span>
                
                  <span class="post-meta-item-text">本文字数：</span>
                
                <span title="本文字数">1.3k</span>
              

              
                <span class="post-meta-divider">|</span>
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-clock-o"></i>
                </span>
                
                  <span class="post-meta-item-text">阅读时长 &asymp;</span>
                
                <span title="阅读时长">3 分钟</span>
              
            </div>
          

          

        </div>
      </header>
    

    
    
    
    <div class="post-body" itemprop="articleBody">

      
      

      
        
          <h3 id="推github"><a href="#推github" class="headerlink" title="推github"></a>推github</h3><p>继续在各个场景下，力推github到全校。回想当初开推365，颇为类似了。<br>推法列举:</p>
<ul>
<li>前两周已经开始将荣誉文凭的事情全线迁移到github，运转效果还不错。</li>
<li>讨论<a href="https://github.com/pkuschool/house-or-not/issues" target="_blank" rel="noopener">书院是否要必须选</a>，其实只是找一个相对敏感的话题看能拉多少人进场，更重要的是，测试github的issue能否在9月作为<a href="https://pkuschool.github.io/public-argument/" target="_blank" rel="noopener">公共说理</a>的对外平台。</li>
<li>SUBIT将<a href="https://pkuschool.github.io/ptm/" target="_blank" rel="noopener">家长会的通知</a>平台放在github，效果极佳。<a href="https://pkuschool.github.io/SubIT/" target="_blank" rel="noopener">社团官网</a>也逐步成形。</li>
</ul>
          <!--noindex-->
          
            <div class="post-button text-center">
              <a class="btn" href="/2019/05/24/week21/#more" rel="contents">
                阅读全文 &raquo;
              </a>
            </div>
          
          <!--/noindex-->
        
      
    </div>

    

    
    
    

    <div>
  
</div>

<div>
    
</div>


    

    
      
    
    

    

    <footer class="post-footer">
      

      

      

      
      
        <div class="post-eof"></div>
      
    </footer>
  </div>
  
  
  
  </article>


    
      

  

  
  
  

  

  <article class="post post-type-normal" itemscope itemtype="http://schema.org/Article">
  
  
  
  <div class="post-block">
    <link itemprop="mainEntityOfPage" href="https://suenyu.github.io/2019/05/23/houseornot/">

    <span hidden itemprop="author" itemscope itemtype="http://schema.org/Person">
      <meta itemprop="name" content="suen">
      <meta itemprop="description" content>
      <meta itemprop="image" content="/images/avatar.gif">
    </span>

    <span hidden itemprop="publisher" itemscope itemtype="http://schema.org/Organization">
      <meta itemprop="name" content="无余说">
    </span>

    
      <header class="post-header">

        
        
          <h1 class="post-title" itemprop="name headline">
                
                
                <a href="/2019/05/23/houseornot/" class="post-title-link" itemprop="url">选不选书院，是个问题</a>
              
            
          </h1>
        

        <div class="post-meta">
          <span class="post-time">

            
            
            

            
              <span class="post-meta-item-icon">
                <i class="fa fa-calendar-o"></i>
              </span>
              
                <span class="post-meta-item-text">发表于</span>
              

              
                
              

              <time title="创建时间：2019-05-23 10:30:12" itemprop="dateCreated datePublished" datetime="2019-05-23T10:30:12+08:00">2019-05-23</time>
            

            
              

              
                
                <span class="post-meta-divider">|</span>
                

                <span class="post-meta-item-icon">
                  <i class="fa fa-calendar-check-o"></i>
                </span>
                
                  <span class="post-meta-item-text">更新于</span>
                
                <time title="修改时间：2019-05-26 09:00:34" itemprop="dateModified" datetime="2019-05-26T09:00:34+08:00">2019-05-26</time>
              
            
          </span>

          
            <span class="post-category">
            
              <span class="post-meta-divider">|</span>
            
              <span class="post-meta-item-icon">
                <i class="fa fa-folder-o"></i>
              </span>
              
                <span class="post-meta-item-text">分类于</span>
              
              
                <span itemprop="about" itemscope itemtype="http://schema.org/Thing"><a href="/categories/书院/" itemprop="url" rel="index"><span itemprop="name">书院</span></a></span>

                
                
              
            </span>
          

          
            
            
              
              <span class="post-comments-count">
                <span class="post-meta-divider">|</span>
                <span class="post-meta-item-icon">
                  <i class="fa fa-comment-o"></i>
                </span>
            
                <span class="post-meta-item-text">评论数：</span>
                <a href="/2019/05/23/houseornot/#comments" itemprop="discussionUrl">
                  <span class="post-comments-count valine-comment-count" data-xid="/2019/05/23/houseornot/" itemprop="commentCount"></span>
                </a>
              </span>
            
          

          
          
            <span id="/2019/05/23/houseornot/" class="leancloud_visitors" data-flag-title="选不选书院，是个问题">
              <span class="post-meta-divider">|</span>
              <span class="post-meta-item-icon">
                <i class="fa fa-eye"></i>
              </span>
              
                <span class="post-meta-item-text">阅读次数：</span>
              
                <span class="leancloud-visitors-count"></span>
            </span>
          

          

          
            <div class="post-symbolscount">
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-file-word-o"></i>
                </span>
                
                  <span class="post-meta-item-text">本文字数：</span>
                
                <span title="本文字数">421</span>
              

              
                <span class="post-meta-divider">|</span>
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-clock-o"></i>
                </span>
                
                  <span class="post-meta-item-text">阅读时长 &asymp;</span>
                
                <span title="阅读时长">1 分钟</span>
              
            </div>
          

          

        </div>
      </header>
    

    
    
    
    <div class="post-body" itemprop="articleBody">

      
      

      
        
          <font color="red"><strong>本次讨论结果，将直接影响北大附中2019级新生是否有选择进入书院的可能……</strong></font>

<h3 id="在哪里讨论？"><a href="#在哪里讨论？" class="headerlink" title="在哪里讨论？"></a>在哪里讨论？</h3><img src="/images/house001.png" class="[house discuss]" width="1000" height="500">
          <!--noindex-->
          
            <div class="post-button text-center">
              <a class="btn" href="/2019/05/23/houseornot/#more" rel="contents">
                阅读全文 &raquo;
              </a>
            </div>
          
          <!--/noindex-->
        
      
    </div>

    

    
    
    

    <div>
  
</div>

<div>
    
</div>


    

    
      
    
    

    

    <footer class="post-footer">
      

      

      

      
      
        <div class="post-eof"></div>
      
    </footer>
  </div>
  
  
  
  </article>


    
      

  

  
  
  

  

  <article class="post post-type-normal" itemscope itemtype="http://schema.org/Article">
  
  
  
  <div class="post-block">
    <link itemprop="mainEntityOfPage" href="https://suenyu.github.io/2019/05/19/xinzhi/">

    <span hidden itemprop="author" itemscope itemtype="http://schema.org/Person">
      <meta itemprop="name" content="suen">
      <meta itemprop="description" content>
      <meta itemprop="image" content="/images/avatar.gif">
    </span>

    <span hidden itemprop="publisher" itemscope itemtype="http://schema.org/Organization">
      <meta itemprop="name" content="无余说">
    </span>

    
      <header class="post-header">

        
        
          <h1 class="post-title" itemprop="name headline">
                
                
                <a href="/2019/05/19/xinzhi/" class="post-title-link" itemprop="url">心智培训</a>
              
            
          </h1>
        

        <div class="post-meta">
          <span class="post-time">

            
            
            

            
              <span class="post-meta-item-icon">
                <i class="fa fa-calendar-o"></i>
              </span>
              
                <span class="post-meta-item-text">发表于</span>
              

              
                
              

              <time title="创建时间：2019-05-19 08:04:33" itemprop="dateCreated datePublished" datetime="2019-05-19T08:04:33+08:00">2019-05-19</time>
            

            
              

              
                
                <span class="post-meta-divider">|</span>
                

                <span class="post-meta-item-icon">
                  <i class="fa fa-calendar-check-o"></i>
                </span>
                
                  <span class="post-meta-item-text">更新于</span>
                
                <time title="修改时间：2019-05-26 08:59:41" itemprop="dateModified" datetime="2019-05-26T08:59:41+08:00">2019-05-26</time>
              
            
          </span>

          

          
            
            
              
              <span class="post-comments-count">
                <span class="post-meta-divider">|</span>
                <span class="post-meta-item-icon">
                  <i class="fa fa-comment-o"></i>
                </span>
            
                <span class="post-meta-item-text">评论数：</span>
                <a href="/2019/05/19/xinzhi/#comments" itemprop="discussionUrl">
                  <span class="post-comments-count valine-comment-count" data-xid="/2019/05/19/xinzhi/" itemprop="commentCount"></span>
                </a>
              </span>
            
          

          
          
            <span id="/2019/05/19/xinzhi/" class="leancloud_visitors" data-flag-title="心智培训">
              <span class="post-meta-divider">|</span>
              <span class="post-meta-item-icon">
                <i class="fa fa-eye"></i>
              </span>
              
                <span class="post-meta-item-text">阅读次数：</span>
              
                <span class="leancloud-visitors-count"></span>
            </span>
          

          

          
            <div class="post-symbolscount">
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-file-word-o"></i>
                </span>
                
                  <span class="post-meta-item-text">本文字数：</span>
                
                <span title="本文字数">850</span>
              

              
                <span class="post-meta-divider">|</span>
              

              
                <span class="post-meta-item-icon">
                  <i class="fa fa-clock-o"></i>
                </span>
                
                  <span class="post-meta-item-text">阅读时长 &asymp;</span>
                
                <span title="阅读时长">2 分钟</span>
              
            </div>
          

          

        </div>
      </header>
    

    
    
    
    <div class="post-body" itemprop="articleBody">

      
      

      
        
          <h3 id="昔日"><a href="#昔日" class="headerlink" title="昔日"></a>昔日</h3><p>上一次围观心智，都应该至少2年前了。<br>最早参加心智，是2010年5月，校外一个宾馆，北大附中教师团队。<br>总计参加心智应该有5-6次，从成员到观察员，从无知到协助设计方案，程度不一。</p>
<p>2010年学校变革初期，个性化与制度化共舞，学长团的打造几乎与之是绑定的；学长团之外，心智也成为一个出口。<br>初期的体验有公民教育成分，集中在领袖风采的压轴，之后转型，更多温情团建。<br>
          <!--noindex-->
          
            <div class="post-button text-center">
              <a class="btn" href="/2019/05/19/xinzhi/#more" rel="contents">
                阅读全文 &raquo;
              </a>
            </div>
          
          <!--/noindex-->
        
      
    </p></div>

    

    
    
    

    <div>
  
</div>

<div>
    
</div>


    

    
      
    
    

    

    <footer class="post-footer">
      

      

      

      
      
        <div class="post-eof"></div>
      
    </footer>
  </div>
  
  
  
  </article>


    
  </section>

  
  <nav class="pagination">
    <span class="page-number current">1</span><a class="page-number" href="/page/2/">2</a><a class="page-number" href="/page/3/">3</a><a class="extend next" rel="next" href="/page/2/"><i class="fa fa-angle-right" aria-label="下一页"></i></a>
  </nav>



          </div>
          

        </div>
        
          
  
  <div class="sidebar-toggle">
    <div class="sidebar-toggle-line-wrap">
      <span class="sidebar-toggle-line sidebar-toggle-line-first"></span>
      <span class="sidebar-toggle-line sidebar-toggle-line-middle"></span>
      <span class="sidebar-toggle-line sidebar-toggle-line-last"></span>
    </div>
  </div>

  <aside id="sidebar" class="sidebar">
    <div class="sidebar-inner">

      

      

      <div class="site-overview-wrap sidebar-panel sidebar-panel-active">
        <div class="site-overview">
          <div class="site-author motion-element" itemprop="author" itemscope itemtype="http://schema.org/Person">
            
<a href="/">
              <img class="site-author-image" itemprop="image" src="/images/avatar.gif" alt="suen">
</a>
            
              <p class="site-author-name" itemprop="name">suen</p>
              <div class="site-description motion-element" itemprop="description"></div>
          </div>

          
            <nav class="site-state motion-element">
              
                <div class="site-state-item site-state-posts">
                
                  <a href="/archives/">
                
                    <span class="site-state-item-count">21</span>
                    <span class="site-state-item-name">日志</span>
                  </a>
                </div>
              

              
                
                
                <div class="site-state-item site-state-categories">
                  
                    
                      <a href="/categories/">
                    
                  
                    
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                    <span class="site-state-item-count">13</span>
                    <span class="site-state-item-name">分类</span>
                  </a>
                </div>
              

              
                
                
                <div class="site-state-item site-state-tags">
                  
                    
                      <a href="/tags/">
                    
                  
                    
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                      
                    
                    <span class="site-state-item-count">17</span>
                    <span class="site-state-item-name">标签</span>
                  </a>
                </div>
              
            </nav>
          

          
            <div class="feed-link motion-element">
              <a href="/atom.xml" rel="alternate">
                <i class="fa fa-rss"></i>
                RSS
              </a>
            </div>
          

          

          
            <div class="links-of-author motion-element">
              
                <span class="links-of-author-item">
                  
                  
                    
                  
                  
                    
                  
                  <a href="mailto:sunyulei@i.pkuschool.edu.cn" title="E-Mail &rarr; mailto:sunyulei@i.pkuschool.edu.cn" rel="noopener" target="_blank"><i class="fa fa-fw fa-envelope"></i>E-Mail</a>
                </span>
              
            </div>
          

          

          
          

          
            
          
          

        </div>
      </div>

      

      

    </div>
  </aside>
  
    <div id="sidebar-dimmer"></div>
  


        
      </div>
    </main>

    <footer id="footer" class="footer">
      <div class="footer-inner">
        <div class="copyright">&copy; <span itemprop="copyrightYear">2019</span>
  <span class="with-love" id="animate">
    <i class="fa fa-user"></i>
  </span>
  <span class="author" itemprop="copyrightHolder">suen</span>

  
    <span class="post-meta-divider">|</span>
    <span class="post-meta-item-icon">
      <i class="fa fa-area-chart"></i>
    </span>
    
      <span class="post-meta-item-text">站点总字数：</span>
    
    <span title="站点总字数">28k</span>
  

  
    <span class="post-meta-divider">|</span>
    <span class="post-meta-item-icon">
      <i class="fa fa-coffee"></i>
    </span>
    
      <span class="post-meta-item-text">站点阅读时长 &asymp;</span>
    
    <span title="站点阅读时长">1:11</span>
  

</div>
<!--
  <div class="powered-by">由 <a href="https://hexo.io" class="theme-link" rel="noopener" target="_blank">Hexo</a> 强力驱动 v3.8.0</div>
  <span class="post-meta-divider">|</span>
  <div class="theme-info">主题 – <a href="https://theme-next.org" class="theme-link" rel="noopener" target="_blank">NexT.Mist</a> v7.1.2</div>
-->



        








        
      </div>
    </footer>

    
      <div class="back-to-top">
        <i class="fa fa-arrow-up"></i>
        
          <span id="scrollpercent"><span>0</span>%</span>
        
      </div>
    

    

    

    
  </div>

  

<script>
  if (Object.prototype.toString.call(window.Promise) !== '[object Function]') {
    window.Promise = null;
  }
</script>












  















  
  <script src="/lib/jquery/index.js?v=2.1.3"></script>

  
  <script src="/lib/velocity/velocity.min.js?v=1.2.1"></script>

  
  <script src="/lib/velocity/velocity.ui.min.js?v=1.2.1"></script>

  
  <script src="/lib/fancybox/source/jquery.fancybox.pack.js"></script>


  


  <script src="/js/utils.js?v=7.1.2"></script>

  <script src="/js/motion.js?v=7.1.2"></script>



  
  


  <script src="/js/schemes/muse.js?v=7.1.2"></script>




  

  


  <script src="/js/next-boot.js?v=7.1.2"></script>


  
  <script src="/js/js.cookie.js?v=7.1.2"></script>
  <script src="/js/scroll-cookie.js?v=7.1.2"></script>


  

  

  
  

<script src="//cdn1.lncld.net/static/js/3.11.1/av-min.js"></script>



<script src="//unpkg.com/valine/dist/Valine.min.js"></script>

<script>
  var GUEST = ['nick', 'mail', 'link'];
  var guest = 'nick,mail,link';
  guest = guest.split(',').filter(function(item) {
    return GUEST.indexOf(item) > -1;
  });
  new Valine({
    el: '#comments',
    verify: false,
    notify: false,
    appId: 'uzLOlgQFg81pxXmNduFlnwpX-gzGzoHsz',
    appKey: 'se04sYEvYq6g2fHpdeH53GhV',
    placeholder: 'Just go go',
    avatar: 'mm',
    meta: guest,
    pageSize: '10' || 10,
    visitor: true,
    lang: '' || 'zh-cn'
  });
</script>





  
  <script>
    // Popup Window;
    var isfetched = false;
    var isXml = true;
    // Search DB path;
    var search_path = "search.xml";
    if (search_path.length === 0) {
      search_path = "search.xml";
    } else if (/json$/i.test(search_path)) {
      isXml = false;
    }
    var path = "/" + search_path;
    // monitor main search box;
    var onPopupClose = function (e) {
      $('.popup').hide();
      $('#local-search-input').val('');
      $('.search-result-list').remove();
      $('#no-result').remove();
      $(".local-search-pop-overlay").remove();
      $('body').css('overflow', '');
    }
    function proceedsearch() {
      $("body")
        .append('<div class="search-popup-overlay local-search-pop-overlay"></div>')
        .css('overflow', 'hidden');
      $('.search-popup-overlay').click(onPopupClose);
      $('.popup').toggle();
      var $localSearchInput = $('#local-search-input');
      $localSearchInput.attr("autocapitalize", "none");
      $localSearchInput.attr("autocorrect", "off");
      $localSearchInput.focus();
    }
    // search function;
    var searchFunc = function(path, search_id, content_id) {
      'use strict';
      // start loading animation
      $("body")
        .append('<div class="search-popup-overlay local-search-pop-overlay">' +
          '<div id="search-loading-icon">' +
          '<i class="fa fa-spinner fa-pulse fa-5x fa-fw"></i>' +
          '</div>' +
          '</div>')
        .css('overflow', 'hidden');
      $("#search-loading-icon").css('margin', '20% auto 0 auto').css('text-align', 'center');
      
      $.ajax({
        url: path,
        dataType: isXml ? "xml" : "json",
        async: true,
        success: function(res) {
          // get the contents from search data
          isfetched = true;
          $('.popup').detach().appendTo('.header-inner');
          var datas = isXml ? $("entry", res).map(function() {
            return {
              title: $("title", this).text(),
              content: $("content",this).text(),
              url: $("url" , this).text()
            };
          }).get() : res;
          var input = document.getElementById(search_id);
          var resultContent = document.getElementById(content_id);
          var inputEventFunction = function() {
            var searchText = input.value.trim().toLowerCase();
            var keywords = searchText.split(/[\s\-]+/);
            if (keywords.length > 1) {
              keywords.push(searchText);
            }
            var resultItems = [];
            if (searchText.length > 0) {
              // perform local searching
              datas.forEach(function(data) {
                var isMatch = false;
                var hitCount = 0;
                var searchTextCount = 0;
                var title = data.title.trim();
                var titleInLowerCase = title.toLowerCase();
                var content = data.content.trim().replace(/<[^>]+>/g,"");
                
                var contentInLowerCase = content.toLowerCase();
                var articleUrl = decodeURIComponent(data.url).replace(/\/{2,}/g, '/');
                var indexOfTitle = [];
                var indexOfContent = [];
                // only match articles with not empty titles
                if(title != '') {
                  keywords.forEach(function(keyword) {
                    function getIndexByWord(word, text, caseSensitive) {
                      var wordLen = word.length;
                      if (wordLen === 0) {
                        return [];
                      }
                      var startPosition = 0, position = [], index = [];
                      if (!caseSensitive) {
                        text = text.toLowerCase();
                        word = word.toLowerCase();
                      }
                      while ((position = text.indexOf(word, startPosition)) > -1) {
                        index.push({position: position, word: word});
                        startPosition = position + wordLen;
                      }
                      return index;
                    }
                    indexOfTitle = indexOfTitle.concat(getIndexByWord(keyword, titleInLowerCase, false));
                    indexOfContent = indexOfContent.concat(getIndexByWord(keyword, contentInLowerCase, false));
                  });
                  if (indexOfTitle.length > 0 || indexOfContent.length > 0) {
                    isMatch = true;
                    hitCount = indexOfTitle.length + indexOfContent.length;
                  }
                }
                // show search results
                if (isMatch) {
                  // sort index by position of keyword
                  [indexOfTitle, indexOfContent].forEach(function (index) {
                    index.sort(function (itemLeft, itemRight) {
                      if (itemRight.position !== itemLeft.position) {
                        return itemRight.position - itemLeft.position;
                      } else {
                        return itemLeft.word.length - itemRight.word.length;
                      }
                    });
                  });
                  // merge hits into slices
                  function mergeIntoSlice(text, start, end, index) {
                    var item = index[index.length - 1];
                    var position = item.position;
                    var word = item.word;
                    var hits = [];
                    var searchTextCountInSlice = 0;
                    while (position + word.length <= end && index.length != 0) {
                      if (word === searchText) {
                        searchTextCountInSlice++;
                      }
                      hits.push({position: position, length: word.length});
                      var wordEnd = position + word.length;
                      // move to next position of hit
                      index.pop();
                      while (index.length != 0) {
                        item = index[index.length - 1];
                        position = item.position;
                        word = item.word;
                        if (wordEnd > position) {
                          index.pop();
                        } else {
                          break;
                        }
                      }
                    }
                    searchTextCount += searchTextCountInSlice;
                    return {
                      hits: hits,
                      start: start,
                      end: end,
                      searchTextCount: searchTextCountInSlice
                    };
                  }
                  var slicesOfTitle = [];
                  if (indexOfTitle.length != 0) {
                    slicesOfTitle.push(mergeIntoSlice(title, 0, title.length, indexOfTitle));
                  }
                  var slicesOfContent = [];
                  while (indexOfContent.length != 0) {
                    var item = indexOfContent[indexOfContent.length - 1];
                    var position = item.position;
                    var word = item.word;
                    // cut out 100 characters
                    var start = position - 20;
                    var end = position + 80;
                    if(start < 0){
                      start = 0;
                    }
                    if (end < position + word.length) {
                      end = position + word.length;
                    }
                    if(end > content.length){
                      end = content.length;
                    }
                    slicesOfContent.push(mergeIntoSlice(content, start, end, indexOfContent));
                  }
                  // sort slices in content by search text's count and hits' count
                  slicesOfContent.sort(function (sliceLeft, sliceRight) {
                    if (sliceLeft.searchTextCount !== sliceRight.searchTextCount) {
                      return sliceRight.searchTextCount - sliceLeft.searchTextCount;
                    } else if (sliceLeft.hits.length !== sliceRight.hits.length) {
                      return sliceRight.hits.length - sliceLeft.hits.length;
                    } else {
                      return sliceLeft.start - sliceRight.start;
                    }
                  });
                  // select top N slices in content
                  var upperBound = parseInt('1');
                  if (upperBound >= 0) {
                    slicesOfContent = slicesOfContent.slice(0, upperBound);
                  }
                  // highlight title and content
                  function highlightKeyword(text, slice) {
                    var result = '';
                    var prevEnd = slice.start;
                    slice.hits.forEach(function (hit) {
                      result += text.substring(prevEnd, hit.position);
                      var end = hit.position + hit.length;
                      result += '<b class="search-keyword">' + text.substring(hit.position, end) + '</b>';
                      prevEnd = end;
                    });
                    result += text.substring(prevEnd, slice.end);
                    return result;
                  }
                  var resultItem = '';
                  if (slicesOfTitle.length != 0) {
                    resultItem += "<li><a href='" + articleUrl + "' class='search-result-title'>" + highlightKeyword(title, slicesOfTitle[0]) + "</a>";
                  } else {
                    resultItem += "<li><a href='" + articleUrl + "' class='search-result-title'>" + title + "</a>";
                  }
                  slicesOfContent.forEach(function (slice) {
                    resultItem += "<a href='" + articleUrl + "'>" +
                      "<p class=\"search-result\">" + highlightKeyword(content, slice) +
                      "...</p>" + "</a>";
                  });
                  resultItem += "</li>";
                  resultItems.push({
                    item: resultItem,
                    searchTextCount: searchTextCount,
                    hitCount: hitCount,
                    id: resultItems.length
                  });
                }
              })
            };
            if (keywords.length === 1 && keywords[0] === "") {
              resultContent.innerHTML = '<div id="no-result"><i class="fa fa-search fa-5x"></i></div>'
            } else if (resultItems.length === 0) {
              resultContent.innerHTML = '<div id="no-result"><i class="fa fa-frown-o fa-5x"></i></div>'
            } else {
              resultItems.sort(function (resultLeft, resultRight) {
                if (resultLeft.searchTextCount !== resultRight.searchTextCount) {
                  return resultRight.searchTextCount - resultLeft.searchTextCount;
                } else if (resultLeft.hitCount !== resultRight.hitCount) {
                  return resultRight.hitCount - resultLeft.hitCount;
                } else {
                  return resultRight.id - resultLeft.id;
                }
              });
              var searchResultList = '<ul class=\"search-result-list\">';
              resultItems.forEach(function (result) {
                searchResultList += result.item;
              })
              searchResultList += "</ul>";
              resultContent.innerHTML = searchResultList;
            }
          }
          if ('auto' === 'auto') {
            input.addEventListener('input', inputEventFunction);
          } else {
            $('.search-icon').click(inputEventFunction);
            input.addEventListener('keypress', function (event) {
              if (event.keyCode === 13) {
                inputEventFunction();
              }
            });
          }
          // remove loading animation
          $(".local-search-pop-overlay").remove();
          $('body').css('overflow', '');
          proceedsearch();
        }
      });
    }
    // handle and trigger popup window;
    $('.popup-trigger').click(function(e) {
      e.stopPropagation();
      if (isfetched === false) {
        searchFunc(path, 'local-search-input', 'local-search-result');
      } else {
        proceedsearch();
      };
    });
    $('.popup-btn-close').click(onPopupClose);
    $('.popup').click(function(e){
      e.stopPropagation();
    });
    $(document).on('keyup', function (event) {
      var shouldDismissSearchPopup = event.which === 27 &&
        $('.search-popup').is(':visible');
      if (shouldDismissSearchPopup) {
        onPopupClose();
      }
    });
  </script>





  

  

  

  

  

  
  <script>
    (function(){
      var bp = document.createElement('script');
      var curProtocol = window.location.protocol.split(':')[0];
      bp.src = (curProtocol === 'https') ? 'https://zz.bdstatic.com/linksubmit/push.js' : 'http://push.zhanzhang.baidu.com/push.js';
      var s = document.getElementsByTagName("script")[0];
      s.parentNode.insertBefore(bp, s);
    })();
  </script>


  

  

  

  

  

  
<script>
  $('.highlight').not('.gist .highlight').each(function(i, e) {
    var $wrap = $('<div>').addClass('highlight-wrap');
    $(e).after($wrap);
    $wrap.append($('<button>').addClass('copy-btn').append('复制').on('click', function(e) {
      var code = $(this).parent().find('.code').find('.line').map(function(i, e) {
        return $(e).text();
      }).toArray().join('\n');
      var ta = document.createElement('textarea');
      var yPosition = window.pageYOffset || document.documentElement.scrollTop;
      ta.style.top = yPosition + 'px'; // Prevent page scroll
      ta.style.position = 'absolute';
      ta.style.opacity = '0';
      ta.readOnly = true;
      ta.value = code;
      document.body.appendChild(ta);
      ta.select();
      ta.setSelectionRange(0, code.length);
      ta.readOnly = false;
      var result = document.execCommand('copy');
      
        if (result) $(this).text('复制成功');
        else $(this).text('复制失败');
      
      ta.blur(); // For iOS
      $(this).blur();
    })).on('mouseleave', function(e) {
      var $b = $(this).find('.copy-btn');
      setTimeout(function() {
        $b.text('复制');
      }, 300);
    }).append(e);
  })
</script>


  

  

</body>
</html>
© 2019 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
