# Estilos-css-em-arquivos-separados-formata-es-com-folhas-de-estilo-css

@charset "UTF8";
body {
    background-image: url("fundo.jpg.jpg");
}
p {
    text-align: justify;
    text-indent: 50px;        
}

/* Formatação de imagem com legenda*/

figure.foto-legenda {
    position: relative;
    border: 8px solid white;
    box-shadow: 1px 1px 4px black;
    
}


figure.foto-legenda img {
    width: 100%;
    height: 100%
}

figure.foto-legenda figcaption{
    opacity: 0;
    position: absolute;
    top: 0px;
    background-color rgba(0,0,0,.4);
    color: white;
    width: 100%;
    height: 100%;
    padding: 10px;
    box-sizing: border-box;
    transition: 1s;

}

figure.foto-legenda:hover figcaption {
    opacity: 1;


}
