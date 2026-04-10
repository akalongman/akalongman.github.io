---
layout: null
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Avtandil Kikabidze | Principal Software Architect</title>
    <meta name="title" content="Avtandil Kikabidze | Principal Software Architect">
    <meta name="description" content="Elite Senior Software Architect with 15 years of experience engineering high-availability, enterprise-grade systems and zero-downtime DevOps pipelines.">
    
    <meta property="og:type" content="website">
    <meta property="og:title" content="Avtandil Kikabidze | Principal Software Architect">
    <meta property="og:description" content="Elite Senior Software Architect with 15 years of experience engineering high-availability, enterprise-grade systems.">
    
    <link rel="icon" type="image/png" href="/favicon.png">

    <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');

    body {
        font-family: 'Inter', sans-serif;
        line-height: 1.6;
        color: #374151;
        background-color: #f3f4f6;
        margin: 0;
        padding: 3rem 1rem;
    }

    main {
        max-width: 850px;
        margin: 0 auto;
        background: #ffffff;
        padding: 4rem 5rem;
        border-radius: 12px;
        box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 8px 10px -6px rgba(0, 0, 0, 0.1);
    }

    h1 {
        font-size: 2.5rem;
        font-weight: 700;
        color: #111827;
        margin-bottom: 0.2rem;
        text-align: center;
        letter-spacing: -0.025em;
    }

    h2 {
        font-size: 1.5rem;
        font-weight: 600;
        color: #111827;
        border-bottom: 2px solid #e5e7eb;
        padding-bottom: 0.5rem;
        margin-top: 2.5rem;
        margin-bottom: 1rem;
    }

    p, li {
        font-size: 1.05rem;
        color: #4b5563;
        margin-bottom: 0.75rem;
    }

    strong {
        color: #111827;
        font-weight: 600;
    }

    a {
        color: #2563eb;
        text-decoration: none;
        font-weight: 600;
    }

    a:hover {
        text-decoration: underline;
        color: #1d4ed8;
    }

    ul {
        padding-left: 1.5rem;
    }

    li {
        margin-bottom: 0.5rem;
    }

    p:first-of-type {
        text-align: center;
        font-size: 1.1rem;
        margin-bottom: 2.5rem;
    }

    @media (max-width: 600px) {
        main {
            padding: 2rem 1.5rem;
        }
    }
    </style>
</head>
<body>

<main markdown="1">

{% capture cv %}{% include cv.md %}{% endcapture %}
{{ cv | markdownify }}

</main>

</body>
</html>
