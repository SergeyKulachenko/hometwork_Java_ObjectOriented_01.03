# hometwork_Java_ObjectOriented_01.03
<h3>"Цикломатическая сложность кода"</h1>
<p>Определение цикломатической сложности v (G) основано на представление графа потока управления методом в виде направленного графа: v (G) = E-N + 2
Где E-число ребер, а N-число узлов. </p>
Рекомендуется разделять модули на более мелкие всякий раз, когда цикломатическая сложность этих модулей превысит десять.
Эта практика была включена НИСТ-ом в методику структурного тестирования с замечанием, что со времени исходной публикации Маккейба выбор значения 10 
получил весомые подтверждения, однако в некоторых случаях может быть целесообразно ослабить ограничение и разрешить модули со сложностью до 15.
