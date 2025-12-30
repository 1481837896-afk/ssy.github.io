<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>安吉乡村振兴专题</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Microsoft YaHei', sans-serif;
        }
        
        body {
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
            background-image: url('https://images.unsplash.com/photo-1500382017468-9049fed747ef?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80');
            background-size: cover;
            background-attachment: fixed;
            background-position: center;
            background-repeat: no-repeat;
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        /* 栏头样式 - 强化文字居中对齐 */
        .header {
            background: linear-gradient(rgba(0, 80, 0, 0.85), rgba(0, 60, 0, 0.85)), url('https://images.unsplash.com/photo-1500382017468-9049fed747ef?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80');
            background-size: cover;
            background-position: center;
            height: 450px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center; /* 文字水平居中 */
            color: white;
            border-radius: 0 0 15px 15px;
            margin-bottom: 30px;
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.2);
            position: relative;
            overflow: hidden;
        }
        
        .header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://images.unsplash.com/photo-1500382017468-9049fed747ef?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80');
            background-size: cover;
            background-position: center;
            opacity: 0.3;
            z-index: -1;
        }
        
        .header h1 {
            font-size: 3.8rem;
            text-shadow: 3px 3px 10px rgba(0, 0, 0, 0.7);
            margin-bottom: 25px;
            letter-spacing: 4px;
            font-weight: bold;
            text-align: center; /* 标题强制居中 */
            width: 100%; /* 确保宽度铺满，居中生效 */
        }
        
        .header p {
            font-size: 1.3rem;
            max-width: 800px;
            padding: 0 20px;
            text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.7);
            line-height: 1.8;
            text-align: center; /* 副标题强制居中 */
            width: 100%; /* 确保宽度铺满，居中生效 */
            margin: 0 auto; /* 水平居中 */
        }
        
        /* 主内容区域背景 */
        .main-content {
            background-color: rgba(255, 255, 255, 0.92);
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
        }
        
        /* 摘要区样式 */
        .summary {
            background-color: rgba(233, 247, 233, 0.95);
            padding: 35px;
            border-radius: 12px;
            margin-bottom: 40px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
            border-left: 8px solid #4CAF50;
            border-top: 2px solid #c8e6c9;
        }
        
        .summary h2 {
            color: #2e7d32;
            margin-bottom: 20px;
            font-size: 2rem;
        }
        
        .summary p {
            font-size: 1.15rem;
            line-height: 1.9;
        }
        
        /* 栏目区域样式 */
        .sections {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            margin-bottom: 50px;
        }
        
        .section {
            background-color: rgba(255, 255, 255, 0.98);
            border-radius: 12px;
            padding: 30px;
            box-shadow: 0 6px 18px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
            border: 1px solid #e8f5e9;
        }
        
        .section:hover {
            transform: translateY(-8px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.15);
        }
        
        .section-title {
            color: #2e7d32;
            border-bottom: 4px solid #81c784;
            padding-bottom: 12px;
            margin-bottom: 25px;
            font-size: 1.7rem;
            display: flex;
            align-items: center;
        }
        
        .section-title i {
            margin-right: 12px;
            font-size: 1.5rem;
        }
        
        .section.featured {
            border-top: 6px solid #ff9800;
            background-color: rgba(255, 255, 255, 0.98);
        }
        
        .section.featured .section-title {
            color: #e65100;
            border-bottom-color: #ffb74d;
        }
        
        .article-list {
            list-style-type: none;
        }
        
        .article-item {
            padding: 14px 0;
            border-bottom: 2px dashed #e0e0e0;
        }
        
        .article-item:last-child {
            border-bottom: none;
        }
        
        .article-item a {
            color: #333;
            text-decoration: none;
            display: flex;
            align-items: center;
            transition: color 0.2s, padding-left 0.2s;
        }
        
        .article-item a:hover {
            color: #4CAF50;
            padding-left: 8px;
        }
        
        .article-item a i {
            color: #4CAF50;
            margin-right: 12px;
            font-size: 1rem;
        }
        
        /* 多媒体区域样式 */
        .multimedia {
            margin-bottom: 50px;
        }
        
        .multimedia h2 {
            color: #2e7d32;
            margin-bottom: 30px;
            font-size: 2rem;
            border-left: 6px solid #4CAF50;
            padding-left: 18px;
        }
        
        .media-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .image-gallery, .video-gallery {
            background-color: rgba(255, 255, 255, 0.98);
            border-radius: 12px;
            padding: 25px;
            box-shadow: 0 6px 18px rgba(0, 0, 0, 0.1);
            border: 1px solid #e8f5e9;
        }
        
        .gallery-title {
            color: #2e7d32;
            margin-bottom: 20px;
            font-size: 1.5rem;
            display: flex;
            align-items: center;
        }
        
        .gallery-title i {
            margin-right: 12px;
        }
        
        .image-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
        }
        
        .image-item {
            border-radius: 8px;
            overflow: hidden;
            height: 160px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
            border: 2px solid #e8f5e9;
        }
        
        .image-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.4s;
        }
        
        .image-item:hover img {
            transform: scale(1.08);
        }
        
        .video-item {
            margin-bottom: 25px;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
            position: relative;
            height: 220px;
            border: 2px solid #e8f5e9;
        }
        
        .video-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .video-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5);
            display: flex;
            justify-content: center;
            align-items: center;
            transition: background-color 0.3s;
        }
        
        .video-item:hover .video-overlay {
            background-color: rgba(0, 0, 0, 0.7);
        }
        
        .video-overlay a {
            color: white;
            font-size: 3.5rem;
            text-decoration: none;
        }
        
        .video-overlay a:hover {
            color: #4CAF50;
        }
        
        .video-caption {
            padding: 12px 8px;
            font-size: 1rem;
        }
        
        .video-caption a {
            color: #333;
            text-decoration: none;
            font-weight: bold;
        }
        
        .video-caption a:hover {
            color: #4CAF50;
        }
        
        /* 主题图文区域样式 */
        .theme-section {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 35px;
            margin-bottom: 45px;
            align-items: center;
        }
        
        .theme-image {
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
            height: 420px;
            border: 4px solid #e8f5e9;
        }
        
        .theme-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.6s;
        }
        
        .theme-image:hover img {
            transform: scale(1.08);
        }
        
        .theme-content {
            padding: 25px;
        }
        
        .theme-content h2 {
            color: #2e7d32;
            font-size: 2.3rem;
            margin-bottom: 25px;
            border-left: 6px solid #4CAF50;
            padding-left: 18px;
        }
        
        .theme-content p {
            font-size: 1.15rem;
            line-height: 1.9;
            margin-bottom: 25px;
            text-align: justify;
        }
        
        /* 安吉特色介绍 */
        .anji-features {
            background-color: rgba(240, 249, 255, 0.95);
            border-radius: 12px;
            padding: 30px;
            margin-bottom: 45px;
            border: 3px solid #64b5f6;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
        }
        
        .anji-features h3 {
            color: #1565c0;
            font-size: 1.9rem;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
        }
        
        .anji-features h3 i {
            margin-right: 12px;
            color: #1565c0;
        }
        
        .anji-features p {
            font-size: 1.15rem;
            line-height: 1.8;
            margin-bottom: 20px;
        }
        
        .feature-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
            margin-top: 25px;
        }
        
        .feature-tag {
            background-color: rgba(227, 242, 253, 0.9);
            padding: 10px 18px;
            border-radius: 25px;
            font-size: 0.95rem;
            color: #0d47a1;
            border: 2px solid #90caf9;
            transition: all 0.3s;
        }
        
        .feature-tag:hover {
            background-color: #1565c0;
            color: white;
            transform: translateY(-3px);
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
        }
        
        /* 页脚样式 */
        .footer {
            background-color: rgba(46, 125, 50, 0.95);
            color: white;
            padding: 35px 0;
            text-align: center;
            border-radius: 15px 15px 0 0;
            margin-top: 30px;
            box-shadow: 0 -5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .footer p {
            margin-bottom: 12px;
        }
        
        .footer-links {
            display: flex;
            justify-content: center;
            margin-top: 25px;
            flex-wrap: wrap;
        }
        
        .footer-links a {
            color: #c8e6c9;
            text-decoration: none;
            margin: 0 18px;
            transition: color 0.2s;
        }
        
        .footer-links a:hover {
            color: white;
            text-decoration: underline;
        }
        
        /* 响应式设计 */
        @media (max-width: 768px) {
            .header h1 {
                font-size: 2.8rem;
            }
            
            .sections {
                grid-template-columns: 1fr;
            }
            
            .media-container {
                grid-template-columns: 1fr;
            }
            
            .image-grid {
                grid-template-columns: 1fr;
            }
            
            .theme-section {
                grid-template-columns: 1fr;
            }
            
            .theme-image {
                height: 320px;
            }
            
            .feature-tags {
                flex-direction: column;
            }
            
            .header {
                height: 380px;
            }
        }
        
        @media (max-width: 480px) {
            .header h1 {
                font-size: 2.2rem;
            }
            
            .header p {
                font-size: 1.1rem;
            }
        }
    </style>
</head>
<body>
    <!-- 栏头区域 -->
    <header class="header">
        <div class="container">
            <h1>安吉乡村振兴专题</h1>
            <p>从田间地头到美丽乡村，"绿水青山就是金山银山"理念发源地，探索新时代乡村振兴的安吉实践。</p>
        </div>
    </header>
    
    <main class="container">
        <div class="main-content">
            <!-- 主题图文区域 -->
            <section class="theme-section">
                <div class="theme-image">
                    <!-- 替换主题图为安吉特色风光 -->
                    <img src="https://p3-flow-imagex-download-sign.byteimg.com/tos-cn-i-a9rns2rl98/f26f35fba98140139927799b494cdef2.png~tplv-a9rns2rl98-24:720:720.png?rcl=20251229234106826E35FE168394C5DC01&rk3s=8e244e95&rrcfp=8a172a1a&x-expires=1767627666&x-signature=19LiY0uh%2FGSEd0PO8h85pcW6jlg%3D" alt="安吉农耕风光">
                </div>
                <div class="theme-content">
                    <h2>安吉：从农耕文明到乡村振兴</h2>
                    <p>安吉的乡村振兴之路，始于广袤的田野和辛勤的农耕。从传统农业到现代农业，从单一耕作到多元发展，安吉在保留农耕文明精髓的同时，创新农业发展模式，实现了农业增效、农民增收、农村增美。</p>
                    <p>作为"绿水青山就是金山银山"理念的发源地，安吉将农耕文化、生态保护与乡村振兴有机结合，走出了一条具有地方特色的可持续发展之路，为全国乡村振兴提供了宝贵经验。</p>
                </div>
            </section>
            
            <!-- 安吉特色介绍 -->
            <section class="anji-features">
                <h3><i class="fas fa-tractor"></i> 安吉乡村振兴特色</h3>
                <p>安吉县以农业为基础，以生态为底色，以文化为灵魂，全面推进乡村振兴战略。从田间地头的辛勤耕耘到美丽乡村的生动实践，安吉探索出了一条独具特色的乡村振兴之路。</p>
                <div class="feature-tags">
                    <span class="feature-tag">农耕文化传承</span>
                    <span class="feature-tag">生态农业发展</span>
                    <span class="feature-tag">美丽乡村典范</span>
                    <span class="feature-tag">茶竹产业兴旺</span>
                    <span class="feature-tag">农旅融合发展</span>
                    <span class="feature-tag">乡村治理创新</span>
                </div>
            </section>
            
            <!-- 摘要区 -->
            <section class="summary">
                <h2><i class="fas fa-book-open"></i> 专题摘要</h2>
                <p>本专题聚焦安吉县乡村振兴的创新实践，深入分析安吉在"两山"理念指导下，如何将传统农耕与现代发展有机结合，实现生态保护与经济发展双赢。从农耕文明传承、现代农业发展、美丽乡村建设、乡村治理创新等多个维度，全方位展示安吉乡村振兴的成功经验和未来发展方向。</p>
            </section>
            
            <!-- 栏目区域 -->
            <div class="sections">
                <!-- 栏目1：现代农业发展 -->
                <section class="section">
                    <h3 class="section-title"><i class="fas fa-seedling"></i> 现代农业发展</h3>
                    <ul class="article-list">
                        <li class="article-item">
                            <a href="http://zj.people.com.cn/n2/2022/1118/c186327-40200371.html" target="_blank">
                                <i class="fas fa-chevron-right"></i> 安吉白茶标准化种植与管理技术
                            </a>
                        </li>
                        <li class="article-item">
                            <a href="http://zj.people.com.cn/n2/2025/0815/c186327-41323391.html" target="_blank">
                                <i class="fas fa-chevron-right"></i> 生态循环农业模式在安吉的实践
                            </a>
                        </li>
                        <li class="article-item">
                            <a href="http://finance.people.com.cn/n1/2025/0727/c1004-40530358.html" target="_blank">
                                <i class="fas fa-chevron-right"></i> 智慧农业技术在安吉的应用与推广
                            </a>
                        </li>
                        <li class="article-item">
                            <a href="http://zj.people.com.cn/n2/2025/1211/c186327-41438975.html" target="_blank">
                                <i class="fas fa-chevron-right"></i> 安吉农产品品牌建设与市场营销
                            </a>
                        </li>
                    </ul>
                </section>
                
                <!-- 栏目2：农耕文化传承 -->
                <section class="section">
                    <h3 class="section-title"><i class="fas fa-tractor"></i> 农耕文化传承</h3>
                    <ul class="article-list">
                        <li class="article-item">
                            <a href="https://www.thepaper.cn/newsDetail_forward_10103133" target="_blank">
                                <i class="fas fa-chevron-right"></i> 安吉传统农耕技艺的保护与传承
                            </a>
                        </li>
                        <li class="article-item">
                            <a href="http://zj.people.com.cn/n2/2025/1204/c370990-41431906.html" target="_blank">
                                <i class="fas fa-chevron-right"></i> 安吉县研学走廊"农耕文化有机结合
                            </a>
                        </li>
                        <li class="article-item">
                            <a href="http://zj.people.com.cn/n2/2025/0325/c186327-41175053.html" target="_blank">
                                <i class="fas fa-chevron-right"></i> 农耕文化体验园的建设与发展
                            </a>
                        </li>
                        <li class="article-item">
                            <a href="http://zj.people.com.cn/n2/2025/0325/c186327-41175053.html" target="_blank">
                                <i class="fas fa-chevron-right"></i> 安吉农事节庆活动的创新实践
                            </a>
                        </li>
                    </ul>
                </section>
                
                <!-- 栏目3：美丽乡村建设 -->
                <section class="section featured">
                    <h3 class="section-title"><i class="fas fa-home"></i> 美丽乡村建设</h3>
                    <ul class="article-list">
                        <li class="article-item">
                            <a href="http://zj.people.com.cn/n2/2023/1127/c370990-40655741.html" target="_blank">
                                <i class="fas fa-chevron-right"></i> 安吉"中国美丽乡村"建设标准体系
                            </a>
                        </li>
                        <li class="article-item">
                            <a href="http://zj.people.com.cn/n2/2023/1127/c370990-40655741.html" target="_blank">
                                <i class="fas fa-chevron-right"></i> 农村人居环境整治的安吉实践
                            </a>
                        </li>
                        <li class="article-item">
                            <a href="http://zj.people.com.cn/n2/2025/1107/c370990-41404987.html" target="_blank">
                                <i class="fas fa-chevron-right"></i> 安吉乡村垃圾分类与资源化利用
                            </a>
                        </li>
                        <li class="article-item">
                            <a href="http://society.people.com.cn/n1/2025/1214/c1008-40623834.html" target="_blank">
                                <i class="fas fa-chevron-right"></i> 乡村建筑风貌保护与创新设计
                            </a>
                        </li>
                    </ul>
                </section>
                
                <!-- 栏目4：农旅融合发展 -->
                <section class="section">
                    <h3 class="section-title"><i class="fas fa-umbrella-beach"></i> 农旅融合发展</h3>
                    <ul class="article-list">
                        <li class="article-item">
                            <a href="http://zj.people.com.cn/n2/2023/1108/c186327-40633086.html" target="_blank">
                                <i class="fas fa-chevron-right"></i> 安吉乡村旅游提质升级路径
                            </a>
                        </li>
                        <li class="article-item">
                            <a href="https://www.thepaper.cn/newsDetail_forward_31798477" target="_blank">
                                <i class="fas fa-chevron-right"></i> 农家乐与民宿经济的规范发展
                            </a>
                        </li>
                        <li class="article-item">
                            <a href="https://k.sina.com.cn/article_6824573189_196c6b90502002fcig.html" target="_blank">
                                <i class="fas fa-chevron-right"></i> 农耕体验与乡村旅游的深度融合
                            </a>
                        </li>
                        <li class="article-item">
                            <a href="https://finance.sina.com.cn/jjxw/2025-08-08/doc-infkfuvz9156966.shtml" target="_blank">
                                <i class="fas fa-chevron-right"></i> 安吉茶文化主题旅游线路开发
                            </a>
                        </li>
                    </ul>
                </section>
            </div>
            
            <!-- 多媒体区域 -->
            <section class="multimedia">
                <h2><i class="fas fa-photo-video"></i> 安吉农耕与乡村振兴视觉展示</h2>
                <div class="media-container">
                    <!-- 图片展示区 - 替换为用户提供的四张安吉图片 -->
                    <div class="image-gallery">
                        <h3 class="gallery-title"><i class="fas fa-images"></i> 安吉农耕与乡村图集</h3>
                        <div class="image-grid">
                            <div class="image-item">
                                <img src="https://p3-flow-imagex-download-sign.byteimg.com/tos-cn-i-a9rns2rl98/f26f35fba98140139927799b494cdef2.png~tplv-a9rns2rl98-24:720:720.png?rcl=20251229234106826E35FE168394C5DC01&rk3s=8e244e95&rrcfp=8a172a1a&x-expires=1767627666&x-signature=19LiY0uh%2FGSEd0PO8h85pcW6jlg%3D" alt="安吉乡村日落全景">
                            </div>
                            <div class="image-item">
                                <img src="https://p3-flow-imagex-download-sign.byteimg.com/tos-cn-i-a9rns2rl98/34dc0cf53b6c4b74abd6f7c98f3887fd.jpg~tplv-a9rns2rl98-24:720:720.png?rcl=20251229234106826E35FE168394C5DC01&rk3s=8e244e95&rrcfp=8a172a1a&x-expires=1767627666&x-signature=BXYbBTyP0MxYyjYlyF512gLWVMY%3D" alt="安吉生态乡村景观">
                            </div>
                            <div class="image-item">
                                <img src="https://p3-flow-imagex-download-sign.byteimg.com/tos-cn-i-a9rns2rl98/194f1c0d794c41799d3c65e99ec4aea1.png~tplv-a9rns2rl98-24:720:720.png?rcl=20251229234106826E35FE168394C5DC01&rk3s=8e244e95&rrcfp=8a172a1a&x-expires=1767627666&x-signature=FEbl4uW8UFkYYfd4%2FVj5HKaNQBM%3D" alt="安吉传统乡村民居">
                            </div>
                            <div class="image-item">
                                <img src="https://p3-flow-imagex-download-sign.byteimg.com/tos-cn-i-a9rns2rl98/79688ded6236411780f4e53bf49e413e.jpg~tplv-a9rns2rl98-24:720:720.png?rcl=20251229234106826E35FE168394C5DC01&rk3s=8e244e95&rrcfp=8a172a1a&x-expires=1767627666&x-signature=5ugTicKQrdo0i32HbRvhxqUNr10%3D" alt="安吉水乡古村风貌">
                            </div>
                        </div>
                    </div>
                    
                    <!-- 视频展示区 -->
                    <div class="video-gallery">
                        <h3 class="gallery-title"><i class="fas fa-video"></i> 安吉乡村振兴视频报道</h3>
                        <div class="video-item">
                            <img src="https://p3-flow-imagex-download-sign.byteimg.com/tos-cn-i-a9rns2rl98/f26f35fba98140139927799b494cdef2.png~tplv-a9rns2rl98-24:720:720.png?rcl=20251229234106826E35FE168394C5DC01&rk3s=8e244e95&rrcfp=8a172a1a&x-expires=1767627666&x-signature=19LiY0uh%2FGSEd0PO8h85pcW6jlg%3D" alt="安吉农耕视频封面">
                            <div class="video-overlay">
                                <a href="https://www.bilibili.com/video/BV1om4y1q7JK/?spm_id_from=333.337.search-card.all.click&vd_source=028f2946930012ed9316ecad9dfcac4f" target="_blank">
                                    <i class="fas fa-play-circle"></i>
                                </a>
                            </div>
                        </div>
                        <div class="video-caption">
                            <a href="https://www.bilibili.com/video/BV1om4y1q7JK/?spm_id_from=333.337.search-card.all.click&vd_source=028f2946930012ed9316ecad9dfcac4f" target="_blank">"安吉余村的故事"——"两山"理念诞生地的乡村振兴实践</a> - 走进"绿水青山就是金山银山"理念发源地
                        </div>
                        
                        <div class="video-item">
                            <img src="https://p3-flow-imagex-download-sign.byteimg.com/tos-cn-i-a9rns2rl98/34dc0cf53b6c4b74abd6f7c98f3887fd.jpg~tplv-a9rns2rl98-24:720:720.png?rcl=20251229234106826E35FE168394C5DC01&rk3s=8e244e95&rrcfp=8a172a1a&x-expires=1767627666&x-signature=BXYbBTyP0MxYyjYlyF512gLWVMY%3D" alt="安吉乡村视频封面">
                            <div class="video-overlay">
                                <a href="https://www.bilibili.com/video/BV1vY4y1a7iA/?spm_id_from=333.337.search-card.all.click&vd_source=028f2946930012ed9316ecad9dfcac4f" target="_blank">
                                    <i class="fas fa-play-circle"></i>
                                </a>
                            </div>
                        </div>
                        <div class="video-caption">
                            <a href="https://www.bilibili.com/video/BV1vY4y1a7iA/?spm_id_from=333.337.search-card.all.click&vd_source=028f2946930012ed9316ecad9dfcac4f" target="_blank">"数字赋能乡村"——探访安吉智慧农业与数字乡村建设</a> - 看科技如何改变传统农业与乡村治理
                        </div>
                    </div>
                </div>
            </section>
        </div>
    </main>
    
    <!-- 页脚 -->
    <footer class="footer">
        <div class="container">
            <p>安吉乡村振兴专题网站</p>
            <p>主办：盛思伊 | 承办：xxx</p>
            <p>联系电话：0572-XXXXXXX | 邮箱：xxx</p>
            <div class="footer-links">
                <a href="#">关于安吉</a>
                <a href="#">联系我们</a>
                <a href="#">投稿指南</a>
                <a href="#">网站地图</a>
                <a href="#">访问统计</a>
            </div>
        </div>
    </footer>
    
    <script>
        // 添加简单的交互效果
        document.addEventListener('DOMContentLoaded', function() {
            // 为文章链接添加点击效果
            const articleLinks = document.querySelectorAll('.article-item a');
            articleLinks.forEach(link => {
                link.addEventListener('click', function(e) {
                    // 如果链接是外部链接，允许跳转
                    if(this.href && (this.href.includes('people.com.cn') || this.href.includes('thepaper.cn') || this.href.includes('sina.com.cn'))) {
                        console.log('跳转到外部新闻报道：' + this.href);
                        // 允许跳转，不阻止默认行为
                        return;
                    }
                    
                    // 否则，阻止默认行为并显示提示
                    e.preventDefault();
                    const articleTitle = this.textContent.replace('› ', '');
                    alert(`您选择了文章："${articleTitle}"\n\n在实际网站中，这里将跳转到文章详情页面。`);
                });
            });
            
            // 为视频链接添加点击效果
            const videoLinks = document.querySelectorAll('.video-overlay a, .video-caption a');
            videoLinks.forEach(link => {
                link.addEventListener('click', function(e) {
                    if(this.href.includes('example.com')) {
                        e.preventDefault();
                        alert('在实际网站中，这里将播放安吉乡村振兴相关视频。\n\n视频链接：' + this.href);
                    }
                });
            });
            
            // 添加滚动到顶部按钮
            const scrollToTopBtn = document.createElement('button');
            scrollToTopBtn.innerHTML = '<i class="fas fa-arrow-up"></i>';
            scrollToTopBtn.style.position = 'fixed';
            scrollToTopBtn.style.bottom = '25px';
            scrollToTopBtn.style.right = '25px';
            scrollToTopBtn.style.backgroundColor = '#4CAF50';
            scrollToTopBtn.style.color = 'white';
            scrollToTopBtn.style.border = 'none';
            scrollToTopBtn.style.borderRadius = '50%';
            scrollToTopBtn.style.width = '60px';
            scrollToTopBtn.style.height = '60px';
            scrollToTopBtn.style.fontSize = '1.5rem';
            scrollToTopBtn.style.cursor = 'pointer';
            scrollToTopBtn.style.boxShadow = '0 5px 15px rgba(0,0,0,0.3)';
            scrollToTopBtn.style.zIndex = '1000';
            scrollToTopBtn.style.display = 'none';
            scrollToTopBtn.style.transition = 'all 0.3s';
            
            scrollToTopBtn.addEventListener('mouseenter', function() {
                this.style.backgroundColor = '#2e7d32';
                this.style.transform = 'scale(1.1)';
            });
            
            scrollToTopBtn.addEventListener('mouseleave', function() {
                this.style.backgroundColor = '#4CAF50';
                this.style.transform = 'scale(1)';
            });
            
            scrollToTopBtn.addEventListener('click', function() {
                window.scrollTo({
                    top: 0,
                    behavior: 'smooth'
                });
            });
            
            document.body.appendChild(scrollToTopBtn);
            
            window.addEventListener('scroll', function() {
                if (window.scrollY > 300) {
                    scrollToTopBtn.style.display = 'block';
                } else {
                    scrollToTopBtn.style.display = 'none';
                }
            });
            
            // 安吉特色标签悬停效果
            const featureTags = document.querySelectorAll('.feature-tag');
            featureTags.forEach(tag => {
                tag.addEventListener('mouseenter', function() {
                    this.style.backgroundColor = '#1565c0';
                    this.style.color = 'white';
                    this.style.transform = 'translateY(-5px)';
                    this.style.boxShadow = '0 8px 15px rgba(0,0,0,0.15)';
                });
                
                tag.addEventListener('mouseleave', function() {
                    this.style.backgroundColor = 'rgba(227, 242, 253, 0.9)';
                    this.style.color = '#0d47a1';
                    this.style.transform = 'translateY(0)';
                    this.style.boxShadow = 'none';
                });
            });
        });
    </script>
</body>
</html>
