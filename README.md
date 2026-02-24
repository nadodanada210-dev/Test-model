<style>
    :root {
        --gold: #d4af37;
        --dark-gold: #b8860b;
    }

    body {
        margin: 0;
        padding: 0;
        /* خلفية مغربية راقية (زخرفة مذهبة) */
        background: linear-gradient(rgba(255, 250, 240, 0.8), rgba(255, 250, 240, 0.8)), 
                    url('https://images.unsplash.com/photo-1582192732881-43b74633ac05?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
        background-size: cover;
        background-attachment: fixed;
        font-family: 'Amiri', serif;
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 100vh;
        overflow-x: hidden;
    }

    /* تأثير القلوب باللون الأحمر والذهبي */
    .heart {
        position: absolute;
        color: var(--gold); /* تقدري تبدليها لـ red إلا بغيتي قلوب حمراء */
        font-size: 20px;
        animation: fall linear infinite;
        text-shadow: 0 0 5px rgba(0,0,0,0.1);
    }

    /* الإطار الملكي */
    .container {
        position: relative;
        width: 85%;
        max-width: 450px;
        background: rgba(255, 255, 255, 0.95);
        padding: 50px 25px;
        text-align: center;
        border: 2px solid var(--gold);
        outline: 8px double var(--gold);
        outline-offset: -15px;
        border-radius: 5px;
        box-shadow: 0 20px 50px rgba(0,0,0,0.3);
        z-index: 1;
    }

    /* باقي الستايلات كتبقى كما هي */
</style>
