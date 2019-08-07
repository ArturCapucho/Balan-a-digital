<p>A Celula de carga nada mais eh que um sensor de forca. Sao capazes de medir deformacoes mecanicas, ou seja, a medida que o corpo sofre uma deformacao a resistencia fixada no corpo dessa celula eh alterada.</p>
<p>Com a alteracao da resistencia &eacute; possivel determinar a deformacao causada pela forca aplicada, essa resistencia eh um circuito ponte de Wheatstone.</p>
<p>Quando R1=R2=R3=R4 a ponte estara em equil&iacute;brio, assim o valor medido pelo voltimetro (Vm) sera de 0V, mas quando variamos o potenciometro R4 a ponte entra em desequilibrio assim o voltimetro acusara um valor de tensao. Obviamente que na celula de carga nao teremos esse potenciometro e sim como ja citado uma resistencia que sera variada de acordo com a deforma&ccedil;&atilde;o do corpo da celula. A celula de carga dispoe de meia ponte, e para completar uma ponte foram utilizadas duas celulas de carga.</p>
<p>O m&oacute;dulo conversor HX711 &eacute; um conversor anal&oacute;gico digital de 24 bits que tamb&eacute;m funciona como um amplificador, assim mantendo o n&iacute;vel de sinal dentro da faixa de opera&ccedil;&atilde;o do conversor.</p>
<p><strong>Materiais Utilizados</strong></p>
<ul>
<li>2 Unidades &ndash;&nbsp;Sensores de Peso 50Kg Celula de Carga</li>
<li>1 Unidade &ndash;&nbsp;M&oacute;dulo Conversor HX711</li>
<li>1 Unidade &ndash; Plataforma 9 cm x 16 cm</li>
<li>1 Unidade &ndash;&nbsp;Arduino Uno</li>
emium-40p-x-20cm-macho-femea.html"
<li>1 Unidade &ndash;&nbsp;Jumpers (Macho &ndash; F&ecirc;mea)</li>
</ul>
<p><strong>Programa&ccedil;&atilde;o</strong></p>
<p>Ser&aacute; necess&aacute;rio desenvolver duas programa&ccedil;&otilde;es, uma para calibrar a balan&ccedil;a e outra para mostrar o peso.</p>
<p>Para calibrar a balan&ccedil;a &eacute; necess&aacute;rio seguir os passos abaixo:</p>
<ul>
<li>Colocar um peso conhecido sobre a plataforma;</li>
<li>Atrav&eacute;s das teclas, ajustar o valor deste peso (voc&ecirc; ver&aacute; o valor do peso pelo monitor serial);</li>
<li>Retirar o peso da plataforma e zerar o peso da balan&ccedil;a pela tecla t ( tara);</li>
<li>Repetir os 3 primeiros passos at&eacute; obter o peso correto</li>
</ul>
<p>Quando sua balan&ccedil;a estiver pesando corretamente, guarde o valor de fator de calibra&ccedil;&atilde;o e utilize &ndash; o no programa seguinte para mostrar o peso correto no monitor serial.</p>
<p>N&atilde;o sabe como funciona a ovula&ccedil;&atilde;o e quando &eacute; a melhor &eacute;poca para fazer amor para conceber? Na verdade, voc&ecirc; pode calcular sua ovula&ccedil;&atilde;o aqui para obter uma estimativa muito precisa. Para calcular sua dias f&eacute;rteis.&nbsp;Basta adicionar a dura&ccedil;&atilde;o do seu ciclo e o &uacute;ltimo per&iacute;odo e ver os resultados em segundos.</p
<p><img src="http://blog.baudaeletronica.com.br/wp-content/uploads/2018/08/Liga%C3%A7%C3%A3o-do-Arduino-M%C3%B3dulo-HX711-e-C%C3%A9lulas-de-Carga.jpg" /></p>
