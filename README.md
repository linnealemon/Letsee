<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Opinion Matters - Tiago Pires Surf School</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        /* RESET & BASE */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body {
            background-color: #F8F1DE; /* Brand Cream */
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        /* FLYER CONTAINER */
        .flyer-container {
            width: 100%;
            max-width: 500px;
            background-color: #79A09E; /* Brand Teal */
            border: 4px solid #1C1C1C;
            box-shadow: 8px 8px 0px #1C1C1C; /* Reto shadow effect */
            display: flex;
            flex-direction: column;
            overflow: hidden;
        }

        /* HERO CARD (Text Area) */
        .content-card {
            background-color: rgba(248, 241, 222, 0.15); /* Soft overlay */
            border: 2px solid #F8F1DE;
            margin: 30px 30px 20px 30px;
            padding: 30px 20px;
            text-align: center;
            color: #F8F1DE;
        }

        .content-card h1 {
            font-family: 'Montserrat', sans-serif;
            font-weight: 900;
            font-size: 24px;
            letter-spacing: 1px;
            text-transform: uppercase;
            margin-bottom: 20px;
            color: #F8F1DE;
        }

        .content-card p {
            font-size: 15px;
            line-height: 1.6;
            font-weight: 500;
            max-width: 320px;
            margin: 0 auto;
        }

        .content-card p.separator {
            margin: 15px auto;
            font-weight: bold;
            opacity: 0.9;
        }

        /* QR CODE HOLDER */
        .qr-section {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 10px 30px 30px 30px;
            text-align: center;
        }

        .qr-placeholder {
            width: 180px;
            height: 180px;
            background-color: #F8F1DE;
            border: 3px solid #1C1C1C;
            box-shadow: 5px 5px 0px #1C1C1C;
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 15px;
            position: relative;
        }

        /* This is where your QR image will actually load */
        .qr-placeholder img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            display: block;
        }

        /* Helper instructions below QR */
        .scan-instruction {
            font-family: 'Montserrat', sans-serif;
            font-size: 11px;
            font-weight: 700;
            letter-spacing: 1.5px;
            color: #1C1C1C;
            text-transform: uppercase;
            margin-top: 5px;
        }

        /* BRAND FOOTER BAR */
        .footer-bar {
            background-color: #F8F1DE;
            border-top: 4px solid #1C1C1C;
            padding: 20px;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .logo-text {
            font-family: 'Montserrat', sans-serif;
            font-weight: 900;
            font-size: 20px;
            letter-spacing: 1px;
            color: #1C1C1C;
            text-transform: uppercase;
        }

        .logo-text span {
            font-weight: 400;
            color: #79A09E;
        }
    </style>
</head>
<body>

    <div class="flyer-container">
        
        <div class="content-card">
            <h1>Your opinion matters to us</h1>
            <p>We would love to hear your thoughts in a more detailed questionnaire.</p>
            <p class="separator">—</p>
            <p>If you have a moment, please scan the code below to send us your answers.</p>
        </div>

        <div class="qr-section">
            <div class="qr-placeholder">
                <img src="your_qr_code_image.png" alt="Scan to Review" onerror="this.style.display='none';">
                <span style="position: absolute; font-family: sans-serif; font-size: 12px; font-weight: bold; color: #1C1C1C;">[ INSERT QR HERE ]</span>
            </div>
            <div class="scan-instruction">
                📷 Scan with your phone camera
            </div>
        </div>

        <div class="footer-bar">
            <div class="logo-text">TIAGO PIRES <span>SURF SCHOOL</span></div>
        </div>

    </div>

</body>
</html>
