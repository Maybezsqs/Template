# 希腊字母表及 LaTeX 代码（含小写、大写及变体）

|    |    |    |     |       |  |      |    |    |    |    |   |  |      |
|--------|--------|--------|---------|---------------------|----------------|--------------------|--------|--------|--------|---------|---------------------|----------------|--------------------|
| 阿尔法 | α      | Α      |         | `\alpha`            | `\Alpha`       |                    | 贝塔   | β      | Β      |         | `\beta`             | `\Beta`        |                    |
| 伽马   | γ      | Γ      |         | `\gamma`            | `\Gamma`       |                    | 德尔塔 | δ      | Δ      |         | `\delta`            | `\Delta`       |                    |
| 埃普西隆 | ε    | Ε      | ϵ       | `\epsilon`          | `\Epsilon`     | `\varepsilon`      | 齐塔   | ζ      | Ζ      |         | `\zeta`             | `\Zeta`        |                    |
| 艾塔   | η      | Η      |         | `\eta`              | `\Eta`         |                    | 西塔   | θ      | Θ      | ϑ       | `\theta`            | `\Theta`       | `\vartheta`        |
| 爱欧塔 | ι      | Ι      |         | `\iota`             | `\Iota`        |                    | 卡帕   | κ      | Κ      | ϰ       | `\kappa`            | `\Kappa`       | `\varkappa`        |
| 拉姆达 | λ      | Λ      |         | `\lambda`           | `\Lambda`      |                    | 缪     | μ      | Μ      |         | `\mu`               | `\Mu`          |                    |
| 努     | ν      | Ν      |         | `\nu`               | `\Nu`          |                    | 克西   | ξ      | Ξ      |         | `\xi`               | `\Xi`          |                    |
| 欧米伽 | ο      | Ο      |         | `\omicron`          | `\Omicron`     |                    | 派     | π      | Π      | ϖ       | `\pi`               | `\Pi`          | `\varpi`           |
| 罗     | ρ      | Ρ      | ϱ       | `\rho`              | `\Rho`         | `\varrho`          | 西格玛 | σ      | Σ      | ς       | `\sigma`            | `\Sigma`       | `\varsigma`        |
| 塔乌   | τ      | Τ      |         | `\tau`              | `\Tau`         |                    | 宇普西隆 | υ    | Υ      |         | `\upsilon`          | `\Upsilon`     |                    |
| 菲     | φ      | Φ      | ϕ       | `\phi`              | `\Phi`         | `\varphi`          | 凯     | χ      | Χ      |         | `\chi`              | `\Chi`         |                    |
| 赛     | ψ      | Ψ      |         | `\psi`              | `\Psi`         |                    | 欧米茄 | ω      | Ω      |         | `\omega`            | `\Omega`       |                    |








\begin{table}[H]
\centering
\footnotesize
\renewcommand{\arraystretch}{1.2}
\begin{tabular}{l l l l l l}
\toprule
  & \multicolumn{2}{l}{Branch Net}  & \multicolumn{2}{l}{Trunk Net} & \multirow{2}{*}{Training steps}  \\
  \cmidrule(lr){2-3} \cmidrule(lr){4-5}
  & width $\times$ depth  & Activation & width $\times$ depth & Activation & \\
\midrule
  {Sec. 3.3} & $64 \times 2$   & tanh & $64 \times 3$ & tanh &  100,000 \\
  {Sec. 3.4} & $256 \times 2$   & tanh  & $128 \times 2$ & tanh &  200,000 \\
\bottomrule
\end{tabular}
\caption{
Architecture and training steps of DeepONets in each case. 
}
\label{table:deeponet_arch}
\end{table}
