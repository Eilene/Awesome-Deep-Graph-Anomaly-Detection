
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

<!-- Begin Jekyll SEO tag v2.7.1 -->
<title>Awesome-Deep-Graph-Anomaly-Detection | Awesome graph anomaly detection techniques built based on deep learning frameworks. We also provide collections of datasets, papers as well as implementations in this github repository</title>
<meta name="generator" content="Jekyll v3.9.0" />
<meta property="og:title" content="Awesome-Deep-Graph-Anomaly-Detection" />
<meta property="og:locale" content="en_US" />
<meta name="description" content="Awesome graph anomaly detection techniques built based on deep learning frameworks. We also provide collections of datasets, papers as well as implementations in this github repository" />
<meta property="og:description" content="Awesome graph anomaly detection techniques built based on deep learning frameworks. We also provide collections of datasets, papers as well as implementations in this github repository" />
<link rel="canonical" href="https://xiaoxiaoma-mq.github.io/Awesome-Deep-Graph-Anomaly-Detection/" />
<meta property="og:url" content="https://xiaoxiaoma-mq.github.io/Awesome-Deep-Graph-Anomaly-Detection/" />
<meta property="og:site_name" content="Awesome-Deep-Graph-Anomaly-Detection" />
<meta name="twitter:card" content="summary" />
<meta property="twitter:title" content="Awesome-Deep-Graph-Anomaly-Detection" />
<script type="application/ld+json">
{"description":"Awesome graph anomaly detection techniques built based on deep learning frameworks. We also provide collections of datasets, papers as well as implementations in this github repository","url":"https://xiaoxiaoma-mq.github.io/Awesome-Deep-Graph-Anomaly-Detection/","@type":"WebSite","headline":"Awesome-Deep-Graph-Anomaly-Detection","name":"Awesome-Deep-Graph-Anomaly-Detection","@context":"https://schema.org"}</script>
<!-- End Jekyll SEO tag -->

    <link rel="stylesheet" href="/Awesome-Deep-Graph-Anomaly-Detection/assets/css/style.css?v=d4763ad8392bc195dce6ae3f0a63c3442e6b3710">
    <!--[if lt IE 9]>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv.min.js"></script>
    <![endif]-->
    <!-- start custom head snippets, customize with your own _includes/head-custom.html file -->

<!-- Setup Google Analytics -->



<!-- You can set your favicon here -->
<!-- link rel="shortcut icon" type="image/x-icon" href="/Awesome-Deep-Graph-Anomaly-Detection/favicon.ico" -->

<!-- end custom head snippets -->

  </head>
  <body>
    <div class="wrapper">
      <header>
        <h1><a href="https://xiaoxiaoma-mq.github.io/Awesome-Deep-Graph-Anomaly-Detection/">Awesome-Deep-Graph-Anomaly-Detection</a></h1>

        

        <p>Awesome graph anomaly detection techniques built based on deep learning frameworks. We also provide collections of datasets, papers as well as implementations in this github repository</p>

        
        <p class="view"><a href="https://github.com/XiaoxiaoMa-MQ/Awesome-Deep-Graph-Anomaly-Detection">View the Project on GitHub <small>XiaoxiaoMa-MQ/Awesome-Deep-Graph-Anomaly-Detection</small></a></p>
        

        

        
      </header>
      <section>

      <h1 id="awesome-deep-graph-anomaly-detection">Awesome-Deep-Graph-Anomaly-Detection</h1>

<p><a href="https://github.com/XiaoxiaoMa-MQ/Awesome-Deep-Graph-Anomaly-Detection"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome" /></a> <a href="https://github.com/XiaoxiaoMa-MQ/Awesome-Deep-Graph-Anomaly-Detection"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome" /></a> <img src="https://img.shields.io/github/stars/XiaoxiaoMa-MQ/Awesome-Deep-Graph-Anomaly-Detection?color=yellow&amp;label=Stars" alt="GitHub stars" /> <img src="https://img.shields.io/github/forks/XiaoxiaoMa-MQ/Awesome-Deep-Graph-Anomaly-Detection?color=blue&amp;label=Forks" alt="GitHub forks" /> <img src="https://visitor-badge.glitch.me/badge?page_id=littleTreeme" alt="" /></p>

<p>A collection of papers on deep learning for graph anomaly detection, and published algorithms and datasets.</p>

<ul>
  <li><a href="#awesome-deep-graph-anomaly-detection">Awesome-Deep-Graph-Anomaly-Detection</a>
    <ul>
      <li><a href="#a-timeline-of-graph-anomaly-detection">A Timeline of graph anomaly detection</a></li>
      <li><a href="#survey">Survey</a></li>
      <li><a href="#anomalous-node-detection-on-static-graphs">Anomalous Node Detection on Static Graphs</a>
        <ul>
          <li><a href="#anomalous-node-detection-on-static-plain-graphs">Anomalous Node Detection on Static Plain Graphs</a>
            <ul>
              <li><a href="#traditional-non-deep-learning-techniques">Traditional Non-Deep Learning Techniques</a></li>
              <li><a href="#network-representation-based-techniques">Network Representation Based Techniques</a></li>
            </ul>
          </li>
          <li><a href="#anomalous-node-detection-on-static-attributed-graphs">Anomalous Node Detection on Static Attributed Graphs</a>
            <ul>
              <li><a href="#traditional-non-deep-learning-techniques-1">Traditional Non-Deep Learning Techniques</a></li>
              <li><a href="#deep-neural-network-based-techniques">Deep Neural Network Based Techniques</a></li>
              <li><a href="#graph-convolutional-neural-network-based-techniques">Graph Convolutional Neural Network Based Techniques</a></li>
              <li><a href="#graph-attention-neural-network-based-techniques">Graph Attention Neural Network Based Techniques</a></li>
              <li><a href="#generative-adversarial-neural-network-based-techniques">Generative Adversarial Neural Network Based Techniques</a></li>
              <li><a href="#reinforcement-learning-based-techniques">Reinforcement Learning Based Techniques</a></li>
              <li><a href="#network-representation-based-techniques-1">Network Representation Based Techniques</a></li>
            </ul>
          </li>
        </ul>
      </li>
      <li><a href="#anomalous-node-detection-on-dynamic-graphs">Anomalous Node Detection on Dynamic Graphs</a></li>
      <li><a href="#anomalous-edge-detection">Anomalous Edge Detection</a></li>
      <li><a href="#anomalous-sub-graph-detection">Anomalous Sub-graph Detection</a></li>
      <li><a href="#anomalous-graph-detection">Anomalous Graph Detection</a></li>
      <li><a href="#published-algorithms-and-models">Published Algorithms and Models</a></li>
      <li><a href="#datasets">Datasets</a>
        <ul>
          <li><a href="#citationco-authorship-networks">Citation/Co-authorship Networks</a></li>
          <li><a href="#social-networks">Social Networks</a></li>
          <li><a href="#co-purchasing-networks">Co-purchasing Networks</a></li>
          <li><a href="#transportation-networks">Transportation Networks</a></li>
        </ul>
      </li>
      <li><a href="#tools">Tools</a></li>
    </ul>
  </li>
</ul>

<hr />
<h2 id="a-timeline-of-graph-anomaly-detection">A Timeline of graph anomaly detection</h2>
<p><a href="https://github.com/XiaoxiaoMa-MQ/Awesome-Deep-Graph-Anomaly-Detection/"><img src="/Awesome-Deep-Graph-Anomaly-Detection/Timeline.png" alt="timeline" /></a></p>

<h2 id="survey">Survey</h2>
<p><strong>A Comprehensive Survey on Graph Anomaly Detection with Deep Learning</strong>. <strong>28 Pages</strong>, IEEE Trans. Knowl. Data Eng., 2021. 
<em>Xiaoxiao Ma, Jia Wu, Shan Xue, Jian Yang, Chuan Zhou, Quan Z. Sheng, Hui Xiong, Leman Akoglu</em>, [<a href="https://www.computer.org/csdl/journal/tk/5555/01/09565320/1xx849OoPks">Paper</a>] [<a href="https://arxiv.org/abs/2106.07178">arXiv</a>]</p>

<p>Link: https://www.computer.org/csdl/journal/tk/5555/01/09565320/1xx849OoPks, https://arxiv.org/abs/2106.07178</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>@article{ma2021comprehensive,
    title={A comprehensive survey on graph anomaly detection with 
            deep learning},
    author={Ma, Xiaoxiao and Wu, Jia and Xue, Shan and Yang, Jian and 
            Zhou, Chuan and Sheng, Quan Z and Xiong, Hui and
            Akoglu, Leman},
    journal={IEEE Transactions on Knowledge and Data Engineering},
    year={2021},
    publisher={IEEE}
}
</code></pre></div></div>

<table>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Venue</th>
      <th>Year</th>
      <th>Authors</th>
      <th>Materials</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Deep learning for anomaly detection</td>
      <td>ACM Comput. Surv.</td>
      <td>2021</td>
      <td><em>Pang et al.</em></td>
      <td>[<a href="https://dl.acm.org/doi/pdf/10.1145/3439950">Paper</a>]</td>
    </tr>
    <tr>
      <td>Anomaly detection for big data using efficient techniques: A review</td>
      <td>AIDE</td>
      <td>2021</td>
      <td><em>Jennifer and Kumar</em></td>
      <td>[<a href="https://link.springer.com/chapter/10.1007/978-981-15-3514-7_79">Paper</a>]</td>
    </tr>
    <tr>
      <td>Anomalous Example Detection in Deep Learning: A Survey</td>
      <td>IEEE</td>
      <td>2021</td>
      <td><em>Bulusu et al.</em></td>
      <td>[<a href="https://ieeexplore.ieee.org/iel7/6287639/8948470/09144212.pdf">Paper</a>]</td>
    </tr>
    <tr>
      <td>Outlier detection: Methods, models, and classification</td>
      <td>ACM Comput. Surv.</td>
      <td>2020</td>
      <td><em>Boukerche et al.</em></td>
      <td>[<a href="https://dl.acm.org/doi/pdf/10.1145/3381028">Paper</a>]</td>
    </tr>
    <tr>
      <td>A comprehensive survey of anomaly detection techniques for high dimensional big data</td>
      <td>J. Big Data</td>
      <td>2020</td>
      <td><em>Thudumu et al.</em></td>
      <td>[<a href="https://link.springer.com/article/10.1186/s40537-020-00320-x">Paper</a>]</td>
    </tr>
    <tr>
      <td>Machine learning techniques for network anomaly detection: A survey</td>
      <td>Int. Conf. Inform. IoT Enabling Technol</td>
      <td>2020</td>
      <td><em>Eltanbouly et al.</em></td>
      <td>[<a href="https://ieeexplore.ieee.org/iel7/9081868/9089428/09089465.pdf">Paper</a>]</td>
    </tr>
    <tr>
      <td>Fraud detec- tion: A systematic literature review of graph-based anomaly detection approaches</td>
      <td>Decis. Support Syst.</td>
      <td>2020</td>
      <td><em>Pourhabibi et al.</em></td>
      <td>[<a href="https://dl.acm.org/doi/10.1145/3172867">Paper</a>]</td>
    </tr>
    <tr>
      <td>A comprehensive survey on network anomaly detection</td>
      <td>Telecommun. Syst.</td>
      <td>2020</td>
      <td><em>Fernandes et al.</em></td>
      <td>[<a href="https://dl.acm.org/doi/10.1145/3172867">Paper</a>]</td>
    </tr>
    <tr>
      <td>A survey of deep learning-based network anomaly detection</td>
      <td>Clust. Comput.</td>
      <td>2019</td>
      <td><em>Kwon et al.</em></td>
      <td>[<a href="https://dl.acm.org/doi/10.1145/3172867">Paper</a>]</td>
    </tr>
    <tr>
      <td>Combining machine learning with knowledge engineering to detect fake news in social networks-a survey</td>
      <td>AAAI Conf. Artif. Intell</td>
      <td>2019</td>
      <td><em>Hunkelmann et al.</em></td>
      <td>[<a href="https://dl.acm.org/doi/10.1145/3172867">Paper</a>]</td>
    </tr>
    <tr>
      <td>Deep learning for anomaly detection: A survey</td>
      <td>arXiv</td>
      <td>2019</td>
      <td><em>Chalapathy and Chawla</em></td>
      <td>[<a href="https://arxiv.org/pdf/1901.03407.pdf">Paper</a>]</td>
    </tr>
    <tr>
      <td>Anomaly detection in dynamic networks: A survey</td>
      <td>Wiley Interdiscip. Rev. Comput. Stat.</td>
      <td>2018</td>
      <td><em>Ranshous et al.</em></td>
      <td>[<a href="https://wires.onlinelibrary.wiley.com/doi/pdfdirect/10.1002/wics.1347">Paper</a>]</td>
    </tr>
    <tr>
      <td>A survey on social media anomaly detection</td>
      <td>SIGKDD Explor.</td>
      <td>2016</td>
      <td><em>Yu et al.</em></td>
      <td>[<a href="https://dl.acm.org/doi/pdf/10.1145/2980765.2980767">Paper</a>]</td>
    </tr>
    <tr>
      <td>Graph based anomaly detection and description: A survey</td>
      <td>Data Min. Knowl. Discovery</td>
      <td>2015</td>
      <td><em>Akoglu et al.</em></td>
      <td>[<a href="https://idp.springer.com/authorize/casa?redirect_uri=https://link.springer.com/article/10.1007/s10618-014-0365-y">Paper</a>]</td>
    </tr>
    <tr>
      <td>Anomaly detection in online social networks</td>
      <td>Soc. Networks</td>
      <td>2014</td>
      <td><em>Savage et al.</em></td>
      <td>[<a href="https://www.sciencedirect.com/science/article/pii/S0378873314000331">Paper</a>]</td>
    </tr>
    <tr>
      <td>A survey of outlier detection methods in network anomaly identification</td>
      <td>Comput. J.</td>
      <td>2011</td>
      <td><em>Gogoi et al.</em></td>
      <td>[<a href="https://academic.oup.com/comjnl/article-pdf/54/4/570/1024761/bxr026.pdf">Paper</a>]</td>
    </tr>
    <tr>
      <td>Anomaly detection: A survey</td>
      <td>ACM Comput. Surv.</td>
      <td>2009</td>
      <td><em>Chandola et al.</em></td>
      <td>[<a href="https://dl.acm.org/doi/pdf/10.1145/1541880.1541882">Paper</a>]</td>
    </tr>
  </tbody>
</table>

<hr />

<h2 id="anomalous-node-detection-on-static-graphs">Anomalous Node Detection on Static Graphs</h2>

<h3 id="anomalous-node-detection-on-static-plain-graphs">Anomalous Node Detection on Static Plain Graphs</h3>

<h4 id="traditional-non-deep-learning-techniques">Traditional Non-Deep Learning Techniques</h4>

<table>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Venue</th>
      <th>Year</th>
      <th>Authors</th>
      <th>Materials</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Oddball: Spotting anomalies in weighted graphs</td>
      <td>Pacific-Asia Conf. Knowl. Discov. Data Mining.</td>
      <td>2016</td>
      <td><em>Akoglu et al.</em></td>
      <td>[<a href="https://kilthub.cmu.edu/articles/OddBall_Spotting_Anomalies_in_Weighted_Graphs/6607802/files/12098360.pdf">Paper</a>]</td>
    </tr>
    <tr>
      <td>Fraudar: Bounding graph fraud in the face of camouflage</td>
      <td>ACM SIGKDD</td>
      <td>2016</td>
      <td><em>Hooi et al.</em></td>
      <td>[<a href="https://dl.acm.org/doi/pdf/10.1145/2939672.2939747">Paper</a>]</td>
    </tr>
    <tr>
      <td>Intrusion as (anti)social communication: characterization and detection</td>
      <td>ACM SIGKDD</td>
      <td>2012</td>
      <td><em>Ding et al.</em></td>
      <td>[<a href="https://dl.acm.org/doi/pdf/10.1145/2339530.2339670">Paper</a>]</td>
    </tr>
  </tbody>
</table>

<hr />

<h4 id="network-representation-based-techniques">Network Representation Based Techniques</h4>
<p>| Paper Title | Venue | Year | Authors | Materials | 
| —- | —- | – | —- | —- | 
| Decoupling representation learning and classification for gnn-based anomaly detection | Int. ACM SIGIR | 2021 | <em>Wang et al.</em> | [<a href="https://dl.acm.org/doi/pdf/10.1145/3404835.3462944">Paper</a>] |
| An embedding approach to anomaly detection | Int. Conf. Data Eng. | 2016 | <em>Hu et al.</em> | [<a href="https://ieeexplore.ieee.org/iel7/7491900/7498210/07498256.pdf">Paper</a>] |</p>

<hr />

<h3 id="anomalous-node-detection-on-static-attributed-graphs">Anomalous Node Detection on Static Attributed Graphs</h3>

<h4 id="traditional-non-deep-learning-techniques-1">Traditional Non-Deep Learning Techniques</h4>
<p>| Paper Title | Venue | Year | Authors | Materials | 
| —- | —- | – | —- | —- | 
| Anomalous: A joint modeling approach for anomaly detection on attributed networks | Int. Joint Conf. Artif. Intell. | 2018 | <em>Peng et al.</em> | [<a href="https://www.ijcai.org/Proceedings/2018/0488.pdf">Paper</a>] |
| Accelerated local anomaly detection via resolving attributed networks | Int. Joint Conf. Artif. Intell. | 2017 | <em>Liu et al.</em> | [<a href="https://www.ijcai.org/Proceedings/2017/0325.pdf">Paper</a>] |
| Radar: Residual analysis for anomaly detection in attributed networks | Int. Joint Conf. Artif. Intell., | 2017 | <em>Li et al.</em> | [<a href="https://www.researchgate.net/profile/Jundong-Li/publication/318830338_Radar_Residual_Analysis_for_Anomaly_Detection_in_Attributed_Networks/links/5a1f17c4458515a4c3d478ce/Radar-Residual-Analysis-for-Anomaly-Detection-in-Attributed-Networks.pdf">Paper</a>] |</p>

<hr />

<h4 id="deep-neural-network-based-techniques">Deep Neural Network Based Techniques</h4>
<p>| Paper Title | Venue | Year | Authors | Materials | 
| —- | —- | – | —- | —- | 
| Outlier resistant unsupervised deep architectures for attributed network embedding | Int. Conf. Web Search Data Mining | 2020 | <em>Bandyopadhyay et al.</em> | [<a href="https://dl.acm.org/doi/pdf/10.1145/3336191.3371788">Paper</a>] |</p>

<hr />

<h4 id="graph-convolutional-neural-network-based-techniques">Graph Convolutional Neural Network Based Techniques</h4>

<table>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Venue</th>
      <th>Year</th>
      <th>Authors</th>
      <th>Materials</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Resgcn: Attention-based deep residual modeling for anomaly detection on attributed networks</td>
      <td>Mach. Learn.</td>
      <td>2021</td>
      <td><em>Pei et al.</em></td>
      <td>[<a href="https://link.springer.com/article/10.1007/s10994-021-06044-0">Paper</a>]</td>
    </tr>
    <tr>
      <td>A deep multi-view framework for anomaly detection on attributed networks</td>
      <td>IEEE Trans. Knowl. Data Eng.</td>
      <td>2020</td>
      <td><em>Peng et al.</em></td>
      <td>[<a href="https://ieeexplore.ieee.org/iel7/69/4358933/09162509.pdf">Paper</a>]</td>
    </tr>
    <tr>
      <td>Specae: Spectral autoencoder for anomaly detection in attributed networks</td>
      <td>Int. Conf. Inf. Knowl. Manage.</td>
      <td>2020</td>
      <td><em>Li et al.</em></td>
      <td>[<a href="https://dl.acm.org/doi/pdf/10.1145/3357384.3358074">Paper</a>]</td>
    </tr>
    <tr>
      <td>Gcn-based user representation learning for unifying robust recommendation and fraudster detection</td>
      <td>ACM SIGIR</td>
      <td>2020</td>
      <td><em>Zhang et al.</em></td>
      <td>[<a href="https://dl.acm.org/doi/pdf/10.1145/3397271.3401165">Paper</a>]</td>
    </tr>
    <tr>
      <td>Deep anomaly detection on attributed networks</td>
      <td>SIAM Int. Conf. Data Mining</td>
      <td>2019</td>
      <td><em>Ding et al.</em></td>
      <td>[<a href="https://epubs.siam.org/doi/pdf/10.1137/1.9781611975673.67">Paper</a>]</td>
    </tr>
    <tr>
      <td>Fdgars: Fraudster detection via graph convolutional networks in online app review system</td>
      <td>Int. Conf. World Wide Web</td>
      <td>2019</td>
      <td><em>Wang et al.</em></td>
      <td>[<a href="https://dl.acm.org/doi/pdf/10.1145/3308560.3316586">Paper</a>]</td>
    </tr>
  </tbody>
</table>

<hr />

<h4 id="graph-attention-neural-network-based-techniques">Graph Attention Neural Network Based Techniques</h4>

<table>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Venue</th>
      <th>Year</th>
      <th>Authors</th>
      <th>Materials</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Anomalydae: Dual autoencoder for anomaly detection on attributed networks</td>
      <td>IEEE Int. Conf. Acoustics Speech Signal Processing</td>
      <td>2020</td>
      <td><em>Fan et al.</em></td>
      <td>[<a href="https://ieeexplore.ieee.org/iel7/9040208/9052899/09053387.pdf">Paper</a>]</td>
    </tr>
    <tr>
      <td>A semi-supervised graph attentive network for financial fraud detection</td>
      <td>IEEE Int. Conf. Data Mining</td>
      <td>2019</td>
      <td><em>Wang et al.</em></td>
      <td>[<a href="https://ieeexplore.ieee.org/iel7/8961330/8970627/08970829.pdf">Paper</a>]</td>
    </tr>
  </tbody>
</table>

<hr />

<h4 id="generative-adversarial-neural-network-based-techniques">Generative Adversarial Neural Network Based Techniques</h4>

<table>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Venue</th>
      <th>Year</th>
      <th>Authors</th>
      <th>Materials</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Inductive anomaly detection on attributed networks</td>
      <td>Int. Joint Conf. Artif. Intell.</td>
      <td>2020</td>
      <td><em>Ding et al.</em></td>
      <td>[<a href="https://asu.pure.elsevier.com/en/publications/inductive-anomaly-detection-on-attributed-networks">Paper</a>]</td>
    </tr>
  </tbody>
</table>

<hr />

<h4 id="reinforcement-learning-based-techniques">Reinforcement Learning Based Techniques</h4>
<p>| Paper Title | Venue | Year | Authors | Materials | 
| —- | —- | – | —- | —- | 
| Selective network discovery via deep reinforcement learning on embedded spaces | Appl.Network Sci. | 2021 | <em>Morales et al.</em> | [<a href="https://appliednetsci.springeropen.com/articles/10.1007/s41109-021-00365-8">Paper</a>] |
| Interactive anomaly detection on attributed networks | Int. Conf. Web Search Data Mining | 2019 | <em>Ding et al.</em> | [<a href="https://dl.acm.org/doi/pdf/10.1145/3289600.3290964">Paper</a>] |</p>

<hr />

<h4 id="network-representation-based-techniques-1">Network Representation Based Techniques</h4>
<p>| Paper Title | Venue | Year | Authors | Materials | 
| —- | —- | – | —- | —- | 
| Anomaly detection on attributed networks via contrastive self-supervised learning | IEEE Trans. Neural Networks Learn. Syst. | 2021 | <em>Liu et al.</em> | [<a href="https://ieeexplore.ieee.org/iel7/5962385/6104215/09395172.pdf">Paper</a>] |
| Cross-domain graph anomaly detection | IEEE Trans. Neural Networks Learn. Syst. | 2021 | <em>Ding et al.</em> | [<a href="https://ieeexplore.ieee.org/iel7/5962385/6104215/09556511.pdf">Paper</a>] |
| Fraudre: Fraud detection dual-resistant to graph inconsistency and imbalance | ICDM | 2021 | <em>Zhang et al.</em> | [<a href="">Paper</a>] |
| Few-shot network anomaly detection via cross-network meta-learning | Web Conf. | 2021 | <em>Ding et al.</em> | [<a href="https://dl.acm.org/doi/pdf/10.1145/3442381.3449922">Paper</a>] |
| One-class graph neural networks for anomaly detection in attributed networks | Neural Comput. Appl. | 2021 | <em>Wang et al.</em> | [<a href="https://idp.springer.com/authorize/casa?redirect_uri=https://link.springer.com/article/10.1007/s00521-021-05924-9">Paper</a>] |
| Error-bounded graph anomaly loss for gnns | ACM Int. Conf. Inf. Knowl. Manage. | 2021 | <em>Zhao et al.</em> | [<a href="https://dl.acm.org/doi/pdf/10.1145/3340531.3411979">Paper</a>] |
| Enhancing graph neural network-based fraud detectors against camouflaged fraudsters | ACM Int. Conf. Inf. Knowl. Manage. | 2020 | <em>Dou et al.</em> | [<a href="https://dl.acm.org/doi/pdf/10.1145/3340531.3411903">Paper</a>] |
| A robust embedding method for anomaly detection on attributed networks | Int. Joint Conf. Neural Netw. | 2019 | <em>Zhang et al.</em> | [<a href="https://ieeexplore.ieee.org/iel7/8840768/8851681/08852354.pdf">Paper</a>] |
| Semi-supervised embedding in attributed networks with outliers | SIAM Int. Conf. Data Mining | 2018 | <em>Liang et al.</em> | [<a href="https://epubs.siam.org/doi/pdf/10.1137/1.9781611975321.18">Paper</a>] |</p>

<hr />

<h2 id="anomalous-node-detection-on-dynamic-graphs">Anomalous Node Detection on Dynamic Graphs</h2>
<p>| Paper Title | Venue | Year | Authors | Materials | 
| —- | —- | – | —- | —- | 
| One-class adversarial nets for fraud detection | AAAI Conf. Artif. Intell. | 2019 | <em>Zheng et al.</em> | [<a href="https://ojs.aaai.org/index.php/AAAI/article/view/3924/3802">Paper</a>] |
| Netwalk: A flexible deep embedding approach for anomaly detection in dynamic networks | ACM SIGKDD | 2018 | <em>Yu et al.</em> | [<a href="https://dl.acm.org/doi/pdf/10.1145/3219819.3220024">Paper</a>] |
| Anomaly detection in dynamic networks using multi-view time-series hypersphere learning | ACM Int. Conf. Inf. Knowl. Manage. | 2017 | <em>Teng et al.</em> | [<a href="https://dl.acm.org/doi/pdf/10.1145/3132847.3132964">Paper</a>] |</p>

<hr />

<h2 id="anomalous-edge-detection">Anomalous Edge Detection</h2>

<table>
  <thead>
    <tr>
      <th>Paper Title</th>
      <th>Venue</th>
      <th>Year</th>
      <th>Authors</th>
      <th>Materials</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>efraudcom: An e-commerce fraud detection system via competitive graph neural networks</td>
      <td>ACM Trans. Inf. Syst.</td>
      <td>2021</td>
      <td><em>Zhang et al.</em></td>
      <td>[<a href="https://www.researchgate.net/profile/Chuan-Zhou-3/publication/353353148_eFraudCom_An_E-commerce_Fraud_Detection_System_via_Competitive_Graph_Neural_Networks/links/60f768e30c2bfa282aeefa52/eFraudCom-An-E-commerce-Fraud-Detection-System-via-Competitive-Graph-Neural-Networks.pdf">Paper</a>]</td>
    </tr>
    <tr>
      <td>Unified graph embedding-based anomalous edge detection</td>
      <td>Int. Joint Conf. Neural Netw.</td>
      <td>2020</td>
      <td><em>Ouyang et al.</em></td>
      <td>[<a href="https://ieeexplore.ieee.org/iel7/9200848/9206590/09206720.pdf">Paper</a>]</td>
    </tr>
    <tr>
      <td>Aane: Anomaly aware network embedding for anomalous link detection</td>
      <td>IEEE Int. Conf. Data Mining</td>
      <td>2020</td>
      <td><em>Duan et al.</em></td>
      <td>[<a href="https://ieeexplore.ieee.org/iel7/9338245/9338248/09338406.pdf">Paper</a>]</td>
    </tr>
    <tr>
      <td>Addgraph: Anomaly detection in dynamic graph using attention-based temporal gcn</td>
      <td>Int. Joint Conf. Artif. Intell.</td>
      <td>2019</td>
      <td><em>Zheng et al.</em></td>
      <td>[<a href="https://www.ijcai.org/Proceedings/2019/0614.pdf">Paper</a>]</td>
    </tr>
    <tr>
      <td>Netwalk: A flexible deep embedding approach for anomaly detection in dynamic networks</td>
      <td>ACM SIGKDD</td>
      <td>2018</td>
      <td><em>Yu et al.</em></td>
      <td>[<a href="https://dl.acm.org/doi/pdf/10.1145/3219819.3220024">Paper</a>]</td>
    </tr>
  </tbody>
</table>

<hr />

<h2 id="anomalous-sub-graph-detection">Anomalous Sub-graph Detection</h2>
<p>| Paper Title | Venue | Year | Authors | Materials | 
| —- | —- | – | —- | —- | 
| Deep structure learning for fraud detection | IEEE Int. Conf. Data Mining | 2018 | <em>Wang et al.</em> | [<a href="https://ieeexplore.ieee.org/iel7/8591042/8594809/08594881.pdf">Paper</a>] |
| Fraudne: A joint embedding approach for fraud detection | Int. Joint Conf. Neural Netw. | 2018 | <em>Zheng et al.</em> | [<a href="https://ieeexplore.ieee.org/iel7/8465565/8488986/08489585.pdf">Paper</a>] |</p>

<hr />

<h2 id="anomalous-graph-detection">Anomalous Graph Detection</h2>
<p>| Paper Title | Venue | Year | Authors | Materials | 
| —- | —- | – | —- | —- | 
| User preference-aware fake news detection | arXiv | 2021 | <em>Dou et al.</em> | [<a href="https://arxiv.org/abs/2104.12259">Paper</a>] |
| On using classification datasets to evaluate graph outlier detection: Peculiar observations and new insights | arXiv | 2021 | <em>Zheng et al.</em> | [<a href="https://arxiv.org/abs/2012.12931">Paper</a>] |
| Glad-paw: Graph-based log anomaly detection by position aware weighted graph attention network | Pacific-Asia Conf. Knowl. Discov. Data Mining | 2021 | <em>Zheng et al.</em> | [<a href="https://link.springer.com/content/pdf/10.1007/978-3-030-75762-5_6.pdf">Paper</a>] |
| Deep into hypersphere: Robust and unsupervised anomaly discovery in dynamic networks | Int. Joint Conf. Artif. Intell. | 2018 | <em>Teng et al.</em> | [<a href="https://par.nsf.gov/servlets/purl/10070284">Paper</a>] |</p>

<hr />

<h2 id="published-algorithms-and-models">Published Algorithms and Models</h2>

<table>
  <thead>
    <tr>
      <th>Model</th>
      <th>Language</th>
      <th>Platform</th>
      <th>Graph</th>
      <th>Code Repository</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Sedanspot</td>
      <td>C++</td>
      <td>-</td>
      <td>Dynamic Graph</td>
      <td>https://www.github.com/dhivyaeswaran/sedanspot</td>
    </tr>
    <tr>
      <td>AnomalyDAE</td>
      <td>Python</td>
      <td>Tensorflow</td>
      <td>Dynamic Attribute Graph</td>
      <td>https://github.com/haoyfan/AnomalyDAE</td>
    </tr>
    <tr>
      <td>MADAN</td>
      <td>Python</td>
      <td>-</td>
      <td>Static Attributed Graph</td>
      <td>https://github.com/leoguti85/MADAN</td>
    </tr>
    <tr>
      <td>PAICAN</td>
      <td>Python</td>
      <td>Tensorflow</td>
      <td>Static Attributed Graph</td>
      <td>http://www.kdd.in.tum.de/PAICAN/</td>
    </tr>
    <tr>
      <td>Changedar</td>
      <td>Matlab</td>
      <td>-</td>
      <td>Dynamic Attributed Graph</td>
      <td>https://bhooi.github.io/changedar/</td>
    </tr>
    <tr>
      <td>ONE</td>
      <td>Python</td>
      <td>-</td>
      <td>Static Plain Graph</td>
      <td>https://github.com/sambaranban/ONE</td>
    </tr>
    <tr>
      <td>DONE&amp;AdONE</td>
      <td>Python</td>
      <td>Tensorflow</td>
      <td>Static Attributed Graph</td>
      <td>https://bit.ly/35A2xHs</td>
    </tr>
    <tr>
      <td>SLICENDICE</td>
      <td>Python</td>
      <td>-</td>
      <td>Static Attributed Graph</td>
      <td>http://github.com/hamedn/SliceNDice/</td>
    </tr>
    <tr>
      <td>FRAUDRE</td>
      <td>Python</td>
      <td>Pytorch</td>
      <td>Static Attributed Graph</td>
      <td>https://github.com/FraudDetection/FRAUDRE</td>
    </tr>
    <tr>
      <td>SemiGNN</td>
      <td>Python</td>
      <td>Tensorflow</td>
      <td>Static Attributed Graph</td>
      <td>https://github.com/safe-graph/DGFraud</td>
    </tr>
    <tr>
      <td>CARE-GNN</td>
      <td>Python</td>
      <td>Pytorch</td>
      <td>Static Attributed Graph</td>
      <td>https://github.com/YingtongDou/CARE-GNN</td>
    </tr>
    <tr>
      <td>GraphConsis</td>
      <td>Python</td>
      <td>Tensorflow</td>
      <td>Static Attributed Graph</td>
      <td>https://github.com/safe-graph/DGFraud</td>
    </tr>
    <tr>
      <td>GLOD</td>
      <td>Python</td>
      <td>Pytorch</td>
      <td>Static Attributed Graph</td>
      <td>https://github.com/LingxiaoShawn/GLOD-Issues</td>
    </tr>
    <tr>
      <td>GCAN</td>
      <td>Python</td>
      <td>Keras</td>
      <td>Heterogeneous Graph</td>
      <td>https://github.com/l852888/GCAN</td>
    </tr>
    <tr>
      <td>HGATRD</td>
      <td>Python</td>
      <td>Pytorch</td>
      <td>Heterogeneous Graph</td>
      <td>https://github.com/201518018629031/HGATRD</td>
    </tr>
    <tr>
      <td>GLAN</td>
      <td>Python</td>
      <td>Pytorch</td>
      <td>Heterogeneous Graph</td>
      <td>https://github.com/chunyuanY/RumorDetection</td>
    </tr>
    <tr>
      <td>ANOMRANK</td>
      <td>C++</td>
      <td>-</td>
      <td>Dynamic Graph</td>
      <td>https://github.com/minjiyoon/anomrank</td>
    </tr>
    <tr>
      <td>DAGMM</td>
      <td>Python</td>
      <td>Pytorch</td>
      <td>Dynamic Graph</td>
      <td>https://github.com/danieltan07/dagmm</td>
    </tr>
    <tr>
      <td>F-FADE</td>
      <td>Python</td>
      <td>Pytorch</td>
      <td>Dynamic Graph</td>
      <td>http://snap.stanford.edu/f-fade/</td>
    </tr>
    <tr>
      <td>OCAN</td>
      <td>Python</td>
      <td>Tensorflow</td>
      <td>Static Graph</td>
      <td>https://github.com/PanpanZheng/OCAN</td>
    </tr>
    <tr>
      <td>DevNet</td>
      <td>Python</td>
      <td>Tensorflow</td>
      <td>Static Graph</td>
      <td>https://github.com/GuansongPang/deviationnetwork</td>
    </tr>
    <tr>
      <td>RDA</td>
      <td>Python</td>
      <td>Tensorflow</td>
      <td>Static Graph</td>
      <td>https://github.com/zc8340311/RobustAutoencoder</td>
    </tr>
    <tr>
      <td>GAD</td>
      <td>Python</td>
      <td>Tensorflow</td>
      <td>Static Graph</td>
      <td>https://github.com/raghavchalapathy/gad</td>
    </tr>
    <tr>
      <td>GEM</td>
      <td>Python</td>
      <td>-</td>
      <td>Static Graph</td>
      <td>https://github.com/safe-graph/DGFraud/tree/master/algorithms/GEM</td>
    </tr>
    <tr>
      <td>eFraudCom</td>
      <td>Python</td>
      <td>Pytorch</td>
      <td>Static Graph</td>
      <td>https://github.com/GeZhangMQ/eFraudCom</td>
    </tr>
    <tr>
      <td>MIDAS</td>
      <td>C++</td>
      <td>-</td>
      <td>Dynamic Graph</td>
      <td>https://github.com/Stream-AD/MIDAS</td>
    </tr>
    <tr>
      <td>DeFrauder</td>
      <td>Python</td>
      <td>-</td>
      <td>Static Graph</td>
      <td>https://github.com/LCS2-IIITD/DeFrauder</td>
    </tr>
    <tr>
      <td>DeepFD</td>
      <td>Python</td>
      <td>Pytorch</td>
      <td>Bipartite Graph</td>
      <td>https://github.com/JiaWu-Repository/DeepFDpyTorch</td>
    </tr>
    <tr>
      <td>STS-NN</td>
      <td>Python</td>
      <td>Pytorch</td>
      <td>Static Graph</td>
      <td>https://github.com/JiaWu-Repository/STS-NN</td>
    </tr>
    <tr>
      <td>UPFD</td>
      <td>Python</td>
      <td>Pytorch</td>
      <td>Graph Database</td>
      <td>https://github.com/safe-graph/GNN-FakeNews</td>
    </tr>
    <tr>
      <td>DeepSphere</td>
      <td>Python</td>
      <td>Tensorflow</td>
      <td>Dynamic Graph</td>
      <td>https://github.com/picsolab/DeepSphere</td>
    </tr>
    <tr>
      <td>OCGIN</td>
      <td>Python</td>
      <td>Pytorch</td>
      <td>Graph Database</td>
      <td>https://github.com/LingxiaoShawn/GLOD-Issues</td>
    </tr>
    <tr>
      <td>Deep SAD</td>
      <td>Python</td>
      <td>Pytorch</td>
      <td>Non Graph</td>
      <td>https://github.com/lukasruff/Deep-SAD-PyTorch</td>
    </tr>
    <tr>
      <td>DATE</td>
      <td>Python</td>
      <td>Pytorch</td>
      <td>Non Graph</td>
      <td>https://github.com/Roytsai27/Dual-Attentive-Treeaware-Embedding</td>
    </tr>
  </tbody>
</table>

<hr />

<h2 id="datasets">Datasets</h2>
<h3 id="citationco-authorship-networks">Citation/Co-authorship Networks</h3>
<ul>
  <li>Citeseer, Cora, Pubmed https://linqs.soe.ucsc.edu/data</li>
  <li>DBLP http://snap.stanford.edu/data/com-DBLP.html, http://www.informatik.uni-trier.de/ ̃ley/db/</li>
  <li>ACM http://www.arnetminer.org/open-academic-graph
    <h3 id="social-networks">Social Networks</h3>
  </li>
  <li>Enron http://odds.cs.stonybrook.edu/#table2</li>
  <li>UCI Message http://archive.ics.uci.edu/ml</li>
  <li>Google+ https://wangbinghui.net/dataset.html</li>
  <li>Twitter Sybil https://wangbinghui.net/dataset.html</li>
  <li>Twitter World-Cup2014 http://shebuti.com/SelectiveAnomalyEnsemble/</li>
  <li>Twitter Security2014 http://shebuti.com/SelectiveAnomalyEnsemble/</li>
  <li>Reality Mining http://shebuti.com/SelectiveAnomalyEnsemble/</li>
  <li>NYTNews http://shebuti.com/SelectiveAnomalyEnsemble/</li>
  <li>Politifact https://github.com/safe-graph/GNN-FakeNews</li>
  <li>Gossipcop https://github.com/safe-graph/GNN-FakeNews
    <h3 id="co-purchasing-networks">Co-purchasing Networks</h3>
  </li>
  <li>Disney Calls https://www.ipd.kit.edu/mitarbeiter/muellere/consub/</li>
  <li>Amazon-v1 https://www.ipd.kit.edu/mitarbeiter/muellere/consub/</li>
  <li>Amazon-v2 https://github.com/dmlc/dgl/blob/master/python/dgl/data/fraud.py</li>
  <li>Elliptic https://www.kaggle.com/ellipticco/elliptic-data-set</li>
  <li>Yelp https://github.com/dmlc/dgl/blob/master/python/dgl/data/fraud.py
    <h3 id="transportation-networks">Transportation Networks</h3>
  </li>
  <li>New York City Taxi http://www.nyc.gov/html/tlc/html/about/triprecorddata.shtml</li>
</ul>

<hr />

<h2 id="tools">Tools</h2>
<ul>
  <li>Gephi https://gephi.org/</li>
  <li>Pajek http://mrvar.fdv.uni-lj.si/pajek/</li>
  <li>LFR https://www.santofortunato.net/resources</li>
</ul>

<hr />
<p><strong>Disclaimer</strong></p>

<p>If you have any questions or updated news on graph anomaly detection, please feel free to contact us.
We also invite researchers interested in anomaly detection, graph representation learning, and graph anomaly detection to join this project as contributors and boost further research in this area.</p>

<p>Emails: <u>xiaoxiao.ma2@hdr.mq.edu.au</u>, <u>jia.wu@mq.edu.au</u>.</p>


      </section>
      <footer>
        
        <p>This project is maintained by <a href="https://github.com/XiaoxiaoMa-MQ">XiaoxiaoMa-MQ</a></p>
        
        <p><small>Hosted on GitHub Pages &mdash; Theme by <a href="https://github.com/orderedlist">orderedlist</a></small></p>
      </footer>
    </div>
    <script src="/Awesome-Deep-Graph-Anomaly-Detection/assets/js/scale.fix.js"></script>
  </body>
</html>
