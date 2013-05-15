    BattleSpace is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    BattleSpace is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.
  
    You should have received a copy of the GNU General Public License
    along with BattleSpace.  If not, see <http://www.gnu.org/licenses/>.



    BattleSpace es software libre: puede ser redistribuído y/o modificado
    bajo los términos de la GNU General Public License, publicada por la
    Free Software Foundation, ya sea la versión 3 de la Licencia, o, (a
    discreción) cualquier versión posterior.

    BattleSpace es distribuída con la esperanza de que sea útil, pero 
    SIN GARANTÍA ALGUNA; ni siquiera la garantía implícita de MERCANTA-
    BILIDAD o APTITUD PARA UN FIN ESPECÍFICO. Para más detalles, ver la
    GNU General Public License.

    Debe haber recibido una copia de la GNU General Public License junto
    con BattleSpace. De no ser así, vea <http://www.gnu.org/licenses/>.


.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.

Autor: Manuel Olguín

BattleSpace es un juego escrito en Java, implementando las librerías Slick2D
y LWJGL. Fue creado para una tarea de un curso de Computación Gráfica de la 
Universidad de Chile.

Para compilar el juego es necesario bajar el código fuente presente en esta
página, y luego configurar Eclipse o BlueJ para que utilicen las librerías
incluídas en la carpeta "lib". Cómo hacer esto está detallado en:
<http://www.slick2d.org/wiki/index.php/Setting_up_Slick2D_with-Eclipse>

En este repositorio también existen ejecutables de la versión más reciente 
para Linux y Windows.


INSTRUCCIONES DE JUEGO:

Es un juego de dos jugadores. La finalidad del juego es, a través de el arma
propia de cada nave, destruir la nave enemiga; el problema es que las naves
son invulnerables por delante, y la única manera de causar daño a la nave 
enemiga es disparándole en la parte posterior.

Cada nave también tiene asociado un contador de combustible. Si este llega a 
cero, la nave no podrá seguir moviéndose. En el mapa aparecerán oportunamente
contenedores de combustible para rellenar los estanques de las naves. También
apareceran vidas adicionales y powerups para aumentar la potencia del arma
de cada nave.

En el mapa también existen asteroides que dañan las naves al chocar con ellas.

CONTROLES:

FLECHA ARRIBA:	Rojo acelera.
FLECHA ABAJO:	Rojo retrocede.
FLECHA IZQ:	Rojo gira izquierda.
FLECHA DER:	Rojo gira derecha.
CONTROL DER:	Rojo dispara.

W:		Azul acelera.
S:		Azul retrocede.
A:		Azul gira izquierda.
D.		Azul gira derecha.
CONTROL IZQ:	Azul dispara.

P:		Pausa	 

