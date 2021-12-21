# INFORME TAERA 4

**3. EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS**

***CAPITULO N° 7***

Identificación de relaciones en serie-paralelo

1. Visualice y trace las siguientes combinaciones en serie-paralelo:
(a) R1 en serie con la combinación en paralelo de R2 y R3
(b) R1 en paralelo con la combinación en serie de R2 y R3
(c) R1 en paralelo con una rama que contiene R2 en serie con una combinación en paralelo de otros cuatro resistores

(a)
![image](https://user-images.githubusercontent.com/94182617/146943558-41925a08-5d2b-4d78-9821-55d1180a94e9.png)

(b) 
![image](https://user-images.githubusercontent.com/94182617/146943582-8cbd382e-17a3-4ede-a086-730f285d0652.png)

(c)
![image](https://user-images.githubusercontent.com/94182617/146943594-ef61bcf9-5216-40ab-8265-098178037673.png)


3. En cada circuito de la figura, identifique las relaciones en serie-paralelo de los resistores vistas desde la fuente.

![image](https://user-images.githubusercontent.com/94182617/146943620-30777bdf-810c-4525-9d63-9e3a7a8d1d1b.png)

(a) R1 y R4 están en serie con la combinación en paralelo de R2 y R3.

(b) R1 está en serie con la combinación en paralelo de R2, R3 y R4.

(c) La combinación en paralelo de R2 y R3 está en serie con la combinación en paralelo de R4 y R5. Todo esto está en paralelo con R1.


5. Trace el diagrama esquemático de la configuración de la tarjeta de circuito impreso mostrada en la figura indicando valores de resistor, e identifique las relaciones en serie-paralelo.

![image](https://user-images.githubusercontent.com/94182617/146943672-b72ed9dd-9b9e-4de0-81af-bc855f0c29c5.png)

![image](https://user-images.githubusercontent.com/94182617/146943692-674c3926-481c-4f32-b3d3-622b582afe53.png)

La combinación en paralelo de R1 en serie con R3 y R2 en serie con R4, está en serie con las resistencias en serie R10, R11, R9, R8, R7, R6 y R5.

7. Configure una tarjeta de circuito impreso para el circuito de la figura. La batería tiene que conectarse externa a la tarjeta.

![image](https://user-images.githubusercontent.com/94182617/146943762-0febcd3d-8110-441d-97ec-bb045de011cb.png)

![image](https://user-images.githubusercontent.com/94182617/146943775-5a235d81-ed10-455d-bb99-e65adc284035.png)

Análisis de circuitos resistivos en serie-paralelo

9. Para cada uno de los circuitos mostrados en la figura, determine la resistencia total presentada a la fuente.

![image](https://user-images.githubusercontent.com/94182617/146943829-a72160d3-c433-465f-87f7-ee1d9644c7e9.png)

R2||R3 = R2/n
R2||R3 = 100/2
R2||R3 = 50 ohm

R1+R2||R3+R4 = R1 + R2||R3 + R4
R1+R2||R3+R4 = 56 + 50 + 27
RT = 133 ohm

(b)
R2||R3||R4 = 1/(1/R2 + 1/R3 + 1/R4)
R2||R3||R4 = 1/(1/680 + 1/330 + 1/180)
R2||R3||R4 = 99.44 ohm

R1+R2||R3||R4 = 680 + 99.44
RT = 779.44 ohm

(c)
R2||R3 = R2*R3/R2+R3
R2||R3 = (6.2)(3.3)/6.2 + 3.3
R2||R3 = 2.15 kohm

R4||R5 = R4*R5/R4+R5
R4||R5 = (10)(5.6)/(10 + 5.6)
R4||R5 = 3.59 kohm

R4||R5 + R2||R3 = 2.15 + 3.59
R4||R5 + R2||R3 = 5.74kohm

RT = R1||( R4||R5 + R2||R3)
RT = 1/(1/R1 + 1/(R4||R5 + R2||R3)
RT = 1/(1/1 + 1/5.74)
RT = 0.852 kohm
RT = 852 ohm

11. Determine la corriente a través de cada resistor del circuito de la figura; calcule en seguida cada caída de voltaje.

![image](https://user-images.githubusercontent.com/94182617/146944423-c23a1d18-ba2e-468c-8fb7-c08940719d16.png)

(a)
RT = 133 ohm

R2||R3 = 1/(1/R2 + 1/R3)
R2||R3 = 1/(1/100 + 1/100)
R2||R3 = 50 ohm

IT = Vs/RT
IT = 1.5/133
IT = 0.0113 A

Vn1-n2 = IT * R1
Vn1-n2 = 0.0113 * 56
Vn1-n2 = 0.633 V

Vn2-n3 = IT * R2||R3
Vn2-n3 = 0.0113 * 50
Vn2-n3 = 0.565 V

Vn3-n4 = IT * R4
Vn3-n4 = 0.0113 * 27
Vn3-n4 = 0.305 V

I1 = I4 = 0.0113 A = 11.3 mA

I3 = I4 = Vn2-n3/R2-3 
I3 = I4 = 0.565/100
I3 = I4 = 0.0056 A = 5.6 mA

V1 = (R1/RT)*Vs
V1 = (56/133) * 1.5
V1 = 0.632 V = 632 mV

V4 = (R4/RT)*Vs
V4 = (27/133)*1.5
V4 = 0.305 V = 305 mV

V2 = V3 = (R2||R3/RT)*Vs
V2 = V3 = (50/133)*1.5
V2 = V3 = 0.564 V = 564 mV


(b)
RT = 779 ohm

R2||R3||R4 = 1/(1/R2 + 1/R3 + 1/R4)
R2||R3||R4 = 1/(1/680 + 1/330 + 1/180)
R2||R3||R4 = 99.43 ohm

IT = Vs/RT
IT = 3/779
IT = 0.0038 A

Vn1-n2 = IT * R1
Vn1-n2 = 0.0038 * 680
Vn1-n2 = 2.58 V

Vn2-n3 = IT * R2||R3||R4 
Vn2-n3 = 0.0038 * 99.43
Vn2-n3 = 0.38 V

I1 = 0.0038 A = 3.8 mA

I2 = Vn2-n3/R2
I2 = 0.38/680
I2 = 0.000555 A = 555 microA

I3 = Vn2-n3/R3
I3 = 0.38/330
I3 = 0.00115 A = 1.16 mA

I4 = Vn2-n3/R4
I4 = 0.38/180
I4 = 0.0021 A = 2.1 mA

V1 = (R1/RT)*Vs
V1 = (680/779) * 3
V1 = 2.62 V

V2 = (R2||R3||R4/RT)*Vs
V2 = V3 = V4 = (99.43/779)*3
V2 = V3 = V4 = 0.383 V = 383 mV

13. Encuentre RT para todas las combinaciones de los interruptores de la figura.
 
![image](https://user-images.githubusercontent.com/94182617/146944531-38b8f2fb-4b3a-4a50-9775-48c388a9724e.png)
 
 
SW1 cerrado, SW2 abierto: 220 ohm
SW1 cerrado, SW2 cerrado: 200 ohm
SW1 abierto, SW2 abierto: 320 ohm
SW1 abierto, SW2 cerrado: 300 ohm

15. Determine el voltaje en cada nodo con respecto a tierra en la figura.

![image](https://user-images.githubusercontent.com/94182617/146944585-2057f034-9006-4a56-8899-3be37b1dab3f.png)

RT = R2 + R1||R3 + R4||R5
RT = 4.7 + 0.8 + 0.85 + 1
RT = 2.8 kohm

RA = 2.8 kohm
VA = (2.8/7.35) * 100
VA = 38.09 V

RB = 0.84 kohm
VA = (0.84/7.35) * 100
VB = 11.48 V

RC = 0.64 kohm
VA = (0.64/7.35) * 100
VC = 8.70 V

RD = 1 kohm
VA = (1/7.35) * 100
VD = 13.6 V


17. En la figura, ¿cómo determinaría el voltaje entre los extremos de R2 por medición sin conectar directamente un medidor entre los extremos del resistor?
 
![image](https://user-images.githubusercontent.com/94182617/146944646-1c833874-d260-4b10-a254-322ed346045a.png)
 
 
Medir el voltaje en A con respecto a tierra y el voltaje en B con respecto a tierra. La diferencia es VR2.

19. Determine la resistencia del circuito mostrado en la figura como se ve desde la fuente de voltaje.

![image](https://user-images.githubusercontent.com/94182617/146944704-d20625a1-81c0-4dde-86a7-a16d706de69e.png)

R1+R2+R3 = 100 + 560 + 56
R1+R2+R3 = 716 kohm

R5+R6 = 100 + 1000
R5+R6 = 1100 kohm

RT = 1/(1/(R1+R2+R3) + 1/(R5+R6) + 1/R4)
RT = 1/(1/716 + 1/1100 + 1/1000)
RT = 303 kohm

21. 
(a) Determine el valor de R2 en la figura. 
(b) Encuentre la potencia en R2.

![image](https://user-images.githubusercontent.com/94182617/146944743-8c12876b-0e45-4e8b-94b2-6c0a546a6a90.png)

(a)
I2 = [R1/(R1+R2)]*IT
1 = [47/(47+R2)]*IT
IT = V/RT = 220/(33+47R2/47R2)
47 + R2 = 47[220/(33+47R2/47R2)]
R2 = 110 kohm

(b)
P2 = I2^2*R2
P2 = 1^2 * 110
W = 110 mW


23. Encuentre la resistencia entre cada uno de los siguientes juegos de nodos mostrados en la figura: AB, BC y CD.

![image](https://user-images.githubusercontent.com/94182617/146944777-322e9359-0c90-4985-810b-033acf9d540f.png)

RAB = 1/(1/(R1+R2) + 1/R3 + 1/R4)
RAB = 1/(1/6.6 + 1/3.3 + 1/3.3)
RAB = 1.32 kohm

RBC = 1/(1/(R1+R2) + 1/R3 + 1/R4)
RBC = 1/(1/6.6 + 1/3.3 + 1/3.3)
RBC = 1.32 kohm

RCD = 0 ohm

Divisores de voltaje con cargas resistivas
25. Un divisor de voltaje está compuesto por dos resistores de 56 kohm y una fuente de 15 V. Calcule el voltaje de salida sin carga. ¿Cuál será el voltaje de salida si se conecta un resistor con carga de 1 Mohm a la salida?

VSalida(sin carga) = (R1/R1+R2)*Vs
VSalida(sin carga) = (56/56+56)*15
VSalida(sin carga) = 7.5 V

R1||RL = R1*RL/(R1+RL)
R1||RL = (5.6*10^4)(1*10^6)/(5.6*10^4 + 1*10^6)
R1||RL = 53030.3 ohm = 53 kohm

VSalida(con carga) = (R1||RL/(R1 + R1||RL) * Vs
VSalida(con carga) = (53/(56 + 53) * 15
VSalida(con carga) = 7.29 V


27. ¿Cuál de dos cargas, una de 10 kohm y otra de 47 kohm, provocará una disminución más pequeña en el voltaje de salida de un divisor de voltaje dado?

La carga que provocará una disminución más pequeña en el voltaje de salida de un divisor de voltaje es la de 47 ohm ya que entre mayor sea la resistencia menor será el voltaje de salida.



29. En la figura determine el voltaje de salida con una carga de 33kohm conectada entre A y B.

![image](https://user-images.githubusercontent.com/94182617/146944840-a023c288-75a3-4ec3-a2a0-3d82aaebcbc0.png)

RAB = R2+3*
RAB = 8.3 * 33/(8.3 + 33)
RAB = 6.63 kohm

VAB = 6.63/(10 + 6.63)
VAB = 8.77 V


31. Determine los valores de resistencia para un divisor de voltaje que debe satisfacer las siguientes especificaciones: la corriente extraída de la fuente sin carga no debe exceder de 5 mA; el voltaje de fuente tiene que ser de 10 V, y las salidas requeridas deben ser de 5 y 2.5 V. Trace el circuito. Determine el efecto en los voltajes de salida si se conecta una carga de 1.0 kΩ a cada toma, una a la vez.

![image](https://user-images.githubusercontent.com/84757114/146865216-7e80467d-cb8f-4f69-b343-25ebd32cfafa.png)
![image](https://user-images.githubusercontent.com/84757114/146865288-2daa22d0-6c55-4b54-9627-ab72c97daa21.png)

33. La figura 7-76 muestra un circuito polarizador de cd para un amplificador de transistor de efecto de campo. La polarización es un método común empleado para establecer ciertos niveles de voltaje de cd para la operación apropiada de un amplificador. Aunque no se espera que usted conozca los amplificadores con transistores en este momento, los voltajes y las corrientes de cd presentes en el circuito pueden ser determinados con métodos ya conocidos. 
(a) Encuentre VG y VS (b) Determine I1, I2, ID, e IS (c) Encuentre VDS y VDG.

![image](https://user-images.githubusercontent.com/84757114/146867140-d281a3d2-b61d-4c39-9474-689e38ff06af.png)

35. ¿En cuál de los siguientes intervalos de voltaje presentará un voltímetro la mínima carga que haya en un circuito? (a) 1 V (b) 10 V (c) 100 V (d) 1000 V.

![image](https://user-images.githubusercontent.com/84757114/146867416-65b0b308-7a7c-4a23-b359-5ede586dfed8.png)


37. El voltímetro descrito en el problema 36 se utiliza para medir voltaje entre los extremos de R4 en la figura 7-62(a). (a) ¿Qué intervalo se deberá utilizar? (b) ¿En cuánto se reduce el voltaje medido por el medidor con respecto al voltaje real?

![image](https://user-images.githubusercontent.com/84757114/146867910-664c4d28-b297-4b90-ba2d-15ca5fed6f1e.png)

39. Para el circuito mostrado en la figura 7-77, calcule: (a) La resistencia total entre las terminales de la fuente (b) La corriente total suministrada por la fuente (c) La corriente a través del resistor de 910 Æ (d) El voltaje desde el punto A hasta el punto B.

![image](https://user-images.githubusercontent.com/84757114/146868111-b181152e-ad9f-45f7-8fd3-6c1d7a904319.png)
![image](https://user-images.githubusercontent.com/84757114/146868179-30877c25-3914-4938-89a0-47a1e71df82e.png)

41. Determine la resistencia total entre las terminales A y B de la red en escalera de la figura 7-79. Asimismo, calcule la corriente en cada rama con 10 V entre A y B.

![image](https://user-images.githubusercontent.com/84757114/146868842-d6bcdc62-15b3-4a33-a163-ab6db3eebb89.png)
![image](https://user-images.githubusercontent.com/84757114/146869115-ccdf5670-b344-435c-bb42-7d53546c5fca.png)

43. Determine IT y VSALIDA en la figura 7-80.

![image](https://user-images.githubusercontent.com/84757114/146869331-86ecceda-ab41-42af-9940-4041a8b36aec.png)
![image](https://user-images.githubusercontent.com/84757114/146869294-80c50ad7-82ea-4e55-95fe-e88abd440888.png)
![image](https://user-images.githubusercontent.com/84757114/146869557-163254a7-0a3f-4597-a0c2-ada9b97452ae.png)
![image](https://user-images.githubusercontent.com/84757114/146869601-072ffa68-09b2-4d69-90d0-291a70e4dc8e.png)

45. Determine VSALIDA para la red R/2R en escalera mostrada en la figura 7-81 para las siguientes condiciones:
(a) Interruptor SW2 conectado a +12 V y los demás conectados a tierra 
(b) Interruptor SW1 conectado a +12 V y los demás conectados a tierra

![image](https://user-images.githubusercontent.com/84757114/146869676-f89fd39a-bf4b-4f98-8ff8-e5bce6ba9e38.png)
![image](https://user-images.githubusercontent.com/84757114/146869735-55c964cd-0b32-4af3-8d06-a967a8b1ddef.png)
![image](https://user-images.githubusercontent.com/84757114/146869789-b139653d-e04f-40d5-9e4c-53a369f09241.png)

47. Una celda de carga tiene cuatro medidores de deformación idénticos con una resistencia ilimitada de 120,000 Æ para cada medidor (un valor estándar). Cuando se agrega una carga, los medidores a tensión incrementan su resistencia en 60 mΩ, a 120,060 Ω, y los medidores a compresión disminuyen su resistencia en 60 mΩ, a 119.940 Ω, como se muestra en la figura 7-82. ¿Cuál es el voltaje de salida con carga? 

![image](https://user-images.githubusercontent.com/84757114/146869952-83aa1dab-88fe-4bb7-8832-7b9e80e7c849.png)
![image](https://user-images.githubusercontent.com/84757114/146870049-ec583f12-df5f-43ea-818b-99ac92e39098.png)
![image](https://user-images.githubusercontent.com/84757114/146870094-9d848331-5b72-4a31-b3ed-0344dedd162e.png)

49. ¿Es correcta la lectura del voltímetro de la figura 7-84?

![image](https://user-images.githubusercontent.com/84757114/146870196-445420d8-4e4f-4f15-be94-b81008fb2c21.png)
![image](https://user-images.githubusercontent.com/84757114/146870635-ddfae26d-9742-4786-9335-c47815a93643.png)
![image](https://user-images.githubusercontent.com/84757114/146870334-0dbfce63-afd0-4476-810e-7e854e8d458b.png)
![image](https://user-images.githubusercontent.com/84757114/146870411-9706eeb6-9809-4a89-9192-a24f2db16522.png)

51. En la figura 7-86 hay una falla. Con base en las indicaciones del medidor, determine cuál es la falla.

![image](https://user-images.githubusercontent.com/84757114/146870721-53cf9398-c2d5-438c-951c-6f1b6c9a62a2.png)
![image](https://user-images.githubusercontent.com/84757114/146870862-8e0411f3-d324-40bf-b516-9a4823f7af86.png)
![image](https://user-images.githubusercontent.com/84757114/146870928-c57cee86-29e6-49da-95f4-0672bb804ea8.png)
![image](https://user-images.githubusercontent.com/84757114/146870965-651e481c-2c9d-456e-be94-e6f817617d40.png)
![image](https://user-images.githubusercontent.com/84757114/146871013-af18be20-8069-4482-8891-8dd31dae4855.png)

53. Revise las lecturas de los medidores de la figura 7-88 y localice cualquier falla que pudiera existir.

![image](https://user-images.githubusercontent.com/84757114/146871073-cd98c508-eebf-4d8e-bc07-9517d6e9512b.png)
![image](https://user-images.githubusercontent.com/84757114/146871128-feb27d83-f29b-4ff9-8e95-4a0be2ccb0b8.png)
![image](https://user-images.githubusercontent.com/84757114/146871184-96cf22fc-fb79-4873-8b29-1bc8afa230cb.png)


***CAPITULO N° 8***

 1. Una fuente de voltaje tiene los valores VS 3. Una batería tipo D nueva tiene entre sus terminales un voltaje de 1.6 V y puede suministrar hasta 8.0 A a un cortocircuito durante muy poco tiempo. ¿Cuál es la resistencia interna de la batería?00 V y RS  50Ω. Conviértala en una fuente de corriente equivalente.
 
 ![image](https://user-images.githubusercontent.com/84757114/146871533-f9a5dfc9-6afc-4fea-a3c2-c9df823bbdac.png)

3. Una batería tipo D nueva tiene entre sus terminales un voltaje de 1.6 V y puede suministrar hasta 8.0 A a un cortocircuito durante muy poco tiempo. ¿Cuál es la resistencia interna de la batería?

![image](https://user-images.githubusercontent.com/84757114/146871766-7378d93e-430f-4d90-ad7a-2191d9d7662f.png)

5. Una fuente de corriente tiene una IS de 600 mA y una RS de 1.2 kΩ. Conviértala en una fuente de voltaje equivalente.

![image](https://user-images.githubusercontent.com/84757114/146871894-a66f5d2b-0b5a-4fc3-9eb7-d3846b7b695b.png)

 Ejercicios Tito  (15 ultimos ejercicios impares)
 
 7.Con el método de superposición, encuentre la corriente a través de R5 en la figura 8-69.
 
 ![image](https://user-images.githubusercontent.com/94098157/146895768-94170cad-df8c-4bc1-b6c3-66372e16c7a0.png)
 ![image](https://user-images.githubusercontent.com/94098157/146895918-ed3acf8f-9914-41ab-8c98-52ab264371d8.png)

 9.Con el teorema de superposición, determine la corriente a través de R3 en la figura 8-70.
 
 ![image](https://user-images.githubusercontent.com/94098157/146896042-3f0b3e39-aad7-4da5-87ed-0050c1f5dc7e.png)
 ![image](https://user-images.githubusercontent.com/94098157/146896399-94ec8278-0ca3-4aac-b578-6176d94cff12.png)

 11.En la figura 8-72 se muestra un circuito comparador. El voltaje de entrada, VENTRADA, se compara con
 el voltaje de referencia, VREFERENCIA, y se genera una salida negativa si VREFERENCIA > VENTRADA; de
 lo contrario es positiva. El comparador no carga a una u otra entrada. Si R2 es de 1.0 kΩ, ¿cuál es el intervalo
 del voltaje de referencia?
 ![image](https://user-images.githubusercontent.com/94098157/146896524-d18afedd-851a-4d72-a622-1086f9a80420.png)

 13.Determine el voltaje del punto A al punto B en la figura 8-73.
 
 15.La figura 8-75 muestra dos redes en escalera. Determine la corriente producida por cada una de las baterías
 cuando se conectan las terminales A (A a A) y las terminales B (B a B).
 
 ![image](https://user-images.githubusercontent.com/94098157/146896687-c42b2650-6b0a-4961-8264-9e9fef1f8edd.png)

 17.Con el teorema de Thevenin, determine la corriente a través de la carga RL en la figura 8-77.
 
 ![image](https://user-images.githubusercontent.com/94098157/146927847-80a82ac5-6b88-4f58-9114-6b8931f1e858.png)
 ![image](https://user-images.githubusercontent.com/94098157/146927967-70a22c01-c9ec-4490-82c4-6910549040c3.png)

 19.Determine el equivalente de Thevenin para el circuito externo al amplificador de la figura 8-79.
 ![image](https://user-images.githubusercontent.com/94098157/146933798-0ce3b827-be75-4264-8dbb-12f7e9fb2215.png)

 21.Determine la corriente a través del resistor de carga en el circuito puente de la figura 8-81.
 
 23.Para cada uno de los circuitos mostrados en la figura 8-76, determine el equivalente Norton visto por RL.
 ![image](https://user-images.githubusercontent.com/94098157/146938759-f52ffc79-a593-4341-8b51-1ba82d3810a2.png)

 25.Con el teorema de Norton, determine el voltaje entre los extremos de R5 en la figura 8-78.
![image](https://user-images.githubusercontent.com/94098157/146940393-39546ad1-a0af-4896-b0d1-14c5cfa2cba5.png) 
 
 27.Determine el circuito equivalente Norton para el puente que aparece en la figura 8-81 sin RL.
 ![image](https://user-images.githubusercontent.com/94098157/146941657-de771c2c-af6e-4452-b138-9a544dceebe4.png)

 29.Aplique el teorema de Norton al circuito de la figura 8-84.
 ![image](https://user-images.githubusercontent.com/94098157/146943284-8f0348bb-d214-4315-8d5e-fcc760f85c3f.png)

 31.En el circuito de la figura 8-86, determine el valor de RL para transferencia de potencia máxima.
 
 33.¿Cuáles son los valores de R4 y RTH cuando la potencia máxima se transfiere de la fuente thevenizada
 a la red en configuración de escalera de la figura 8-87?
 
 35.En la figura 8-89, convierta cada red Y en una red delta.
 


