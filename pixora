<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Pixora - Free online image compression tool. Optimize your images for web with our easy-to-use compression tool.">
    <meta name="keywords" content="image compression, optimize images, reduce file size, web images, Pixora">
    <title>Pixora - Free Online Image Compression Tool</title>
    <style>
        :root {
            --primary-color: #4a6cf7;
            --secondary-color: #6a7c92;
            --accent-color: #ff6b6b;
            --light-color: #f8f9fa;
            --dark-color: #212529;
            --border-radius: 8px;
            --box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            --transition: all 0.3s ease;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f5f7fb;
            color: var(--dark-color);
            line-height: 1.6;
        }

        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        header {
            background-color: white;
            box-shadow: var(--box-shadow);
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
            font-size: 24px;
            font-weight: 700;
            color: var(--primary-color);
        }

        .logo-icon {
            width: 32px;
            height: 32px;
            background-color: var(--primary-color);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 25px;
        }

        nav a {
            text-decoration: none;
            color: var(--secondary-color);
            font-weight: 500;
            transition: var(--transition);
        }

        nav a:hover {
            color: var(--primary-color);
        }

        .hero {
            text-align: center;
            padding: 60px 0;
            background: linear-gradient(135deg, #f5f7fb 0%, #e4e8f0 100%);
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 15px;
            color: var(--dark-color);
        }

        .hero p {
            font-size: 1.2rem;
            color: var(--secondary-color);
            max-width: 700px;
            margin: 0 auto 30px;
        }

        .main-content {
            display: grid;
            grid-template-columns: 1fr 300px;
            gap: 30px;
            padding: 40px 0;
        }

        @media (max-width: 992px) {
            .main-content {
                grid-template-columns: 1fr;
            }
        }

        .compression-tool {
            background-color: white;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            padding: 30px;
        }

        .tool-title {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: var(--dark-color);
        }

        .upload-area {
            border: 2px dashed #d1d8e0;
            border-radius: var(--border-radius);
            padding: 40px 20px;
            text-align: center;
            margin-bottom: 30px;
            transition: var(--transition);
            cursor: pointer;
        }

        .upload-area:hover {
            border-color: var(--primary-color);
        }

        .upload-area i {
            font-size: 48px;
            color: var(--secondary-color);
            margin-bottom: 15px;
        }

        .upload-area p {
            color: var(--secondary-color);
            margin-bottom: 15px;
        }

        .btn {
            background-color: var(--primary-color);
            color: white;
            border: none;
            padding: 12px 24px;
            border-radius: var(--border-radius);
            font-weight: 600;
            cursor: pointer;
            transition: var(--transition);
            display: inline-block;
        }

        .btn:hover {
            background-color: #3a5bd9;
            transform: translateY(-2px);
        }

        .btn-outline {
            background-color: transparent;
            border: 2px solid var(--primary-color);
            color: var(--primary-color);
        }

        .btn-outline:hover {
            background-color: var(--primary-color);
            color: white;
        }

        .compression-controls {
            margin: 30px 0;
        }

        .control-group {
            margin-bottom: 20px;
        }

        .control-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 500;
        }

        .slider-container {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .slider {
            flex: 1;
            -webkit-appearance: none;
            height: 6px;
            border-radius: 3px;
            background: #d1d8e0;
            outline: none;
        }

        .slider::-webkit-slider-thumb {
            -webkit-appearance: none;
            width: 20px;
            height: 20px;
            border-radius: 50%;
            background: var(--primary-color);
            cursor: pointer;
        }

        .slider-value {
            min-width: 40px;
            text-align: center;
            font-weight: 600;
        }

        .preview-section {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-top: 30px;
        }

        @media (max-width: 768px) {
            .preview-section {
                grid-template-columns: 1fr;
            }
        }

        .preview-box {
            border: 1px solid #eaeaea;
            border-radius: var(--border-radius);
            padding: 15px;
            text-align: center;
        }

        .preview-title {
            font-size: 1.1rem;
            margin-bottom: 15px;
            color: var(--secondary-color);
        }

        .preview-image {
            max-width: 100%;
            max-height: 200px;
            border-radius: 4px;
            margin-bottom: 10px;
        }

        .file-info {
            font-size: 0.9rem;
            color: var(--secondary-color);
        }

        .sidebar {
            display: flex;
            flex-direction: column;
            gap: 30px;
        }

        .ad-container {
            background-color: white;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            padding: 20px;
            text-align: center;
            min-height: 250px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .ad-label {
            font-size: 0.8rem;
            color: var(--secondary-color);
            margin-bottom: 10px;
            text-transform: uppercase;
        }

        .ad-placeholder {
            width: 100%;
            height: 200px;
            background-color: #f5f7fb;
            border: 1px dashed #d1d8e0;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--secondary-color);
            font-size: 0.9rem;
        }

        .features {
            background-color: white;
            border-radius: var(--border-radius);
            box-shadow: var(--box-shadow);
            padding: 20px;
        }

        .features h3 {
            margin-bottom: 15px;
            color: var(--dark-color);
        }

        .features ul {
            list-style-position: inside;
            color: var(--secondary-color);
        }

        .features li {
            margin-bottom: 10px;
        }

        footer {
            background-color: var(--dark-color);
            color: white;
            padding: 40px 0 20px;
        }

        .footer-content {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 30px;
            margin-bottom: 30px;
        }

        @media (max-width: 768px) {
            .footer-content {
                grid-template-columns: repeat(2, 1fr);
            }
        }

        @media (max-width: 480px) {
            .footer-content {
                grid-template-columns: 1fr;
            }
        }

        .footer-column h3 {
            font-size: 1.2rem;
            margin-bottom: 20px;
            color: white;
        }

        .footer-column ul {
            list-style: none;
        }

        .footer-column li {
            margin-bottom: 10px;
        }

        .footer-column a {
            color: #b0b7c3;
            text-decoration: none;
            transition: var(--transition);
        }

        .footer-column a:hover {
            color: white;
        }

        .copyright {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid #343a40;
            color: #b0b7c3;
            font-size: 0.9rem;
        }

        .hidden {
            display: none;
        }

        .compression-options {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
            margin-top: 20px;
        }

        @media (max-width: 576px) {
            .compression-options {
                grid-template-columns: 1fr;
            }
        }

        .option-card {
            border: 1px solid #eaeaea;
            border-radius: var(--border-radius);
            padding: 15px;
            text-align: center;
            cursor: pointer;
            transition: var(--transition);
        }

        .option-card:hover {
            border-color: var(--primary-color);
        }

        .option-card.active {
            border-color: var(--primary-color);
            background-color: rgba(74, 108, 247, 0.05);
        }

        .option-icon {
            font-size: 24px;
            margin-bottom: 10px;
            color: var(--primary-color);
        }

        .option-title {
            font-weight: 600;
            margin-bottom: 5px;
        }

        .option-desc {
            font-size: 0.85rem;
            color: var(--secondary-color);
        }

        .action-buttons {
            display: flex;
            gap: 15px;
            margin-top: 30px;
        }

        @media (max-width: 576px) {
            .action-buttons {
                flex-direction: column;
            }
        }

        .btn-full {
            flex: 1;
            text-align: center;
        }

        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            font-size: 24px;
            color: var(--dark-color);
            cursor: pointer;
        }

        @media (max-width: 768px) {
            .mobile-menu-btn {
                display: block;
            }

            nav {
                position: fixed;
                top: 70px;
                left: 0;
                width: 100%;
                background-color: white;
                box-shadow: var(--box-shadow);
                padding: 20px;
                transform: translateY(-100%);
                opacity: 0;
                visibility: hidden;
                transition: var(--transition);
            }

            nav.active {
                transform: translateY(0);
                opacity: 1;
                visibility: visible;
            }

            nav ul {
                flex-direction: column;
                gap: 15px;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="header-content">
                <div class="logo">
                    <div class="logo-icon">P</div>
                    <span>Pixora</span>
                </div>
                <button class="mobile-menu-btn">☰</button>
                <nav>
                    <ul>
                        <li><a href="#">Home</a></li>
                        <li><a href="#">How It Works</a></li>
                        <li><a href="#">Features</a></li>
                        <li><a href="#">Pricing</a></li>
                        <li><a href="#">Blog</a></li>
                        <li><a href="#">Contact</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h1>Optimize Your Images with Pixora</h1>
            <p>Compress and resize your images without losing quality. Fast, secure, and completely free!</p>
            <a href="#compression-tool" class="btn">Start Compressing</a>
        </div>
    </section>

    <div class="container">
        <div class="main-content">
            <div class="compression-tool" id="compression-tool">
                <h2 class="tool-title">Image Compression Tool</h2>
                
                <div class="upload-area" id="uploadArea">
                    <i>📁</i>
                    <p>Drag & Drop your image here</p>
                    <p>or</p>
                    <button class="btn">Select Image</button>
                    <input type="file" id="fileInput" accept="image/*" class="hidden">
                </div>

                <div class="compression-controls">
                    <div class="control-group">
                        <label for="compressionLevel">Compression Level</label>
                        <div class="slider-container">
                            <input type="range" min="0" max="100" value="70" class="slider" id="compressionLevel">
                            <span class="slider-value" id="compressionValue">70%</span>
                        </div>
                    </div>

                    <div class="control-group">
                        <label>Compression Type</label>
                        <div class="compression-options">
                            <div class="option-card active">
                                <div class="option-icon">⚡</div>
                                <div class="option-title">Fast</div>
                                <div class="option-desc">Quick compression with good quality</div>
                            </div>
                            <div class="option-card">
                                <div class="option-icon">⚖</div>
                                <div class="option-title">Balanced</div>
                                <div class="option-desc">Good balance of size and quality</div>
                            </div>
                            <div class="option-card">
                                <div class="option-icon">💎</div>
                                <div class="option-title">Maximum</div>
                                <div class="option-desc">Smallest file size possible</div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="preview-section">
                    <div class="preview-box">
                        <div class="preview-title">Original Image</div>
                        <div class="preview-image-container">
                            <img src="" alt="Original" class="preview-image hidden" id="originalPreview">
                            <div class="file-info" id="originalInfo">No image selected</div>
                        </div>
                    </div>
                    <div class="preview-box">
                        <div class="preview-title">Compressed Image</div>
                        <div class="preview-image-container">
                            <img src="" alt="Compressed" class="preview-image hidden" id="compressedPreview">
                            <div class="file-info" id="compressedInfo">Compressed image will appear here</div>
                        </div>
                    </div>
                </div>

                <div class="action-buttons">
                    <button class="btn btn-full" id="compressBtn">Compress Image</button>
                    <button class="btn btn-outline btn-full" id="downloadBtn" disabled>Download Compressed</button>
                </div>
            </div>

            <div class="sidebar">
                <div class="ad-container">
                    <div>
                        <div class="ad-label">Advertisement</div>
                        <div class="ad-placeholder">
                            Google AdSense Ad Unit
                        </div>
                    </div>
                </div>

                <div class="ad-container">
                    <div>
                        <div class="ad-label">Advertisement</div>
                        <div class="ad-placeholder">
                            Google AdSense Ad Unit
                        </div>
                    </div>
                </div>

                <div class="features">
                    <h3>Why Use Pixora?</h3>
                    <ul>
                        <li>Compress images without quality loss</li>
                        <li>Supports JPG, PNG, WebP formats</li>
                        <li>Fast processing with secure uploads</li>
                        <li>No registration required</li>
                        <li>Completely free to use</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>Pixora</h3>
                    <ul>
                        <li><a href="#">About Us</a></li>
                        <li><a href="#">Our Team</a></li>
                        <li><a href="#">Careers</a></li>
                        <li><a href="#">Press</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Product</h3>
                    <ul>
                        <li><a href="#">Features</a></li>
                        <li><a href="#">Pricing</a></li>
                        <li><a href="#">API</a></li>
                        <li><a href="#">Integrations</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Resources</h3>
                    <ul>
                        <li><a href="#">Documentation</a></li>
                        <li><a href="#">Blog</a></li>
                        <li><a href="#">Tutorials</a></li>
                        <li><a href="#">Support</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Legal</h3>
                    <ul>
                        <li><a href="#">Privacy Policy</a></li>
                        <li><a href="#">Terms of Service</a></li>
                        <li><a href="#">Cookie Policy</a></li>
                        <li><a href="#">GDPR</a></li>
                    </ul>
                </div>
            </div>
            <div class="copyright">
                &copy; 2023 Pixora. All rights reserved.
            </div>
        </div>
    </footer>

    <script>
        // DOM Elements
        const fileInput = document.getElementById('fileInput');
        const uploadArea = document.getElementById('uploadArea');
        const compressionLevel = document.getElementById('compressionLevel');
        const compressionValue = document.getElementById('compressionValue');
        const originalPreview = document.getElementById('originalPreview');
        const compressedPreview = document.getElementById('compressedPreview');
        const originalInfo = document.getElementById('originalInfo');
        const compressedInfo = document.getElementById('compressedInfo');
        const compressBtn = document.getElementById('compressBtn');
        const downloadBtn = document.getElementById('downloadBtn');
        const optionCards = document.querySelectorAll('.option-card');
        const mobileMenuBtn = document.querySelector('.mobile-menu-btn');
        const nav = document.querySelector('nav');

        // Event Listeners
        uploadArea.addEventListener('click', () => fileInput.click());
        uploadArea.addEventListener('dragover', (e) => {
            e.preventDefault();
            uploadArea.style.borderColor = 'var(--primary-color)';
            uploadArea.style.backgroundColor = 'rgba(74, 108, 247, 0.05)';
        });
        uploadArea.addEventListener('dragleave', () => {
            uploadArea.style.borderColor = '#d1d8e0';
            uploadArea.style.backgroundColor = 'transparent';
        });
        uploadArea.addEventListener('drop', (e) => {
            e.preventDefault();
            uploadArea.style.borderColor = '#d1d8e0';
            uploadArea.style.backgroundColor = 'transparent';
            
            if (e.dataTransfer.files.length) {
                handleImageUpload(e.dataTransfer.files[0]);
            }
        });

        fileInput.addEventListener('change', (e) => {
            if (e.target.files.length) {
                handleImageUpload(e.target.files[0]);
            }
        });

        compressionLevel.addEventListener('input', () => {
            compressionValue.textContent = ${compressionLevel.value}%;
        });

        optionCards.forEach(card => {
            card.addEventListener('click', () => {
                optionCards.forEach(c => c.classList.remove('active'));
                card.classList.add('active');
            });
        });

        compressBtn.addEventListener('click', compressImage);
        downloadBtn.addEventListener('click', downloadImage);

        mobileMenuBtn.addEventListener('click', () => {
            nav.classList.toggle('active');
        });

        // Functions
        function handleImageUpload(file) {
            if (!file.type.match('image.*')) {
                alert('Please select an image file.');
                return;
            }

            const reader = new FileReader();
            reader.onload = (e) => {
                originalPreview.src = e.target.result;
                originalPreview.classList.remove('hidden');
                originalInfo.textContent = Size: ${formatFileSize(file.size)} | Type: ${file.type};
                
                // Reset compressed preview
                compressedPreview.src = '';
                compressedPreview.classList.add('hidden');
                compressedInfo.textContent = 'Compressed image will appear here';
                downloadBtn.disabled = true;
            };
            reader.readAsDataURL(file);
        }

        function compressImage() {
            if (!originalPreview.src) {
                alert('Please select an image first.');
                return;
            }

            // In a real implementation, this would use a compression library
            // For demonstration, we'll simulate compression
            compressedPreview.src = originalPreview.src;
            compressedPreview.classList.remove('hidden');
            
            // Calculate simulated file size reduction
            const originalSize = getFileSizeFromDataURL(originalPreview.src);
            const compressionRatio = compressionLevel.value / 100;
            const compressedSize = Math.round(originalSize * (1 - compressionRatio * 0.7));
            
            compressedInfo.textContent = Size: ${formatFileSize(compressedSize)} | Reduction: ${Math.round(compressionRatio * 70)}%;
            downloadBtn.disabled = false;
            
            // Show success message
            alert('Image compressed successfully!');
        }

        function downloadImage() {
            if (!compressedPreview.src) return;
            
            const link = document.createElement('a');
            link.download = 'compressed-image.jpg';
            link.href = compressedPreview.src;
            link.click();
        }

        function formatFileSize(bytes) {
            if (bytes < 1024) return bytes + ' bytes';
            else if (bytes < 1048576) return (bytes / 1024).toFixed(2) + ' KB';
            else return (bytes / 1048576).toFixed(2) + ' MB';
        }

        function getFileSizeFromDataURL(dataURL) {
            // This is a simplified calculation - in reality, dataURL size != file size
            return Math.round((dataURL.length * 3) / 4);
        }

        // Initialize
        compressionValue.textContent = ${compressionLevel.value}%;
    </script>
</body>
</html>
