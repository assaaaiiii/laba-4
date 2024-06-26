# Момент инерции тела относительно оси. Радиус инерции.
_Моментом инерции тела (системы ) относительно данной оси_ $Oz$ _(или осевым моментом инерции) называется скалярная величина, равная сумме произведений масс всех точек тела (системы ) на квад­раты их расстояний от этой оси_:

$$J_z=\sum m_kh_k^2. (2)$$

Из определения следует, что момент инерции тела (или системы) относительно любой оси является величиной положительной и не равной нулю. В дальнейшем будет показано, что осевой момент инерции играет при вращательном движении тела такую же роль, какую масса при поступательном, т.е. что *осевой момент инерции является мерой инертности тела при вращательном движении.*

Согласно формуле (2) момент инерции тела равен сумме моментов инерции всех его частей относительно той же оси. Для одной мате­риальной точки, находящейся на расстоянии $h$ от оси, $J_z=mh^2.$ Единицей измерения момента инерции в СИ будет 1 $кг м^2$ (в системе МКГСС— 1 $кгм с^2$).

Для вычисления осевых моментов инерции можно расстояния точек от осей выражать через координаты $x_k , y_k, z_k$ этих точек (на­пример, квадрат расстояния от оси $Ox$ будет $y_k^2+ z_k^2$ и т.д.). Тогда моменты инерции относительно осей $Oxyz$ будут определяться формулами: 
$$J_x=\sum m_k(y_k^2+ z_k^2) , J_y=\sum m_k(x_k^2+ z_k^2) , J_z=\sum m_k(y_k^2+ x_k^2).  (3)$$

Часто в ходе расчетов пользуются понятием радиуса инерции. *Радиусом* инерции тела относительно оси $Oz$ называется линейная величина $\rho_z$ определяемая равенством
$$J_x=M\rho_x^2    (4)$$

где $М$ — масса тела. Из определения следует, что радиус инерции геометрически равен расстоянию от оси $Oz$ той точки, в которой надо сосредоточить массу всего тела, чтобы момент инерции одной этой точки был равен моменту инерции всего тела.

Зная радиус инерции, можно по формуле (4) найти момент инерции тела и наоборот. 

Формулы (2) и (3) справедливы как для твердого тела, так и для любой системы материальных точек. В случае сплошного тела, раз­бивая его на элементарные части, найдем, что в пределе сумма, стоя­щая  в равенстве (2), обратится в интеграл. В результате, учитывая,
что (формула)
где $\rho$ — плотность, а $V$ — объем, получим
$$J_z=\int_{(V)}h^2dm  или  J_z=\int_{(V)}\rho h^2dV.    (5)$$

Интеграл здесь распространяется на весь объем $V$ тела, а плотность $\rho$ и расстояние $l$ зависят от координат точек тела. Аналогично фор­мулы (3) для сплошных тел примут вид
$$J_x=\int_{(V)}\rho (y^2+z^2)dV  и т.д.       (5')$$

Формулами (5) и (5') удобно пользоваться при вычислении мо­ментов инерции однородных тел правильной формы. При этом плот­ность р будет постоянной и выйдет из-под знака интеграла.

Найдем моменты инерции некоторых однородных тел.

1. Тонкий однородный стержень длиной $l$ и массой $М$. Вычислим его момент инерции относительно оси $Az$, перпендикулярной стержню и проходящей через его конец $A$(рис. 275). Направим вдоль $AB$ координатную ось $Ax$. Тогда для любого эле­ментарного отрезка длины $dx$ величина $h=x$, а масса $dm=p_1dx$, где $p_1=M/l$— масса единицы длины стержня. В результате формула  (5) дает[^1]
$$J_A=\int_0^lx^2dm=\rho_1\int_0^lx^2dx=\rho_1l^3/3$$

[^1]: Здесь и везде далее $J_A$ обозначает момент инерции относительно оси, проходящей через точку $A$ и направленной перпендикулярно плоскости изображенного на чертеже сечения тела.
Заменяя здесь $\rho_1$ его значением, найдем окончательно

$$J_A=Ml^2/3       (6)$$
3. Тонкое круглое однородное кольцо радиусом $R$ и массой $M$. Найдем его момент инерции относительно

<img src="https://raw.githubusercontent.com/difdifdif/teor_mex/main/image/2.jpg" width="720" height="avto">

Оси $Cz$, перпендикулярной плоскости кольца и проходящей через его центр $С$ (рис. 276). Так как все точки кольца находятся от оси $Cz$ на расстоянии $h_k =R$, то формула (2) дает
$$J_C=\sum m_kR^2=(\sum m_k)R^2=MR^2.$$

Следовательно, для кольца[^2]
$$J_C=MR^2.   (7)$$

Очевидно, такой же результат получится для момента инерции тонкой цилиндрической оболочки массой $М$ и радиусом $R$ относительно ее оси.

3. Круглая однородная пластина или цилиндр радиусом $R$ и массой $М$. Вычислим момент инерции круглой пластины относительно оси Cz, перпендикулярной пластине и проходящей через ее центр (см. рис. 276). Для этого выделим элементарное кольцо радиусом $r$ и шириной $dr$ (рис. 277, а). Площадь этого кольца $2\pi r dr$, а масса $dm=\rho_2\pi rdr$, где $\rho =M/\pi r^2$ - масса единицы площади пластины. Тогда по формуле (7) для выделенного элементарного кольца будет $dJ_C=r^2dm=2\pi \rho_2r^3dr$, a для всей пластины
$$J_c=2\pi\rho_2\int_0^R r^3dr =\pi\rho_2R^4/2 .$$

Заменяя здесь $\rho_2$ его значением, найдем окончательно
$$Jc=MR^2/2.     (8)$$

[^2]:Сравнивая формулы (4) и (7) можно еще заключить, что радиус инерции тела равен радиусу тонкого кольца с таким же осевым моментом инерции, как и у тела.
Такая же формула получится, очевидно, и для момента инерции $J_x$ однородного круглого цилиндра массой $М$ и радиусом $R$ относительно его оси (рис. 277, б).

4. Прямоугольная пластина, конус, шар. Опуская выкладки, приведем формулы, определяющие моменты инерции следующих тел (читатель может получить их самостоятельно, а также найти эти и другие формулы в различных справочниках):

a) сплошная прямоугольная пластина массой $М$ со сторонами $AB=а$ и $BD=b$ (ось $х$ направлена вдоль стороны $AВ$, ось $у$ - вдоль $BD$):
$$J_x=Mb^2/3,    J_y=Ma^2/3;$$

б) прямой сплошной круглый конус массой $М$ с радиусом основания $R$ (ось $z$ направлена вдоль оси конуса):
$$J_z=0,3MR^2;$$

в) сплошной шар массой $М$ и радиусом $R$ (ось $z$ направлена вдоль диаметра):
$$J_z=0,4MR^2.$$

Моменты инерции неоднородных тел и тел сложной конфигурации можно определять экспериментально с помощью соответствующих приборов.
