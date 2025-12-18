<head>
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
<script type="text/x-mathjax-config"> MathJax.Hub.Config({ tex2jax: {inlineMath: [['$', '$']]}, messageStyle: "none" });</script>
<script>
mermaid.initialize({
  flowchart: { htmlLabels: true },
  securityLevel: "loose",
  theme: "base"
});
</script>
<style>
/* --- TITOLI --- */
h1 {
    font-family: 'Georgia', serif;
    color: #34495e;
    border-bottom: 5px solid #3498db;
    padding-bottom: 10px;
    margin-top: 30px;
}
h2 {
    font-family: 'Georgia', serif;
    color: #34495e;
    border-bottom: 3px solid #3498db;
    padding-bottom: 10px;
    margin-top: 25px;
}
h1, h2 {
    /* ... le tue vecchie regole estetiche ... */
    page-break-before: always;
}
h3, h4, h5 {
    font-family: 'Georgia', serif;
    color: #2c3e50;
    margin-top: 20px;
    border-bottom: 2px solid #3498db;
    padding-bottom: 10px;
}
/* --- TESTO E LISTE --- */
p, body {
    font-family: 'Arial', sans-serif;
    font-size: 16px;
    color: #2c3e50;
    line-height: 1.6;
}
ul, ol {
    color: #34495e;
    font-size: 16px;
    line-height: 1.6;
}
/* --- BLOCCHI DI CODICE (quello che abbiamo creato prima) --- */
pre {
    background-color: #f4f6f7;
    border-left: 5px solid #3498db; /* La riga blu a sinistra */
    color: #2c3e50;
    padding: 15px;
    margin: 20px 0;
    font-family: 'Consolas', 'Monaco', 'Courier New', monospace;
    font-size: 0.9em;
    border-radius: 0 5px 5px 0;
    overflow-x: auto;
    box-shadow: 2px 2px 5px rgba(0,0,0,0.1);
}
code {
    font-family: 'Consolas', 'Monaco', 'Courier New', monospace;
}
/* Per le parole evidenziate inline tipo `print()` */
:not(pre) > code {
    background-color: #eaf6ff; /* azzurro molto chiaro, armonico con #3498db */
    color: #0b4f7f; /* testo blu scuro per buon contrasto */
    padding: 2px 6px;
    border-radius: 4px;
    border: 1px solid rgba(11,79,127,0.08);
    box-shadow: inset 0 -1px 0 rgba(255,255,255,0.6);
}
/* --- STILE INDICE (Table of Contents) --- */
/* Il contenitore esterno: simile ai blocchi di codice */
.toc {
    background-color: #f4f6f7;   /* Lo stesso grigio dei blocchi codice */
    border-left: 5px solid #3498db; /* La riga blu a sinistra */
    padding: 15px 20px;
    margin-bottom: 30px;
    border-radius: 0 5px 5px 0;
    box-shadow: 2px 2px 5px rgba(0,0,0,0.05);
}
/* Rimuove i pallini classici della lista per un look più pulito */
.toc ul {
    list-style-type: none; 
    padding-left: 10px;
    margin: 0;
}
/* Gestione dei livelli (indentazione per i sottotitoli) */
.toc ul ul {
    padding-left: 20px;       /* Sposta a destra i sottotitoli */
    border-left: 1px solid #bdc3c7; /* Una linea sottile grigia per guidare l'occhio */
    margin-top: 5px;
    margin-bottom: 5px;
}
/* Stile dei Link */
.toc a {
    text-decoration: none;    /* Toglie la sottolineatura standard */
    color: #2c3e50;           /* Colore scuro standard */
    font-family: 'Arial', sans-serif; /* O il font che preferisci */
    font-size: 0.95em;
    font-weight: 600;         /* Leggermente grassetto */
    transition: color 0.2s;
}
/* Effetto quando passi sopra col mouse */
.toc a:hover {
    color: #3498db;           /* Diventa blu al passaggio */
    text-decoration: underline;
}
/* (Opzionale) Aggiunge un simbolino ">>" prima delle voci principali */
.toc > ul > li > a::before {
    content: "• ";
    color: #3498db;
    font-weight: bold;
    margin-right: 5px;
}
:root {
    --rb-red: #d60000;
    --rb-black: #000000;
    --rb-text-light: #ffffff;
}
</style>
</head>

# Appunti Uni