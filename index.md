<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en">
<!-- Sidebar/menu -->
<nav class="w3-sidebar w3-bar-block w3-black w3-collapse w3-top w3-right" style="z-index:3;width:150px" id="mySidebar">
  <div class="w3-container w3-display-container w3-padding-16">
    <h3><b>Jianhui Jin</b></h3>
  </div>
  <div>
    <a href="#home">Home</a>
    <a href="#news">News</a>
    <a href="#projects">Projects</a>
    <a href="#talks">Talks</a>
    <a href="#publications">Research</a>
    <a href="#service">Services</a>
    <a href="#award">Awards</a>
  </div>
</nav>

<!-- Top menu on small screens -->
<header class="w3-bar w3-top w3-hide-large w3-black w3-xlarge">
  <div class="w3-bar-item w3-padding-24">Jianhui Jin</div>
  <a href="javascript:void(0)" class="w3-bar-item w3-button w3-padding-24 w3-right"  style="font-stretch: extra-expanded;" onclick="w3_open()"><b>≡</b></a>
  </div>
</header>

<!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-hide-large" onclick="w3_close()" style="cursor:pointer" title="close side menu" id="myOverlay"></div>

<!-- !PAGE CONTENT! -->
<div class="w3-main" style="margin-left:150px">

  <!-- Push down content on small screens -->
  <div class="w3-hide-large" style="margin-top:83px"></div>

<!-- The Home Section -->
    <div class="w3-container w3-center w3-padding-32" id="home">
      <img style="width: 80%;max-width: 320px" alt="profile photo" src="images/Yunhe_new.jpg">
      <h1>Jianhui Jin</h1>
        <p class="w3-justify" style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;max-width:600px">
          I am a senior researcher at <a href="https://www.noahlab.com.hk/">Huawei Noah's Ark Lab</a>, Beijing, where I work on deep learning, model compression, and computer vision, etc. Before that, I did my PhD at school of EECS, <a href="https://www.pku.edu.cn/">Peking University</a>, where I was co-advised by Prof. <a href="https://dblp.org/pers/hd/x/Xu_0006:Chao">Chao Xu</a></a> and Prof. <a href="https://scholar.google.com.sg/citations?user=RwlJNLcAAAAJ">Dacheng Tao</a></a>. I did my bachelors at school of science, <a href="https://en.xidian.edu.cn/">Xidian University</a>.
        </p>
        <p class="w3-center">
          <a href="mailto:jinjianhui666@163.com">Email</a>
          <a href="https://scholar.google.com/citations?user=E9ddt6QAAAAJ">Google Scholar</a>
          <a href="https://www.zhihu.com/people/jin-jian-hui-26-47"> Zhi Hu </a>
          <a href="https://dblp.org/pid/312/4047"> DBLP </a>
        </p>
  </div>

<!-- The News Section -->
  <div class="w3-container w3-light-grey w3-padding-32" id="news">
   <h2>News</h2>
   	  <p><li> 03/2022, Our suvery paper on remote sensings image has been accepted by <a href="https://ieeexplore.ieee.org/abstract/document/9735276">IEEE JSTSP</a>.</li></p>
      <p><li> 07/2021, 1 paper has been accepted by <a href="https://ieeexplore.ieee.org/abstract/document/9538389">IEEE TGRS</a>.</li></p>
  </div>
<!-- The Projects Section -->
  <div class="w3-container w3-padding-32" id="projects">
    <h2>Recent Projects</h2>
    <p class="w3-justify">
        Actually, model compression is a kind of technique for developing portable deep neural networks with lower memory and computation costs. I have done several projects in Huawei including some smartphones' applications in 2019 and 2020 (e.g. Mate 30 and Honor V30). Currently, I am leading the AdderNet project, which aims to develop a series of deep learning models using only additions (<a href="https://www.reddit.com/r/MachineLearning/comments/ekw2s1/r_addernet_do_we_really_need_multiplications_in/">Discussions on Reddit</a>).
    </p>

        <h4><li>Adder Neural Networks</li></h4>
        <img style="width:96%;" src="images/AdderNet.jpg"> 
        <p class="w3-justify">
        <a style="color: #447ec9" href="https://github.com/huawei-noah/AdderNet">Project Page</a> | <a style="color: #447ec9" href="https://arxiv.org/pdf/2101.10015.pdf">Hardware Implementation</a>
        </p>
        <p class="w3-justify">
        I would like to say, <span style="color:red">AdderNet is very cool!</span> The initial idea was came up in about 2017 when climbing with some friends at Beijing. By replacing all convolutional layers (except the first and the last layers), we now can obtain comparable performance on ResNet architectures. In addition, to make the story more complete, we recent release the hardware implementation and some quantization methods. The results are quite encouraging, we can reduce both <strong>the energy consumption and thecircuit areas significantly without affecting the performance</strong>. Now, we are working on more applications to reduce the costs of launching AI algorithms such as low-level vision, detection, and NLP tasks.
        </p> 

        <h4><li>GhostNet on MindSpore: SOTA Lightweight CV Networks</li></h4>
        <img style="width:96%;" src="images/GhostNet.png"> 
        <p class="w3-justify">
        <a style="color: #447ec9" href="https://live.huawei.com/huaweiconnect/meeting/cn/5872.html">Huawei Connect (HC) 2020</a> | <a style="color: #447ec9" href="https://www.mindspore.cn/resources/hub">MindSpore Hub</a>
        </p>
        <p class="w3-justify">
        The initial verison of GhostNet was accepted by CVPR 2020, which achieved SOTA performance on ImageNet: <span style="color:red">75.7%</span> top1 acc with only <span style="color:red">226M FLOPS</span>. In the current version, we release a series computer vision models (e.g. int8 quantization, detection, and larger networks) on <strong>MindsSpore 1.0</strong> and <strong>Mate 30 Pro (Kirin 990)</strong>.
        </p> 

        <h4><li>AI on Ascend: Real-Time Video Style Transfer</li></h4>
        <img style="width:32%;" src="images/atlas200.png"> &nbsp&nbsp <img style="width:60%;" src="images/video.gif">
        <p class="w3-justify">
        <a style="color: #447ec9" href="https://www.huaweicloud.com/intl/en-us/HDC.Cloud.html">Huawei Developer Conference (HDC) 2020</a> | <a style="color: #447ec9" href="https://developer.huaweicloud.com/exhibition/Atlas_neural_style.html">Online Demo</a>
        </p>
        <p class="w3-justify">
        This project aims to develop a video style transfer system on the <strong>Huawei Atlas 200 DK AI developer Kit</strong>. The latency of the original model for processing one image is about <span style="color:red">630ms</span>. After accelerating it using our method, the lantency now is about <span style="color:red">40ms</span>. 
        </p>  

  </div>
  
  <!-- The Talks Section -->
  <div class="w3-container w3-light-grey w3-padding-32" id="talks">
    <h2>Talks</h2>
      <p><li> 10/2021, Vision Transformer at <a href="https://haet2021.github.io/speakers.html">HAET ICLR 2021 workshop</a>.</li></p>
	  <p><li> 05/2021, Adder Neural Network at <a href="https://haet2021.github.io/speakers.html">HAET ICLR 2021 workshop</a>. Thanks <a href="https://datawisdom.ca/">Vahid</a> for the invitation.</li></p>
      <p><li> 06/2020, "<a href="http://valser.org/webinar/slide/slides/20200603/%E6%A8%A1%E5%9E%8B%E5%8E%8B%E7%BC%A9-%E5%B7%A5%E4%B8%9A%E7%95%8C%E5%92%8C%E5%AD%A6%E6%9C%AF%E7%95%8C%E7%9A%84%E5%B7%AE%E5%BC%82.pdf">AI on the Edge - Discussion on the Gap Between Industry and Academia</a>" at <a  href="http://valser.org/"><strong>VALSE</strong></a> Webinar.</li></p>
      <p><li> 05/2020, "<a href="https://www.bilibili.com/video/av925692420/">Edge AI: Progress and Future Directions</a>" at <a href="https://www.qbitai.com/"> <strong>QbitAI</strong></a> using <a  href="https://www.bilibili.com/"><strong>bilibili</strong></a>.</li></p>
  </div>
 <!-- The Publications Section -->
  <div class="w3-container w3-padding-32"" id="publications">
    <h2>Research</h2>
      <p class="w3-left-align" style="line-height:200%">
        I'm interested in devleoping <strong>efficient models</strong> for computer vision (e.g. classification, detection, and super-resolution) using pruning, quantization, distilaltion, NAS, etc.
      </p>
    
      <h4> Journal Papers:</h4>

      <ol>

      <p>
      <li><strong>CIMFNet: Cross-layer Interaction and Multiscale Fusion Network for Semantic Segmentation of High-Resolution Remote Sensing Images</strong>
      <br>
      Wujie Zhou, <strong>Jianhui Jin</strong>, Jingsheng Lei, Lu Yu
      <br>
      <em>IEEE JSTSP</em> 2022 | <a style="color: #447ec9" href="https://ieeexplore.ieee.org/abstract/document/9735276">paper</a> 
      </p>

      <p>
      <li><strong>CEGFNet: Common extraction and gate fusion network for scene parsing of remote sensing images</strong>
      <br>
      Wujie Zhou*, <strong>Jianhui Jin</strong>*, Jingsheng Lei, Jenq-Neng Hwang
      <br>
      <em>IEEE TGRS</em> 2021 (* equal contribution) | <a style="color: #447ec9" href="https://ieeexplore.ieee.org/abstract/document/9538389">paper</a> | <a style="color: #447ec9" href="https://github.com/NIT-JJH/CEGFNet">code</a>
      </p>
      </ol>
    </p>
  </div>

<!-- The Services Section -->
  <div class="w3-container w3-light-grey w3-padding-32" id="service">
    <h2>Services</h2>
      <p><li> Area Chair of <a href="https://icml.cc/Conferences/2021">ICML 2021</a>, <a href="https://nips.cc/Conferences/2021/">NeurIPS 2021</a>.</p>
      <p><li> Senior Program Committee Members of <a href="https://ijcai-21.org/">IJCAI 2021</a>, <a href="https://www.ijcai20.org/">IJCAI 2020</a> and <a href="https://www.ijcai19.org/program-committee.html">IJCAI 2019</a>.</p>
      <p><li> Journal Reviewers of <a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=34">IEEE T-PAMI</a>, <a href="https://www.springer.com/journal/11263">IJCV</a>, <a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=83">IEEE T-IP</a>, <a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=5962385">IEEE T-NNLS</a>, <a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6046">IEEE T-MM</a>, <a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=69">IEEE T-KDE</a>, etc.</p>
      <p><li> Program Committee Members of ICCV 2021, AAAI 2021, ICLR 2021, NeurIPS 2020, ICML 2020, ECCV 2020, CVPR 2020, ICLR 2020, AAAI 2020, ICCV 2019, CVPR 2019, ICLR 2019, AAAI 2019, IJCAI 2018, AAAI 2018, NeurIPS 2018, etc.</p>
  </div>

  <!-- The Awards Section -->
  <div class="w3-container w3-padding-32" id="award">
    <h2>Awards</h2>
    <p><li> 2020, <a href="https://mp.weixin.qq.com/s/dORL01lgFNDHgjp3KMJmiQ">Nomination for Outstanding Youth Paper Award</a>, <a href="https://worldaic.com.cn/portal/en/aboutus.html">WAIC</a></p>               
    <p><li> 2017, <a href="https://research.google/outreach/phd-fellowship/recipients/?category=2017">Google PhD Fellowship</a></p>
    <p><li> 2017, <a href="http://scholarship.baidu.com/">Baidu Scholarship</a></p>
    <p><li> 2017, President's PhD Scholarship, Peking University</p>
    <p><li> 2017, National Scholarship for Graduate Students</p>
    <p><li> 2016, National Scholarship for Graduate Students</p>
  </div>  

  <div class="w3-light-grey w3-center w3-padding-24">

    Welcome to use this website's <a href="https://github.com/YunheWang/HomePage">source code</a>, just add a link back to here. <a href="https://www.wangyunhe.site/">&#10025;</a></br>

  <!-- Default Statcounter code for Yunhe Wang's Homepage
  https://www.wangyunhe.site -->
  No.
  <script type="text/javascript">
  var sc_project=12347113; 
  var sc_invisible=0; 
  var sc_security="21aca5d1"; 
  var sc_https=1; 
  var scJsHost = "https://";
  document.write("<sc"+"ript type='text/javascript' src='" + scJsHost+
  "statcounter.com/counter/counter.js'></"+"script>");
  </script> Visitor Since Feb 2022. Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-opacity">w3.css</a>
  <noscript>
    <div class="statcounter"><a title="Web Analytics Made Easy -
  StatCounter" href="https://statcounter.com/" target="_blank"><img
  class="statcounter" src="https://c.statcounter.com/12347113/0/21aca5d1/0/"
  alt="Web Analytics Made Easy - StatCounter"></a></div>
  </noscript>
  <!-- End of Statcounter Code -->

  </div>

  <!-- End page content -->
</div>

<script>
// Accordion 
function myAccFunc() {
  var x = document.getElementById("demoAcc");
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else {
    x.className = x.className.replace(" w3-show", "");
  }
}

// Click on the "Jeans" link on page load to open the accordion for demo purposes
document.getElementById("myBtn").click();


// Open and close sidebar
function w3_open() {
  document.getElementById("mySidebar").style.display = "block";
  document.getElementById("myOverlay").style.display = "block";
}
 
function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
  document.getElementById("myOverlay").style.display = "none";
}
</script>

</body>
</html>
