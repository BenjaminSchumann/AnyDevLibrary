---
layout: default
title: Welcome to AnyDevLibrary Documentation
---

<div class="container">
    <h1>Welcome to AnyDevLibrary Documentation!</h1>
    <p>Explore the comprehensive documentation for the AnyDevLibrary, including detailed API references and custom guides.</p>

    <div class="links-container">
        <a href="./javadoc/index.html" class="link-button">Go to Javadoc API Reference</a>
        <a href="./getting-started.html" class="link-button">Read Our Custom Guides</a>
        <a href="https://benjamin-schumann.com" target="_blank" class="link-button">Visit Benjamin Schumann's Homepage</a>
    </div>
</div>

<style>
/* This CSS can be moved to a separate file for larger projects,
   but for a simple setup, keeping it here works. */
body {
    font-family: 'Inter', sans-serif; /* Using Inter font as per guidelines */
    line-height: 1.6;
    margin: 0;
    padding: 20px;
    background-color: #f4f7f6;
    color: #333;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}
.container {
    background-color: #ffffff;
    padding: 40px;
    border-radius: 12px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    max-width: 800px;
    width: 100%;
    text-align: center;
}
h1 {
    color: #2c3e50;
    margin-bottom: 25px;
    font-size: 2.5em;
}
p {
    margin-bottom: 30px;
    font-size: 1.1em;
    color: #555;
}
.links-container {
    display: flex;
    flex-direction: column;
    gap: 15px;
    margin-top: 30px;
}
.link-button {
    display: inline-block;
    padding: 15px 30px;
    background-color: #3498db;
    color: white;
    text-decoration: none;
    border-radius: 8px;
    transition: background-color 0.3s ease, transform 0.2s ease;
    font-weight: bold;
    font-size: 1.1em;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
}
.link-button:hover {
    background-color: #2980b9;
    transform: translateY(-2px);
}
/* Responsive adjustments */
@media (max-width: 600px) {
    .container {
        padding: 20px;
        margin: 10px;
    }
    h1 {
        font-size: 1.8em;
    }
    p {
        font-size: 1em;
    }
    .link-button {
        padding: 12px 20px;
        font-size: 1em;
    }
}
</style>
