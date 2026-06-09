/* ==========================================================================
   1. CONFIGURAÇÕES GERAIS E RESETS
   ========================================================================== */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    background-color: #f4f7f6;
    color: #333;
    line-height: 1.6;
}

/* ==========================================================================
   2. CABEÇALHO E NAVEGAÇÃO
   ========================================================================== */
header {
    background-color: #ffffff;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    position: sticky;
    top: 0;
    z-index: 1000;
}

.nav-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

.logo {
    font-size: 24px;
    font-weight: bold;
    color: #2c3e50;
    text-decoration: none;
    letter-spacing: 1px;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 25px;
}

.nav-links a {
    text-decoration: none;
    color: #555;
    font-weight: 500;
    transition: color 0.3s ease;
}

.nav-links a:hover {
    color: #3498db;
}

/* ==========================================================================
   3. SECÇÃO HERO (DESTAQUE PRINCIPAL)
   ========================================================================== */
.hero {
    background: linear-gradient(135deg, #3498db, #2c3e50);
    color: white;
    text-align: center;
    padding: 120px 20px;
}

.hero h1 {
    font-size: 48px;
    margin-bottom: 20px;
    font-weight: 700;
}

.hero p {
    font-size: 20px;
    margin-bottom: 35px;
    opacity: 0.9;
    max-width: 600px;
    margin-left: auto;
    margin-right: auto;
}

.btn {
    display: inline-block;
    background-color: #e74c3c;
    color: white;
    padding: 14px 35px;
    text-decoration: none;
    border-radius: 30px;
    font-weight: bold;
    box-shadow: 0 4px 15px rgba(231, 76, 60, 0.3);
    transition: all 0.3s ease;
}

.btn:hover {
    background-color: #c0392b;
    transform: translateY(-3px);
    box-shadow: 0 6px 20px rgba(231, 76, 60, 0.5);
}

/* ==========================================================================
   4. ESTRUTURA DE CONTEÚDO E CARDS
   ========================================================================== */
.container {
    max-width: 1200px;
    margin: 80px auto;
    padding: 0 20px;
}

.section-title {
    text-align: center;
    margin-bottom: 50px;
    font-size: 36px;
    color: #2c3e50;
    position: relative;
}

/* Linha decorativa abaixo do título */
.section-title::after {
    content: '';
    display: block;
    width: 60px;
    height: 4px;
    background-color: #3498db;
    margin: 15px auto 0 auto;
    border-radius: 2px;
}
