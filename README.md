# E_V_plot
立方晶の安定圧力を求めるコード
#原理
Birch–Murnaghanの状態方程式を第一原理計算で算出したエネルギーのデータに対してfittingして以下の式から安定圧力を算出。
E(V)=E_0+\frac{9V_0B_0}{16}\left(\left(\left(\frac{V_0}{V}\right)^{\frac{2}{3}}-1\right)^3B_0^\prime+\left(\left(\frac{V_0}{V}\right)^{\frac{2}{3}}-1\right)^2\left(6-4\left(\frac{V_0}{V}\right)^{\frac{2}{3}}\right)\right)
