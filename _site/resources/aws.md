<!DOCTYPE html>
<html lang="en">
<!-- Beautiful Jekyll 6.0.1 | Copyright Dean Attali 2023 -->
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

  

  

  <title>AWS</title>

  
  
  <meta name="author" content="© 2023 핀옵스 한국 커뮤니티">
  

  <meta name="description" content="# AWS - [AWS Cost Optimization](#AWS-Cost-Optimization-Recommendations) - [AWS Cloud Financial Management](#aws-cloud-financial-management) - [AWS FinOps Video](#aws-finops-video) - [AWS Blogs](#aws-blogs) - [Article](#article) - [Hands-On](#hands-on) - [AWS SkillBuilder](#aws-skillbuilder) - [AWS FinOps Tools](#aws-finops-tools) ## AWS Cost Optimization Recommendations - [비용 최적화 시리즈 1부: AWS 사용량에 대한 시각화로 비용 최적화 인사이트 얻기](https://aws.amazon.com/ko/blogs/korea/visualize-and-gain-insights-into-your-aws-cost-and-usage-with-amazon-managed-grafana/) - [비용 최적화...">

  

  
  <meta name="keywords" content="finops,aws,gcp,cloud,cost,cost optimization">
  

  
  <link rel="alternate" type="application/rss+xml" title="FinOps Korea" href="http://localhost:4000/feed.xml">
  

  

  

  

  


  
    
      
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">


    
      
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.12.1/css/all.min.css">


    
      
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lora:400,700,400italic,700italic">


    
      
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open+Sans:300italic,400italic,600italic,700italic,800italic,400,300,600,700,800">


    
  

  
    
      <link rel="stylesheet" href="/assets/css/bootstrap-social.css">
    
      <link rel="stylesheet" href="/assets/css/beautifuljekyll.css">
    
  

  

  
  
  

  

  
  <meta property="og:site_name" content="FinOps Korea">
  <meta property="og:title" content="AWS">
  <meta property="og:description" content="# AWS - [AWS Cost Optimization](#AWS-Cost-Optimization-Recommendations) - [AWS Cloud Financial Management](#aws-cloud-financial-management) - [AWS FinOps Video](#aws-finops-video) - [AWS Blogs](#aws-blogs) - [Article](#article) - [Hands-On](#hands-on) - [AWS SkillBuilder](#aws-skillbuilder) - [AWS FinOps Tools](#aws-finops-tools) ## AWS Cost Optimization Recommendations - [비용 최적화 시리즈 1부: AWS 사용량에 대한 시각화로 비용 최적화 인사이트 얻기](https://aws.amazon.com/ko/blogs/korea/visualize-and-gain-insights-into-your-aws-cost-and-usage-with-amazon-managed-grafana/) - [비용 최적화...">

  
  <meta property="og:image" content="http://localhost:4000/assets/img/finops_foundation_logo.jpeg">
  

  
  <meta property="og:type" content="website">
  <meta property="og:url" content="http://localhost:4000/resources/aws.md">
  <link rel="canonical" href="http://localhost:4000/resources/aws.md">
  

  
  <meta name="twitter:card" content="summary">
  
  <meta name="twitter:site" content="@">
  <meta name="twitter:creator" content="@">

  <meta property="twitter:title" content="AWS">
  <meta property="twitter:description" content="# AWS - [AWS Cost Optimization](#AWS-Cost-Optimization-Recommendations) - [AWS Cloud Financial Management](#aws-cloud-financial-management) - [AWS FinOps Video](#aws-finops-video) - [AWS Blogs](#aws-blogs) - [Article](#article) - [Hands-On](#hands-on) - [AWS SkillBuilder](#aws-skillbuilder) - [AWS FinOps Tools](#aws-finops-tools) ## AWS Cost Optimization Recommendations - [비용 최적화 시리즈 1부: AWS 사용량에 대한 시각화로 비용 최적화 인사이트 얻기](https://aws.amazon.com/ko/blogs/korea/visualize-and-gain-insights-into-your-aws-cost-and-usage-with-amazon-managed-grafana/) - [비용 최적화...">

  
  <meta name="twitter:image" content="http://localhost:4000/assets/img/finops_foundation_logo.jpeg">
  

  


  

  

</head>


<body>
  


  <nav class="navbar navbar-expand-xl navbar-light fixed-top navbar-custom top-nav-regular"><a class="navbar-brand" href="http://localhost:4000/">FinOps Korea</a><button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#main-navbar" aria-controls="main-navbar" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="main-navbar">
    <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="/aboutus">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/notice">NOTICE</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/codeofconduct">Code of Conduct</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Resources</a>
            <div class="dropdown-menu dropdown-menu-right" aria-labelledby="navbarDropdown">
                  <a class="dropdown-item" href="/finops">FinOps</a>
                  <a class="dropdown-item" href="/aws">AWS</a>
                  <a class="dropdown-item" href="/gcp">GCP</a>
                  <a class="dropdown-item" href="/azure">Azure</a>
                  <a class="dropdown-item" href="/ncloud">NCLOUD</a>
            </div>
          </li>
        
          <li class="nav-item">
            <a class="nav-link" href="https://www.finops.org/">FinOps Foundation</a>
          </li>
        <li class="nav-item">
          <a class="nav-link" id="nav-search-link" href="#" title="Search">
            <span id="nav-search-icon" class="fa fa-search"></span>
            <span id="nav-search-text">Search</span>
          </a>
        </li></ul>
  </div>

  

  
    <div class="avatar-container">
      <div class="avatar-img-border">
        <a href="http://localhost:4000/">
          <img alt="Navigation bar avatar" class="avatar-img" src="/assets/img/finops_foundation_logo.jpeg" />
        </a>
      </div>
    </div>
  

</nav>



<div id="beautifuljekyll-search-overlay">

  <div id="nav-search-exit" title="Exit search">✕</div>
  <input type="text" id="nav-search-input" placeholder="Search">
  <ul id="search-results-container"></ul>
  
  <script src="https://unpkg.com/simple-jekyll-search@latest/dest/simple-jekyll-search.min.js"></script>
  <script>
    var searchjson = '[ \
       \
        { \
          "title"    : "FinOps 란 무엇인가?", \
          "desc"     : "FinOps 란 무엇인가?", \
          "category" : "Finops", \
          "url"      : "/2023-12-22-whats_the_finops/", \
          "date"     : "December 22, 2023" \
        }, \
       \
       \
        { \
          "title"    : "About US", \
          "desc"     : "About US", \
          "category" : "page", \
          "url"      : "/aboutus/", \
          "date"     : "January 1, 1970" \
        }, \
       \
        { \
          "title"    : "Azure", \
          "desc"     : "Azure", \
          "category" : "page", \
          "url"      : "/resources/azure/", \
          "date"     : "January 1, 1970" \
        }, \
       \
        { \
          "title"    : "Code of Conduct", \
          "desc"     : "Code of Conduct", \
          "category" : "page", \
          "url"      : "/codeofconduct/", \
          "date"     : "January 1, 1970" \
        }, \
       \
        { \
          "title"    : "FinOps", \
          "desc"     : "FinOps", \
          "category" : "page", \
          "url"      : "/resources/finops/", \
          "date"     : "January 1, 1970" \
        }, \
       \
        { \
          "title"    : "GCP", \
          "desc"     : "GCP", \
          "category" : "page", \
          "url"      : "/resources/gcp/", \
          "date"     : "January 1, 1970" \
        }, \
       \
        { \
          "title"    : "FinOps Korea Community", \
          "desc"     : "FinOps Korea Community", \
          "category" : "page", \
          "url"      : "/", \
          "date"     : "January 1, 1970" \
        }, \
       \
        { \
          "title"    : "Ncloud", \
          "desc"     : "Ncloud", \
          "category" : "page", \
          "url"      : "/resources/ncloud/", \
          "date"     : "January 1, 1970" \
        }, \
       \
        { \
          "title"    : "Notice", \
          "desc"     : "Notice", \
          "category" : "page", \
          "url"      : "/notice/", \
          "date"     : "January 1, 1970" \
        }, \
       \
        { \
          "title"    : "Tag Index", \
          "desc"     : "Tag Index", \
          "category" : "page", \
          "url"      : "/tags/", \
          "date"     : "January 1, 1970" \
        } \
       \
    ]';
    searchjson = JSON.parse(searchjson);

    var sjs = SimpleJekyllSearch({
      searchInput: document.getElementById('nav-search-input'),
      resultsContainer: document.getElementById('search-results-container'),
      json: searchjson
    });
  </script>
</div>





  



<header class="header-section ">
<div class="intro-header ">
  
  <div class="container-md">
    <div class="row">
      <div class="col-xl-8 offset-xl-2 col-lg-10 offset-lg-1">
        <div class="page-heading">
          <h1>AWS</h1>
          
          
          
        </div>
      </div>
    </div>
  </div>
  
  
</div>



</header>


<main class=" container-md ">
  <div class="row">
    <div class=" col-xl-8 offset-xl-2 col-lg-10 offset-lg-1 ">
      

      <h1 id="aws">AWS</h1>
<ul>
  <li><a href="#AWS-Cost-Optimization-Recommendations">AWS Cost Optimization</a></li>
  <li><a href="#aws-cloud-financial-management">AWS Cloud Financial Management</a></li>
  <li><a href="#aws-finops-video">AWS FinOps Video</a></li>
  <li><a href="#aws-blogs">AWS Blogs</a></li>
  <li><a href="#article">Article</a></li>
  <li><a href="#hands-on">Hands-On</a></li>
  <li><a href="#aws-skillbuilder">AWS SkillBuilder</a></li>
  <li><a href="#aws-finops-tools">AWS FinOps Tools</a></li>
</ul>

<h2 id="aws-cost-optimization-recommendations">AWS Cost Optimization Recommendations</h2>
<ul>
  <li><a href="https://aws.amazon.com/ko/blogs/korea/visualize-and-gain-insights-into-your-aws-cost-and-usage-with-amazon-managed-grafana/">비용 최적화 시리즈 1부: AWS 사용량에 대한 시각화로 비용 최적화 인사이트 얻기</a></li>
  <li><a href="https://aws.amazon.com/ko/blogs/korea/cost-optimization-recommendations-for-aws-config/">비용 최적화 시리즈 2부: AWS Config의 비용 최적화 방안</a></li>
</ul>

<h2 id="aws-cloud-financial-management">AWS Cloud Financial Management</h2>
<ul>
  <li><a href="https://aws.amazon.com/ko/blogs/aws-cloud-financial-management/">AWS Cloud Financial Management</a></li>
</ul>

<h2 id="aws-finops-video">AWS FinOps Video</h2>
<ul>
  <li><a href="https://www.youtube.com/playlist?list=PLkMxFWEx0j2OA-qi5kMMqfIEdCXd-l-Os">AWS 비용 관련 유튜브 재생목록</a></li>
  <li><a href="https://www.youtube.com/watch?v=xOQzhagC9hA&amp;list=PLkMxFWEx0j2N8gV3rmoevDKKU5F0OW5eK">AWS re:Invent 2022 비용 관련 유튜브 재생목록</a></li>
</ul>

<h2 id="aws-blogs">AWS Blogs</h2>
<ul>
  <li><a href="https://aws.amazon.com/ko/blogs/tech/optimizing-your-kubernetes-compute-costs-with-karpenter-consolidation/">Karpenter 통합을 이용한 Kubernetes 컴퓨팅 비용 최적화</a></li>
  <li><a href="https://aws.amazon.com/ko/blogs/tech/amazon-eks-cluster-auto-scaling-karpenter-bp">Amazon EKS 클러스터를 비용 효율적으로 오토스케일링하기</a></li>
  <li><a href="https://aws.amazon.com/ko/blogs/korea/amazon-redshift-continues-its-price-performance-leadership">Amazon Redshift의 가격 대비 성능 리더쉽</a></li>
  <li><a href="https://aws.amazon.com/ko/blogs/korea/aws-well-architected-framework-aws-trusted-advisor-cost-optimization/">AWS Well-Architected 프레임워크와 AWS Trusted Advisor 를 사용한 데이터 기반의 비용 최적화 리뷰</a></li>
  <li><a href="https://aws.amazon.com/ko/blogs/korea/introducing-aws-resource-explorer-quickly-find-resources-in-your-aws-account/">AWS Resource Explorer 소개 — 모든 AWS 리소스 한번에 빠르게 검색하기</a></li>
  <li><a href="https://aws.amazon.com/ko/blogs/korea/new-amazon-cloudwatch-cross-account-observability/">Amazon CloudWatch 계정간 관찰 가능성 기능 출시</a></li>
  <li><a href="https://aws.amazon.com/ko/blogs/korea/overview-of-data-transfer-costs-for-common-architectures/">AWS 범용 클라우드 아키텍처의 데이터 전송 비용 알아보기</a></li>
  <li><a href="https://aws.amazon.com/ko/blogs/korea/exploring-data-transfer-costs-for-aws-managed-databases/">AWS 관리형 데이터베이스 서비스 전송 비용 알아보기</a></li>
  <li><a href="https://aws.amazon.com/ko/blogs/korea/new-for-aws-compute-optimizer-resource-efficiency-metrics-to-estimate-savings-opportunities-and-performance-risks/">AWS Compute Optimizer 신규 기능 — 비용 절감 기회와 성능 위험을 예측하는 리소스 효율성 지표</a></li>
  <li><a href="https://aws.amazon.com/ko/blogs/korea/introducing-tiered-pricing-for-aws-lambda/">AWS Lambda 계층형 신규 요금제 출시</a></li>
  <li><a href="https://aws.amazon.com/ko/blogs/korea/graviton-fast-start-a-new-program-to-help-move-your-workloads-to-aws-graviton/">AWS Graviton Fast Start – 그라비톤 기반 완전 관리 서비스 이전 지원 프로그램</a></li>
  <li><a href="https://aws.amazon.com/ko/blogs/korea/10-things-you-can-do-today-to-reduce-aws-costs/">AWS 비용을 줄일 수 있는 10가지 기법</a></li>
  <li><a href="https://aws.amazon.com/ko/blogs/korea/new-for-aws-compute-optimizer-resource-efficiency-metrics-to-estimate-savings-opportunities-and-performance-risks/">AWS Compute Optimizer</a></li>
</ul>

<h2 id="article">Article</h2>
<ul>
  <li><a href="https://hyperconnect.github.io/2023/07/25/migrate-half-of-workload-in-a-year.html">1년 동안 Workload의 절반을 ARM64로 Migration하기</a></li>
  <li><a href="https://gnidoc.tistory.com/entry/%EC%88%98%EC%A0%9C-FinOps-Lambda%ED%8E%B8">수제 FinOps - Lambda편</a></li>
  <li><a href="https://gnidoc.tistory.com/entry/%EC%88%98%EC%A0%9C-FinOps-NAT%ED%8E%B8">수제 FinOps - NAT편</a></li>
  <li><a href="https://zigispace.net/1193">Telegram Bot으로 AWS 비용 확인하기</a></li>
  <li><a href="https://linuxer.name/2022/08/aws-finops-s3-incomplete-multipart-uploads-mpu/">불완전한 멀티파트 업로드 제거로 비용 절검</a></li>
  <li><a href="https://flavono123.github.io/posts/s3-cost-optimization/">AWS S3 불필요한 객체 삭제로 비용 절감하기</a></li>
  <li><a href="https://newstars.cloud/489">AWS Cli로 오래된 s3 객체 삭제하기</a></li>
  <li><a href="https://velog.io/@sean-2016/DevOps-Engineer%EA%B0%80-FinOps%EB%A5%BC-%EC%8B%9C%EC%9E%91%ED%95%98%EB%A9%B4">DevOps Engineer가 FinOps를 시작하면</a></li>
  <li><a href="https://theburningmonk.com/2022/07/the-best-ways-to-save-money-on-lambda/">The best ways to save money on Lambda</a></li>
  <li><a href="https://engineering.ab180.co/stories/aws-ecs-task-rebalancing-ec2-cost-optimization">ECS Task Rebalancing을 이용한 EC2 비용 최적화</a></li>
  <li><a href="https://medium.com/@NickHystax/13-hidden-aws-charges-and-how-to-avoid-them-79b94a328e62">13 hidden AWS charges and how to avoid them</a></li>
  <li><a href="https://www.linkedin.com/pulse/how-manage-your-aws-resources-effectively-tags-aleksandar-nenov/">How to Manage Your AWS Resources Effectively with Tags</a></li>
</ul>

<h2 id="hands-on">Hands-On</h2>
<ul>
  <li><a href="https://catalog.workshops.aws/eks-cost-optimization/ko-KR">Amazon EKS 비용 최적화 워크샵</a></li>
  <li><a href="https://catalog.workshops.aws/awscff/en-US">Cloud Financial Framework (CFF)</a></li>
  <li><a href="https://github.com/chris-bowman/Azure-Cost-Reporting/tree/main/Power%20BI%20Report">Azure-Cost-Reporing</a></li>
  <li><a href="https://wellarchitectedlabs.com/cost/100_labs/100_5_cost_visualization/">AWS Level 100 : COST VISUALIZATION</a></li>
  <li><a href="https://wellarchitectedlabs.com/cost/200_labs/200_cloud_intelligence/">AWS Level 200 : Cloud Intelligence Dashboards</a></li>
  <li><a href="https://wellarchitectedlabs.com/cost/200_labs/200_cloud_intelligence/compute-optimizer-dashboards/">AWS Level 200 : COMPUTE OPTIMIZER DASHBOARD</a></li>
</ul>

<h2 id="aws-skillbuilder">AWS SkillBuilder</h2>
<ul>
  <li><a href="https://explore.skillbuilder.aws/learn/course/external/view/elearning/13231/optimizing-your-finops-strategy-with-aws">Optimizing your FinOps Strategy with AWS</a></li>
</ul>

<h2 id="aws-finops-tools">AWS FinOps Tools</h2>
<ul>
  <li><a href="https://calculator.aws/">AWS 비용 계산기</a></li>
  <li><a href="https://instances.vantage.sh/">EC2기반 리소스 비용 비교하기</a></li>
  <li><a href="https://calculator.s3.amazonaws.com/index.html">AWS 한달 비용 계산기</a></li>
  <li><a href="https://github.com/alexcasalboni/aws-lambda-power-tuning">AWS Lambda Power tuning</a></li>
  <li><a href="https://github.com/aws-samples/hpc-cost-simulator">Hpc-Cost-Simulator</a></li>
</ul>


      

      

    </div>
  </div>
</main>


  <footer>
  <div class="container-md beautiful-jekyll-footer">
    <div class="row">
      <div class="col-xl-8 offset-xl-2 col-lg-10 offset-lg-1">
      
<ul class="list-inline text-center footer-links"><li class="list-inline-item">
    <a href="mailto:FinOpsKR@gmail.com" title="Email me">
      <span class="fa-stack fa-lg" aria-hidden="true">
        <i class="fas fa-circle fa-stack-2x"></i>
        <i class="fas fa-envelope fa-stack-1x fa-inverse"></i>
      </span>
      <span class="sr-only">Email me</span>
   </a>
  </li><li class="list-inline-item">
    <a href="https://github.com/FinOpsKR" title="GitHub">
      <span class="fa-stack fa-lg" aria-hidden="true">
        <i class="fas fa-circle fa-stack-2x"></i>
        <i class="fab fa-github fa-stack-1x fa-inverse"></i>
      </span>
      <span class="sr-only">GitHub</span>
   </a>
  </li></ul>

      
      <p class="copyright text-muted">
      
        © 2023 핀옵스 한국 커뮤니티
        &nbsp;&bull;&nbsp;
      
      2023

      
        &nbsp;&bull;&nbsp;
        <span class="author-site">
          <a href="http://localhost:4000/">FinOps.kr</a>
        </span>
      

      

      

      </p>
      <p class="theme-by text-muted">
        Powered by
        <a href="https://beautifuljekyll.com">Beautiful Jekyll</a>
      </p>
      <p style="text-align:center;">
        <a href="https://hits.seeyoufarm.com" class="text_muted"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FFinOpsKR%2Fhit-counter&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false"/></a>
      </p>

      </div>
    </div>
  </div>
</footer>


  
  
    
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha256-4+XzXVhsDmqanXGHaHvgh1gMQKX40OUvDEBTu8JcmNs=" crossorigin="anonymous"></script>


  
    
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>


  
    
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>


  



  
    <!-- doing something a bit funky here because I want to be careful not to include JQuery twice! -->
    
      <script src="/assets/js/beautifuljekyll.js"></script>
    
  









</body>
</html>
