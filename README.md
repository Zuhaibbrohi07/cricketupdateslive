<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content=
  "width=device-width, initial-scale=1.0">
  <title>Login to View Live Cricket & Updates</title>
  <style>
    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      background: linear-gradient(135deg, #0f172a, #1e293b);
      color: white;
      text-align: center;
    }

    /* --- LOGIN GATE STYLES --- */
    #login-gate {
        max-width: 400px;
        margin: 50px auto;
        padding: 40px 20px;
        border-radius: 20px;
        background: linear-gradient(135deg, #1e293b, #0f172a);
        box-shadow: 0 0 25px rgba(255, 255, 255, 0.2);
    }
    #login-gate h1 {
        color: #38bdf8;
        font-size: 2rem;
        margin-bottom: 30px;
    }
    .form-group {
        margin-bottom: 15px;
        text-align: left;
    }
    .form-group label {
        display: block;
        margin-bottom: 5px;
        color: #94a3b8;
        font-size: 0.9rem;
    }
    .form-group input {
        width: 100%;
        padding: 12px;
        border: 2px solid #334155;
        border-radius: 10px;
        background-color: #0f172a;
        color: white;
        font-size: 1rem;
        box-sizing: border-box;
    }
    .form-toggle {
        color: #38bdf8;
        cursor: pointer;
        font-size: 0.9rem;
        margin-top: 20px;
    }
    
    /* --- MAIN CONTENT STYLES (Existing) --- */
    .hidden {
        display: none; /* New class to hide main content initially */
    }

    .video-container {
      width: 100%;
      max-width: 900px;
      margin: 20px auto;
      padding: 10px;
      border-radius: 20px;
      background: linear-gradient(135deg, #1e293b, #0f172a);
      box-shadow: 0 0 25px rgba(56, 189, 248, 0.6);
    }

    video {
      width: 100%;
      height: 500px;
      border-radius: 15px;
      outline: none;
      background: black;
    }

    h2 {
      margin-top: 25px;
      font-size: 1.6rem;
      font-weight: bold;
      color: #38bdf8;
      text-shadow: 0 0 10px rgba(56, 189, 248, 0.8);
    }

    .btn {
      display: inline-block;
      padding: 15px 30px;
      margin: 12px;
      font-size: 1.2rem;
      border-radius: 40px;
      text-decoration: none;
      font-weight: bold;
      color: white;
      position: relative;
      overflow: hidden;
      backdrop-filter: blur(10px);
      transition: all 0.3s ease;
      cursor: pointer; /* Added for button/link-like feel */
    }

    .btn::before {
      content: "";
      position: absolute;
      top: -50%;
      left: -50%;
      width: 200%;
      height: 200%;
      background: radial-gradient(circle, rgba(255,255,255,0.2), transparent 70%);
      transform: rotate(25deg);
      transition: opacity 0.3s ease;
      opacity: 0;
    }

    .btn:hover::before {
      opacity: 1;
    }

    .whatsapp {
      background: rgba(34, 197, 94, 0.2);
      border: 2px solid #22c55e;
      box-shadow: 0 0 20px rgba(34, 197, 94, 0.7);
    }
    .primary-btn {
        background: rgba(56, 189, 248, 0.2);
        border: 2px solid #38bdf8;
        box-shadow: 0 0 20px rgba(56, 189, 248, 0.7);
    }

    .instagram {
      background: rgba(236, 72, 153, 0.2);
      border: 2px solid #ec4899;
      box-shadow: 0 0 20px rgba(236, 72, 153, 0.7);
    }

    footer {
      margin-top: 25px;
      font-size: 0.95rem;
      color: #94a3b8;
      padding-bottom: 25px;
      text-shadow: 0 0 8px rgba(148,163,184,0.6);
     }
  </style>
</head>
<body>

<div id="login-gate">
    <h1 id="form-title">Register</h1>
    
    <div id="register-form">
        <div class="form-group">
            <label for="reg-username">Username</label>
            <input type="text" id="reg-username" name="username" placeholder="Enter a username">
        </div>
        <div class="form-group">
            <label for="reg-password
