
        .shape:nth-child(1) {
            width: 80px;
            height: 80px;
            top: 10%;
            left: 10%;
            animation-delay: 0s;
        }

        .shape:nth-child(2) {
            width: 120px;
            height: 120px;
            top: 60%;
            left: 80%;
            animation-delay: 2s;
            animation-duration: 20s;
        }

        .shape:nth-child(3) {
            width: 60px;
            height: 60px;
            top: 80%;
            left: 20%;
            animation-delay: 4s;
            animation-duration: 25s;
        }

        .shape:nth-child(4) {
            width: 100px;
            height: 100px;
            top: 30%;
            left: 70%;
            animation-delay: 6s;
            animation-duration: 18s;
        }

        header {
            text-align: center;
            padding: 30px 0;
            position: relative;
            overflow: hidden;
        }

        .logo {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 20px;
            perspective: 1000px;
        }

        .logo-icon {
            font-size: 50px;
            color: #00b894;
            margin-right: 15px;
            animation: rotate3D 8s infinite linear;
            text-shadow: 0 0 20px rgba(0, 184, 148, 0.7);
        }

        .logo-text {
            font-size: 42px;
            font-weight: 800;
            background: linear-gradient(90deg, #00b894, #00cec9, #81ecec);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 0 20px rgba(0, 184, 148, 0.5);
            animation: glow 3s ease-in-out infinite alternate;
        }

        .tagline {
            font-size: 18px;
            color: #b2bec3;
            margin-bottom: 10px;
            animation: fadeIn 2s;
        }

        .greeting {
            font-size: 28px;
            color: #00cec9;
            margin: 20px 0;
            animation: slideInFromTop 1.5s ease-out;
            text-shadow: 0 0 10px rgba(0, 206, 201, 0.5);
        }

        .battery-status {
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 20px 0;
            padding: 15px;
            background: rgba(0, 0, 0, 0.3);
            border-radius: 15px;
            max-width: 300px;
            margin-left: auto;
            margin-right: auto;
            border: 1px solid rgba(0, 206, 201, 0.3);
            box-shadow: 0 0 15px rgba(0, 206, 201, 0.2);
            animation: pulseGlow 4s infinite;
        }

        .battery-icon {
            font-size: 24px;
            margin-right: 10px;
            color: #00b894;
        }

        .battery-level {
            width: 150px;
            height: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            overflow: hidden;
            position: relative;
        }

        .battery-fill {
            height: 100%;
            width: 0%;
            background: linear-gradient(90deg, #00b894, #00cec9);
            border-radius: 10px;
            transition: width 0.5s;
            position: relative;
            box-shadow: 0 0 10px rgba(0, 184, 148, 0.5);
        }

        .battery-percentage {
            margin-left: 10px;
            font-weight: bold;
            color: #00cec9;
            text-shadow: 0 0 5px rgba(0, 206, 201, 0.5);
        }

        .main-content {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            margin: 30px 0;
        }

        .form-container {
            flex: 1;
            min-width: 300px;
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(15px);
            border-radius: 20px;
            padding: 30px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.5);
            border: 1px solid rgba(255, 255, 255, 0.1);
            animation: slideUp 1s ease-out;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .form-container:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.6);
        }

        .info-panel {
            flex: 1;
            min-width: 300px;
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(15px);
            border-radius: 20px;
            padding: 30px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.5);
            border: 1px solid rgba(255, 255, 255, 0.1);
            animation: slideUp 1.2s ease-out;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .info-panel:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.6);
        }

        h2 {
            color: #00cec9;
            margin-bottom: 20px;
            font-size: 26px;
            border-bottom: 1px solid rgba(0, 206, 201, 0.3);
            padding-bottom: 10px;
            text-shadow: 0 0 10px rgba(0, 206, 201, 0.3);
            animation: textGlow 2s infinite alternate;
        }

        .ban-type-selector {
            display: flex;
            gap: 15px;
            margin-bottom: 25px;
        }

        .ban-option {
            flex: 1;
            text-align: center;
            padding: 15px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            cursor: pointer;
            transition: all 0.3s;
            border: 2px solid transparent;
            animation: fadeIn 1s;
        }

        .ban-option:hover {
            background: rgba(0, 206, 201, 0.2);
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 206, 201, 0.3);
        }

        .ban-option.active {
            background: rgba(0, 206, 201, 0.3);
            border-color: #00cec9;
            box-shadow: 0 0 20px rgba(0, 206, 201, 0.5);
            transform: scale(1.05);
        }

        .ban-option i {
            font-size: 28px;
            margin-bottom: 10px;
            color: #00cec9;
            text-shadow: 0 0 10px rgba(0, 206, 201, 0.5);
        }

        .form-group {
            margin-bottom: 20px;
            animation: slideInFromLeft 0.5s ease-out;
        }

        label {
            display: block;
            margin-bottom: 8px;
            color: #b2bec3;
            font-weight: 500;
        }

        input, textarea, select {
            width: 100%;
            padding: 15px;
            background: rgba(255, 255, 255, 0.1);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 10px;
            color: white;
            font-size: 16px;
            transition: all 0.3s;
        }

        input:focus, textarea:focus, select:focus {
            outline: none;
            border-color: #00cec9;
            box-shadow: 0 0 15px rgba(0, 206, 201, 0.5);
            transform: scale(1.02);
        }

        .submit-btn {
            width: 100%;
            padding: 18px;
            background: linear-gradient(90deg, #00b894, #00cec9);
            border: none;
            border-radius: 10px;
            color: white;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s;
            margin-top: 10px;
            position: relative;
            overflow: hidden;
            z-index: 1;
        }

        .submit-btn::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
            transition: 0.5s;
            z-index: -1;
        }

        .submit-btn:hover::before {
            left: 100%;
        }

        .submit-btn:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 206, 201, 0.4);
        }

        .submit-btn:active {
            transform: translateY(0);
        }

        .info-item {
            margin-bottom: 20px;
            padding: 15px;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 10px;
            border-left: 4px solid #00cec9;
            transition: all 0.3s;
            animation: fadeInUp 0.8s ease-out;
        }

        .info-item:hover {
            transform: translateX(5px);
            background: rgba(255, 255, 255, 0.08);
        }

        .info-item h3 {
            color: #00b894;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
        }

        .info-item h3 i {
            margin-right: 10px;
        }

        .hidden {
            display: none;
        }

        .music-control {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 50%;
            width: 60px;
            height: 60px;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            z-index: 100;
            border: 1px solid rgba(0, 206, 201, 0.5);
            box-shadow: 0 0 15px rgba(0, 206, 201, 0.3);
            animation: pulse 2s infinite;
            transition: all 0.3s;
        }

        .music-control:hover {
            transform: scale(1.1);
            box-shadow: 0 0 20px rgba(0, 206, 201, 0.5);
        }

        .music-control i {
            font-size: 24px;
            color: #00cec9;
        }

        footer {
            text-align: center;
            padding: 30px 0;
            margin-top: 50px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: #b2bec3;
            font-size: 14px;
            animation: fadeIn 2s;
        }

        .copyright {
            margin-top: 10px;
            font-size: 16px;
            color: #00cec9;
            text-shadow: 0 0 5px rgba(0, 206, 201, 0.5);
        }

        .success-message {
            background: rgba(0, 184, 148, 0.2);
            border: 1px solid #00b894;
            border-radius: 15px;
            padding: 25px;
            margin-top: 20px;
            text-align: center;
            animation: bounceIn 1s;
            box-shadow: 0 0 20px rgba(0, 184, 148, 0.3);
        }

        .success-message h3 {
            color: #00b894;
            margin-bottom: 10px;
            text-shadow: 0 0 10px rgba(0, 184, 148, 0.5);
        }

        /* Enhanced Animations */
        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        @keyframes float {
            0% { transform: translate(0, 0) rotate(0deg); }
            50% { transform: translate(20px, 20px) rotate(180deg); }
            100% { transform: translate(0, 0) rotate(360deg); }
        }

        @keyframes rotate3D {
            0% { transform: rotateY(0deg); }
            50% { transform: rotateY(180deg); }
            100% { transform: rotateY(360deg); }
        }

        @keyframes glow {
            from { text-shadow: 0 0 10px rgba(0, 184, 148, 0.5); }
            to { text-shadow: 0 0 20px rgba(0, 184, 148, 0.8), 0 0 30px rgba(0, 184, 148, 0.6); }
        }

        @keyframes textGlow {
            from { text-shadow: 0 0 5px rgba(0, 206, 201, 0.3); }
            to { text-shadow: 0 0 15px rgba(0, 206, 201, 0.7), 0 0 20px rgba(0, 206, 201, 0.5); }
        }

        @keyframes pulseGlow {
            0% { box-shadow: 0 0 5px rgba(0, 206, 201, 0.2); }
            50% { box-shadow: 0 0 20px rgba(0, 206, 201, 0.5); }
            100% { box-shadow: 0 0 5px rgba(0, 206, 201, 0.2); }
        }

        @keyframes slideInFromTop {
            from { transform: translateY(-50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        @keyframes slideInFromLeft {
            from { transform: translateX(-30px); opacity: 0; }
            to { transform: translateX(0); opacity: 1; }
        }

        @keyframes fadeInUp {
            from { transform: translateY(20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        @keyframes bounceIn {
            0% { transform: scale(0.5); opacity: 0; }
            50% { transform: scale(1.05); opacity: 1; }
            100% { transform: scale(1); }
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideUp {
            from { transform: translateY(50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        /* Responsive */
        @media (max-width: 768px) {
            .main-content {
                flex-direction: column;
            }
            
            .ban-type-selector {
                flex-direction: column;
            }
            
            .logo-text {
                font-size: 32px;
            }
            
            .logo-icon {
                font-size: 40px;
            }
        }
    </style>
</head>
<body>
    <!-- Animated Background Elements -->
    <div class="floating-shapes">
        <div class="shape"></div>
        <div class="shape"></div>
        <div class="shape"></div>
        <div class="shape"></div>
    </div>
    
    <!-- T20_STARBOY Watermark -->
    <div class="watermark">T20_STARBOY</div>

    <div class="container">
        <header>
            <div class="logo">
                <div class="logo-icon">
                    <i class="fas fa-robot"></i>
                </div>
                <div class="logo-text">T20 CLASSIC TECH</div>
            </div>
            <div class="tagline">Professional WhatsApp Unban Services</div>
            <div class="greeting" id="greeting">Good Morning!</div>
            
            <div class="battery-status">
                <div class="battery-icon">
                    <i class="fas fa-battery-quarter"></i>
                </div>
                <div class="battery-level">
                    <div class="battery-fill" id="batteryFill"></div>
                </div>
                <div class="battery-percentage" id="batteryPercentage">25%</div>
            </div>
        </header>

        <div class="main-content">
            <div class="form-container">
                <h2><i class="fas fa-unlock-alt"></i> Unban Request Form</h2>
                
                <div class="ban-type-selector">
                    <div class="ban-option active" data-type="temporary">
                        <i class="fas fa-clock"></i>
                        <div>Temporary Ban</div>
                    </div>
                    <div class="ban-option" data-type="permanent">
                        <i class="fas fa-ban"></i>
                        <div>Permanent Ban</div>
                    </div>
                </div>
                
                <form id="unbanForm">
                    <div class="form-group">
                        <label for="fullName"><i class="fas fa-user"></i> Full Name</label>
                        <input type="text" id="fullName" placeholder="Enter your full name" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="phoneNumber"><i class="fas fa-phone"></i> Banned Phone Number</label>
                        <input type="text" id="phoneNumber" placeholder="Enter your banned WhatsApp number" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="email"><i class="fas fa-envelope"></i> Your Email Address</label>
                        <input type="email" id="email" placeholder="Enter your email for response" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="banReason"><i class="fas fa-question-circle"></i> Reason for Ban (if known)</label>
                        <select id="banReason">
                            <option value="unknown">I don't know the reason</option>
                            <option value="spam">Suspected spam activity</option>
                            <option value="mods">Using modified WhatsApp version</option>
                            <option value="behavior">Violation of terms of service</option>
                            <option value="other">Other reason</option>
                        </select>
                    </div>
                    
                    <div class="form-group">
                        <label for="message"><i class="fas fa-comment"></i> Additional Details</label>
                        <textarea id="message" rows="4" placeholder="Provide any additional information that might help your case..."></textarea>
                    </div>
                    
                    <button type="submit" class="submit-btn">
                        <i class="fas fa-paper-plane"></i> Continue Unban Process
                    </button>
                </form>
                
                <div id="successMessage" class="success-message hidden">
                    <h3><i class="fas fa-check-circle"></i> Request Generated Successfully!</h3>
                    <p>Your unban request has been prepared. Click the button below to open your email client and send the request to WhatsApp support.</p>
                    <button id="sendEmailBtn" class="submit-btn" style="margin-top: 15px;">
                        <i class="fas fa-envelope"></i> Send Email to WhatsApp Support
                    </button>
                </div>
            </div>
            
            <div class="info-panel">
                <h2><i class="fas fa-info-circle"></i> Important Information</h2>
                
                <div class="info-item">
                    <h3><i class="fas fa-shield-alt"></i> Why Accounts Get Banned</h3>
                    <p>WhatsApp may ban accounts for violations of their Terms of Service, such as spam, abusive behavior, or using unauthorized mods.</p>
                </div>
                
                <div class="info-item">
                    <h3><i class="fas fa-clock"></i> Temporary vs Permanent Bans</h3>
                    <p>Temporary bans usually last 24-72 hours. Permanent bans require a formal appeal to WhatsApp support.</p>
                </div>
                
                <div class="info-item">
                    <h3><i class="fas fa-envelope-open-text"></i> How Our Service Works</h3>
                    <p>We generate a professionally crafted email that you can send to WhatsApp support, increasing your chances of a successful unban.</p>
                </div>
                
                <div class="info-item">
                    <h3><i class="fas fa-history"></i> Response Time</h3>
                    <p>WhatsApp typically responds to unban requests within 3-7 business days. Be patient and avoid sending multiple requests.</p>
                </div>
            </div>
        </div>
        
        <footer>
            <p>T20 CLASSIC TECH - Professional Tech Solutions</p>
            <div class="copyright">T20-CLASSIC 2025 © All Rights Reserved</div>
        </footer>
    </div>
    
    <div class="music-control" id="musicControl">
        <i class="fas fa-volume-up"></i>
    </div>
    
    <audio id="backgroundMusic" loop>
        <source src="https://files.catbox.moe/e3gniv.mp3" type="audio/mpeg">
    </audio>

    <script>
        // Set greeting based on time of day
        function setGreeting() {
            const hour = new Date().getHours();
            const greeting = document.getElementById('greeting');
            
            if (hour < 12) {
                greeting.textContent = 'Good Morning!';
            } else if (hour < 18) {
                greeting.textContent = 'Good Afternoon!';
            } else {
                greeting.textContent = 'Good Evening!';
            }
        }
        
        // Battery charging simulation
        function simulateBattery() {
            const batteryFill = document.getElementById('batteryFill');
            const batteryPercentage = document.getElementById('batteryPercentage');
            const batteryIcon = document.querySelector('.battery-icon i');
            
            let level = 25;
            const interval = setInterval(() => {
                level += 1;
                batteryFill.style.width = level + '%';
                batteryPercentage.textContent = level + '%';
                
                // Change battery icon based on level
                if (level < 20) {
                    batteryIcon.className = 'fas fa-battery-empty';
                } else if (level < 50) {
                    batteryIcon.className = 'fas fa-battery-quarter';
                } else if (level < 80) {
                    batteryIcon.className = 'fas fa-battery-half';
                } else if (level < 100) {
                    batteryIcon.className = 'fas fa-battery-three-quarters';
                } else {
                    batteryIcon.className = 'fas fa-battery-full';
                    clearInterval(interval);
                }
            }, 200);
        }
        
        // Ban type selector
        document.querySelectorAll('.ban-option').forEach(option => {
            option.addEventListener('click', function() {
                document.querySelectorAll('.ban-option').forEach(opt => {
                    opt.classList.remove('active');
                });
                this.classList.add('active');
            });
        });
        
        // Form submission
        document.getElementById('unbanForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const banType = document.querySelector('.ban-option.active').getAttribute('data-type');
            const fullName = document.getElementById('fullName').value;
            const phoneNumber = document.getElementById('phoneNumber').value;
            const email = document.getElementById('email').value;
            const banReason = document.getElementById('banReason').value;
            const message = document.getElementById('message').value;
            
            // Store the data for email generation
            sessionStorage.setItem('unbanData', JSON.stringify({
                banType, fullName, phoneNumber, email, banReason, message
            }));
            
            // Show success message
            document.getElementById('successMessage').classList.remove('hidden');
            
            // Scroll to success message
            document.getElementById('successMessage').scrollIntoView({ behavior: 'smooth' });
        });
        
        // Send email button
        document.getElementById('sendEmailBtn').addEventListener('click', function() {
            const unbanData = JSON.parse(sessionStorage.getItem('unbanData'));
            
            if (!unbanData) {
                alert('No unban data found. Please fill out the form first.');
                return;
            }
            
            const { banType, fullName, phoneNumber, email, banReason, message } = unbanData;
            
            let emailSubject, emailBody;
            
            if (banType === 'permanent') {
                emailSubject = `Request to Unban Permanently Banned WhatsApp Account - ${fullName}`;
            } else {
                emailSubject = `Request to Review Temporarily Banned WhatsApp Account - ${fullName}`;
            }
            
            // Create a very polite email body
            emailBody = `Dear WhatsApp Support Team,

I hope this message finds you well.

I am writing to kindly request your assistance with my WhatsApp account, which has been ${banType === 'permanent' ? 'permanently banned' : 'temporarily restricted'}.

Here are my account details:
- Full Name: ${fullName}
- Banned Phone Number: ${phoneNumber}
- My Email Address: ${email}
- Suspected Reason for Ban: ${document.getElementById('banReason').options[document.getElementById('banReason').selectedIndex].text}

${message ? `Additional Information: ${message}\n\n` : ''}
I want to assure you that I value WhatsApp as an important communication tool and have always strived to use it in accordance with your Terms of Service. If I have unintentionally violated any rules, I sincerely apologize.

I would be extremely grateful if you could review my case and consider ${banType === 'permanent' ? 'reinstating my account' : 'lifting the temporary restriction'}.

Thank you very much for your time and consideration. I look forward to your positive response.

Sincerely,
${fullName}`;

            // Create mailto link
            const mailtoLink = `mailto:support@whatsapp.com?subject=${encodeURIComponent(emailSubject)}&body=${encodeURIComponent(emailBody)}`;
            
            // Open email client
            window.location.href = mailtoLink;
        });
        
        // Background music control
        const musicControl = document.getElementById('musicControl');
        const backgroundMusic = document.getElementById('backgroundMusic');
        let musicPlaying = false;
        
        musicControl.addEventListener('click', function() {
            if (musicPlaying) {
                backgroundMusic.pause();
                musicControl.innerHTML = '<i class="fas fa-volume-mute"></i>';
                musicPlaying = false;
            } else {
                backgroundMusic.play().catch(e => {
                    alert('Please interact with the page first to enable audio playback.');
                });
                musicControl.innerHTML = '<i class="fas fa-volume-up"></i>';
                musicPlaying = true;
            }
        });
        
        // Enable audio on first user interaction
        document.addEventListener('click', function enableAudio() {
            backgroundMusic.play().then(() => {
                backgroundMusic.pause();
                musicPlaying = false;
            }).catch(e => {
                // Audio will be enabled on next user interaction
            });
            document.removeEventListener('click', enableAudio);
        });
        
        // Initialize functions when page loads
        window.onload = function() {
            setGreeting();
            simulateBattery();
        };
    </script>
</body>
</html>
