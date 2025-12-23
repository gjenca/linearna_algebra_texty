\section{Matica lineárneho zobrazenia}

Uvažujme teraz tieto dáta:
\begin{itemize}
    \item Konečnorozmerné vektorové priestory $V, U$.
    \item $X=(\vec{x}_{1},\dots,\vec{x}_{n})$ je báza $V$ (teda $\dim(V)=n$).
    \item $Y=(\vec{y}_{1},\dots,\vec{y}_{m})$ je báza $U$ (teda $\dim(U)=m$).
    \item $f: V \rightarrow U$ je lineárne zobrazenie.
\end{itemize}

Vieme z Vety 12.4, že $f$ je jednoznačne určené $n$-ticou vektorov $(f(\vec{x}_{1}),\dots,f(\vec{x}_{n}))$.

Každý z týchto vektorov $f(\vec{x}_{1}),\dots,f(\vec{x}_{n})$ je vektor z $U$, a teda každý z nich má nejaké súradnice v
báze $Y$, ktoré ho určujú:
\[
[f(\vec{x}_{1}]_Y,\dots,[f(\vec{x}_{n})]_Y
\]
Vzniká nám nasledujúca definícia.

\begin{definicia}[Matica lineárneho zobrazenia]
\label{def:maticaLZ}
Nech $V, U$ sú konečnorozmerné vektorové priestory, nech $X=(\vec{x}_{1},\dots,\vec{x}_{n})$ je báza $V$, nech $Y=(\vec{y}_{1},\dots,\vec{y}_{m})$ je báza $U$, nech $f: V \rightarrow U$ je lineárne zobrazenie.
Potom \textbf{matica $f$ v bázach $X, Y$} je matica typu $m \times n$:
\[
[f]_{YX}=([f(\vec{x}_{1})]_{Y} \dots [f(\vec{x}_{n})]_{Y})
\]
\end{definicia}

\subsection{Príklady matíc lineárnych zobrazení}

Uvažujme nasledujúce príklady lineárnych zobrazení:
\begin{priklad}[Nulové lineárne zobrazenie]
    $f: V \rightarrow U$, $f(\vec{v})=\vec{0}$.
    \[
    [f]_{YX}=
    \begin{pmatrix}
    0 & 0 & \dots \\
    0 & \dots & \\
    \vdots & &
    \end{pmatrix}
    \]
    Je to nulová matica, bez ohľadu na bázy $X, Y$.
\end{priklad}

\begin{priklad}[Identické lineárne zobrazenie]
    $\id: V \rightarrow V$, $X=(\vec{x}_{1},\dots,\vec{x}_{n})$ je ľubovoľná báza.
    \[
    [\id]_{XX}=([\id(\vec{x}_{1})]_{X} \dots [\id(\vec{x}_{n})]_{X}) = ([\vec{x}_{1}]_{X} \dots [\vec{x}_{n}]_{X})
    \]
    Keďže platí:
    \begin{align*}
    \vec{x}_{1} &= 1\vec{x}_{1} + 0\vec{x}_{2} + \dots + 0\vec{x}_{n} \implies [\vec{x}_{1}]_{X} = (1, 0, \dots, 0) = \vec{e}_{1} \\
    \vec{x}_{2} &= 0\vec{x}_{1} + 1\vec{x}_{2} + \dots + 0\vec{x}_{n} \implies [\vec{x}_{2}]_{X} = (0, 1, \dots, 0) = \vec{e}_{2}
    \end{align*}
    Dostávame:
    \[
    [\id]_{XX} = 
    \begin{pmatrix}
    1 & 0 & \dots & 0 \\
    0 & 1 & \dots & 0 \\
    \vdots & \vdots & \ddots & \vdots \\
    0 & 0 & \dots & 1
    \end{pmatrix}
    = I_n
    \]
\end{priklad}

\begin{priklad}[rovinná rotácia]
    \begin{figure}
\begin{center}
\scalebox{0.75}{
\begin{tikzpicture}[
    thick,
    >={Latex[length=2.5mm, width=2mm]},
    vector/.style={->, very thick, line cap=round},
    basis vector/.style={vector, color=black},
    rotated vector 1/.style={vector, color=blue!70!cyan},
    rotated vector 2/.style={vector, color=green!60!black},
    projection/.style={thin, color=red!80!black},
    angle arc/.style={->, thick},
    every node/.style={font=\large}
]

    % === Parameters ===
    \def\R{4.0} % Radius of the circle
    \def\angleval{40} % Angle theta for drawing

    % === Coordinates ===
    \coordinate (O) at (0,0);
    
    % Basis vectors
    \coordinate (X1_tip) at (\R, 0);
    \coordinate (X2_tip) at (0, \R);
    
    % Rotated vectors on the circle
    \coordinate (LX1) at (\angleval:\R);
    \coordinate (LX2) at (90+\angleval:\R);

    % === Circle ===
    \draw[thin] (O) circle (\R);

    % === Projections of l_theta(x1) ===
    \coordinate (LX1_x) at ({\R*cos(\angleval)}, 0);
    \coordinate (LX1_y) at (0, {\R*sin(\angleval)});

    % Draw projection lines
    \draw[projection] (LX1) -- (LX1_x);
    \draw[projection] (LX1) -- (LX1_y);
    
    % Draw components on axes
    \draw[projection] (O) -- (LX1_x);
    \draw[projection] (O) -- (LX1_y);

    % === Braces for Components ===
    
    % X-component brace (Mirror moves it below the line)
    \draw[projection, decorate, decoration={brace, amplitude=5pt, mirror, raise=3pt}]
        (O) -- (LX1_x) node[midway, below=12pt] {$\cos(\theta)$};

    % Y-component brace (Standard brace on the "left" of the path O->Y puts it on the left side of the axis)
    \draw[projection, decorate, decoration={brace, amplitude=5pt, raise=3pt}]
        (O) -- (LX1_y) node[midway, left=12pt] {$\sin(\theta)$};

    % Right angle symbol
    %\draw[thin, gray] ($(LX1_x)+(-0.3,0)$) -- ($(LX1_x)+(-0.3,0.3)$) -- ($(LX1_x)+(0,0.3)$);
    %\fill[gray] ($(LX1_x)+(-0.15,0.15)$) circle (1pt);


    % === Basis Vectors ===
    \draw[basis vector] (O) -- (X1_tip) node[right, xshift=2pt] {$\vec{x_1}$};
    \draw[basis vector] (O) -- (X2_tip) node[above, yshift=2pt] {$\vec{x_2}$};

    % === Rotated Vectors ===
    % l_theta(x1)
    \draw[rotated vector 1] (O) -- (LX1)
        node[right, xshift=5pt, align=left]
        {$l_\theta(\vec{x_1}) = \cos(\theta).\vec{x_1} +  \sin(\theta).\vec{x_2}$};


    % === Angles ===
    % Theta for x1
    \draw[angle arc, color=blue!70!cyan] (1.3,0) arc (0:\angleval:1.3) node[midway, right, xshift=2pt] {$\theta$};

\end{tikzpicture}
}
\scalebox{0.75}{
\begin{tikzpicture}[
    thick,
    >={Latex[length=2.5mm, width=2mm]},
    vector/.style={->, very thick, line cap=round},
    basis vector/.style={vector, color=black},
    rotated vector 1/.style={vector, color=blue!70!cyan},
    rotated vector 2/.style={vector, color=green!60!black},
    projection/.style={thin, color=red!80!black},
    angle arc/.style={->, thick},
    every node/.style={font=\large}
]

    % === Parameters ===
    \def\R{4.0} % Radius of the circle
    \def\angleval{40} % Angle theta for drawing

    % === Coordinates ===
    \coordinate (O) at (0,0);
    
    % Basis vectors
    \coordinate (X1_tip) at (\R, 0);
    \coordinate (X1m_tip) at (-\R, 0);
    \coordinate (X2_tip) at (0, \R);
    
    % Rotated vectors on the circle
    \coordinate (LX1) at (\angleval:\R);
    \coordinate (LX2) at (90+\angleval:\R);
    
    % === Projections of l_theta(x2) ===
    \coordinate (LX2_x) at ({\R*cos(\angleval+90)}, 0);
    \coordinate (LX2_y) at (0, {\R*sin(\angleval+90)});
    
    % Draw projection lines
    \draw[projection] (LX2) -- (LX2_x);
    \draw[projection] (LX2) -- (LX2_y);

    % === Circle ===
    \draw[thin] (O) circle (\R);


    % === Basis Vectors ===
    \draw[basis vector] (O) -- (X1_tip) node[right, xshift=2pt] {$\vec{x_1}$};
    \draw[basis vector] (O) -- (X2_tip) node[above, yshift=2pt] {$\vec{x_2}$};
    \draw (O) -- (X1m_tip);

    % l_theta(x2)
    \draw[rotated vector 2] (O) -- (LX2) node[left, xshift=-10pt,align=right] 
    {
    $l_\theta(\vec{x_2})=l_{\theta+\frac{\pi}{2}}(\vec{x_1})=$\\
    $\cos(\theta+\frac{\pi}{2}).\vec{x_1}+sin(\theta+\frac{\pi}{2}).\vec{x_2}$
    };


    % Theta for x2
    \draw[angle arc, color=blue!70!cyan] (0,1.3) arc (90:90+\angleval:1.3) node[midway, above, yshift=2pt] {$\theta$};

    % Theta + pi/2 (shifted right and down)
    \draw[angle arc, color=green!60!black] (0.8,0) arc (0:90+\angleval:0.8);
    \node[color=green!60!black, xshift=18pt, yshift=-10pt] at (45+\angleval:1.3) {$\theta + \frac{\pi}{2}$};
    
    \draw[projection, decorate, decoration={brace, amplitude=5pt,raise=3pt}]
        (O) -- (LX2_x) node[midway, below=12pt] {$\cos(\theta+\frac{\pi}{2})$};
    
    \draw[projection, decorate, decoration={brace, amplitude=5pt, mirror, raise=3pt}]
        (O) -- (LX2_y) node[midway, right=12pt] {$\sin(\theta+\frac{\pi}{2})$};


\end{tikzpicture}
}
\end{center}
    \caption{Rotácia vektorov $\vec{x_1}$ a $\vec{x_2}$.}
    \end{figure}
    Nech $\rho_O$ je vektorový priestor geometrických vektorov v rovine s počiatkom $O$, nech $l_{\theta}: \rho_O \rightarrow \rho_O$ je rotácia okolo počiatku doľava o uhol $\theta$.
    Nech $\vec{x}_{1}, \vec{x}_{2}$ sú dva vektory, kolmé na seba, rovnakej dĺžky; $X=(\vec{x}_{1},\vec{x}_{2})$ je
    potom báza $\rho_O$. Aká je matica $[l_{\theta}]_{XX}$?
    
    Z obrázka (rotácia vektorov) dostávame súradnice vektorov:
    \begin{align*}
    l_{\theta}(\vec{x}_{1}) &= \cos(\theta) \vec{x}_{1}+ \sin(\theta) \vec{x}_{2}\\
    l_{\theta}(\vec{x}_{2}) &= \cos(\theta + \frac{\pi}{2}) \vec{x}_{1}+ \sin(\theta + \frac{\pi}{2}) \vec{x}_{2}\\
                             &= -\sin(\theta)\vec{x}_{1} + \cos(\theta)\vec{x}_{2}    
    \end{align*}
    Teda súradnice v báze $X$ sú
    \[
    [l_{\theta}(\vec{x}_{1})]_{X} = (\cos\theta, \sin\theta)
    \]
    \[
    [l_{\theta}(\vec{x}_{2})]_{X} = (-\sin\theta, \cos\theta)
    \]
    a matica $l_{\theta}$ v bázach $X, X$ je
    \[
    [l_{\theta}]_{XX} = ([l_{\theta}(\vec{x}_{1})]_{X}, [l_{\theta}(\vec{x}_{2})]_{X}) = 
    \begin{pmatrix}
    \cos\theta & -\sin\theta \\
    \sin\theta & \cos\theta
    \end{pmatrix}
    \]
\end{priklad}
\begin{priklad}[Derivácia polynómov]

    Nech $d: \R^{3}[x] \rightarrow \R^{2}[x]$ je lineárne zobrazenie "derivácia".
    Báza $\R^{3}[x]$ je $X=(1, x, x^{2}, x^{3})$.
    Báza $\R^{2}[x]$ je $Y=(1, x, x^{2})$.
    Vypočítajme obrazy bázových vektorov z $X$:
    \begin{align*}
    d(1) &= 0 \implies [0]_{Y} = (0,0,0) \\
    d(x) &= 1 \implies [1]_{Y} = (1,0,0) \\
    d(x^{2}) &= 2x \implies [2x]_{Y} = (0,2,0) \\
    d(x^{3}) &= 3x^{2} \implies [3x^{2}]_{Y} = (0,0,3)
    \end{align*}
    Teda matica $d$ v bázach $X, Y$ je:
    \[
    [d]_{YX} = 
    \begin{pmatrix}
    0 & 1 & 0 & 0 \\
    0 & 0 & 2 & 0 \\
    0 & 0 & 0 & 3
    \end{pmatrix}
    \]
\end{priklad}
    \begin{priklad}[Evaluácia polynómu]
    Lineárne zobrazenie $ev_{1,2,3}: \R^{2}[x] \rightarrow \R^{3}$ je
    dané predpisom 
    \[ev_{1,2,3}(p) = (p(1), p(2), p(3))\]
    Pre $\R^2[x]$ zvolíme bázu $X=(1, x, x^{2})$
    Pre $\R^3$ zvolíme bázu $E=(\vec{e}_{1}, \vec{e}_{2}, \vec{e}_{3})$.
    \begin{align*}
    ev_{1,2,3}(1) &= (1, 1, 1)\\
    ev_{1,2,3}(x) &= (1, 2, 3)\\
    ev_{1,2,3}(x^{2}) &= (1, 4, 9)
    \end{align*}
    Matica zobrazenia:
    \[
    [ev_{1,2,3}]_{EX} = 
    \begin{pmatrix}
    1 & 1 & 1 \\
    1 & 2 & 4 \\
    1 & 3 & 9
    \end{pmatrix}
    \]
    \end{priklad}

\begin{priklad}[Pravouhlá projekcia na priamku]
    Uvažujme priamku $q$ v rovine s počiatkom $S$ takú, že prechádza počiatkom. Zobrazenie $P_q: S \rightarrow S$, ktoré zobrazí každý vektor $\vec{v} \in S$ na jeho ortogonálnu projekciu na $q$ je lineárne (nedokazujeme).
    
    Nech $\vec{x}_{1}, \vec{x}_{2}$ sú dva navzájom kolmé vektory rovnakej dĺžky, ktoré (oba) zvierajú s priamkou $q$ uhol $45^{\circ}$. Oba sa pravouhlo premietajú na priamku $q$ do rovnakého vektora $P_q(\vec{x}_{1}) = P_q(\vec{x}_{2})$, ktorého koncový vrchol leží presne v strede štvorca vytýčeného $\vec{x}_{1}, \vec{x}_{2}$.
    
    Platí:
    \[
    P_q(\vec{x}_{1}) = P_q(\vec{x}_{2}) = \frac{1}{2}\vec{x}_{1} + \frac{1}{2}\vec{x}_{2}
    \]
    Súradnice tohto vektora v báze $X=(\vec{x}_{1}, \vec{x}_{2})$ sú $(\frac{1}{2}, \frac{1}{2})$.
    Teda matica $P_q$ v báze $X$ je:
    \[
    [P_q]_{XX} = 
    \begin{pmatrix}
    1/2 & 1/2 \\
    1/2 & 1/2
    \end{pmatrix}
    \]
\end{priklad}

\begin{veta}
\label{veta:akciaMatice}
Nech $V, U$ sú konečnorozmerné vektorové priestory, nech $X$ je báza $V$, nech $Y$ je báza $U$. Nech $f: V \rightarrow U$ je lineárne zobrazenie. Potom pre každý vektor $\vec{v} \in V$ platí:
\[
[f(\vec{v})]_{Y} = [f]_{YX} [\vec{v}]_{X}
\]
\end{veta}

\begin{proof}
Označme $X=(\vec{x}_{1}, \dots, \vec{x}_{n})$.
Uvažujme najprv prípad, že $\vec{v}$ je priamo vektor z $X$, povedzme $\vec{v}=\vec{x}_{1}$. Zrejme $\vec{x}_{1} = 1\vec{x}_{1} + 0\vec{x}_{2} + \dots + 0\vec{x}_{n}$, teda súradnice $\vec{x}_{1}$ v báze $X$ sú $[\vec{x}_{1}]_{X} = (1, 0, \dots, 0) = \vec{e}_{1}$.

Počítajme, čomu je rovná pravá strana dokazovanej rovnosti pre $\vec{v}=\vec{x}_{1}$:
\[
[f]_{YX}[\vec{x}_{1}]_{X} = ([f(\vec{x}_{1})]_Y \dots [f(\vec{x}_{n})]_Y) 
\begin{pmatrix}
1 \\ 0 \\ \vdots \\ 0
\end{pmatrix}
= [f(\vec{x}_{1})]_Y
\]
to je ale presne prvý stĺpec matice $[f]_{YX}$. Zrejme to takto bude fungovať aj pre ostatné stĺpce (prvky bázy $X$), teda vidíme, že pre všetky $i=1,\dots,n$ máme:
\[
[f]_{YX}[\vec{x}_{i}]_{X} = [f(\vec{x}_{i})]_{Y}
\]

Uvažujme teraz ľubovoľný vektor $\vec{v} \in V$ a označíme jeho súradnice v báze $X$ ako $[\vec{v}]_{X} = (c_{1}, \dots, c_{n})$, čo vlastne znamená, že $\vec{v} = c_{1}\vec{x}_{1} + \dots + c_{n}\vec{x}_{n}$. Počítajme:
\begin{align*}
[f]_{YX}[\vec{v}]_{X} &= [f]_{YX}(c_{1}\vec{e}_{1} + \dots + c_{n}\vec{e}_{n}) \\
&= c_{1}([f]_{YX}\vec{e}_{1}) + \dots + c_{n}([f]_{YX}\vec{e}_{n}) \\
&= c_{1}[f(\vec{x}_{1})]_{Y} + \dots + c_{n}[f(\vec{x}_{n})]_{Y}
\end{align*}
Využili sme, že zobrazenie ,,násobenie vektora maticou zľava'' je lineárne.
Ďalej, keďže zobrazenie vektora na jeho súradnice je tiež lineárne, môžeme počítať
\begin{align*}
c_{1}[f(\vec{x}_{1})]_{Y} + \dots + c_{n}[f(\vec{x}_{n})]_{Y} &= [c_{1}f(\vec{x}_{1}) + \dots + c_{n}f(\vec{x}_{n})]_{Y} \\
&= [f(c_{1}\vec{x}_{1} + \dots + c_{n}\vec{x}_{n})]_{Y} \\
&= [f(\vec{v})]_{Y}
\end{align*}
V poslednom kroku sme využili, že $f$ je lineárne zobrazenie.
\end{proof}

Ukážeme si, ako Veta \ref{veta:akciaMatice} funguje na príklade:

\begin{priklad}
Uvažujme polynóm $p \in \R^{3}[x]$ daný predpisom $p(x) = -3x^{3} + 2x - 2$. Jeho súradnice v báze $X=(1, x, x^{2}, x^{3})$ sú $(-2, 2, 0, -3)$.
Uvažujme zobrazenie $d: \R^{3}[x] \rightarrow \R^{2}[x]$ ,,derivácia". Ak zvolíme bázu $Y=(1, x, x^{2})$ vektorového priestoru $\R^{2}[x]$, potom:
\[
[d(p)]_{Y} = [d]_{YX}[p]_{X} = 
\begin{pmatrix}
0 & 1 & 0 & 0 \\
0 & 0 & 2 & 0 \\
0 & 0 & 0 & 3
\end{pmatrix}
\begin{pmatrix}
-2 \\ 2 \\ 0 \\ -3
\end{pmatrix}
=
\begin{pmatrix}
2 \\ 0 \\ -9
\end{pmatrix}
\]
Čo sú súradnice polynómu $2 - 9x^{2}$ v báze $Y$. Zároveň $d(p) = p' = (-3x^{3} + 2x - 2)' = -9x^{2} + 2$, čiže všetko sedí.
\end{priklad}

Vetu \ref{veta:akciaMatice} môžeme vyjadriť kompaktne pomocou diagramu:
\[
\begin{tikzcd}
V \arrow[r, "f"] \arrow[d, "{[\_]_X}"'] & 
U \arrow[d, "{[\_]_Y}"] \\
\R^{n} \arrow[r, "{[f]_{YX}.\_}"'] & 
\R^{m}
\end{tikzcd}
\]

Veta \ref{veta:akciaMatice} potom znamená, že tento diagram \emph{komutuje}. Ak zložíme zobrazenia, ktoré sú na
obrázku reprezentované šípkami $\rightarrow \downarrow$, dostaneme rovnaké zobrazenie, ako keď zložíme zobrazenia
reprezentované šípkami $\downarrow \rightarrow$.

\subsection{Skladanie lineárnych zobrazení a násobenie matíc}

Uvažujme teraz tri konečnorozmerné vektorové priestory $V, U, W$ a dve lineárne zobrazenia $f: V \rightarrow U$, $g: U \rightarrow W$. Podľa Vety 12.2 je zobrazenie $g \circ f: V \rightarrow W$ lineárne.

Ak vyberieme v každom z priestorov nejaké bázy, každé zo zobrazení $f, g, g \circ f$ bude reprezentované nejakou maticou. Nasledujúca veta nám hovorí o vzťahu medzi týmito tromi maticami.

\begin{veta}
\label{veta:skladanieJeNasobenie}
Nech $V, U, W$ sú konečnorozmerné vektorové priestory, $f: V \rightarrow U$, $g: U \rightarrow W$ sú lineárne zobrazenia. $X$ je báza $V$, $Y$ je báza $U$, $Z$ je báza $W$. Potom:
\[
[g \circ f]_{ZX} = [g]_{ZY} [f]_{YX}
\]
(Skladanie zobrazení zodpovedá násobeniu matíc).
\end{veta}

\begin{proof}[Dôkaz]
Najskôr dokážeme, že pre každý vektor $\vec{v} \in V$ platí:
\[
[g \circ f]_{ZX} [\vec{v}]_{X} = [g]_{ZY} [f]_{YX} [\vec{v}]_{X}
\]
A naozaj, naľavo máme:
\[
[g \circ f]_{ZX} [\vec{v}]_{X} \overset{\ref{veta:akciaMatice}}{=} [(g \circ f)(\vec{v})]_{Z} = [g(f(\vec{v}))]_{Z}
\]
A napravo:
\[
[g]_{ZY} ([f]_{YX} [\vec{v}]_{X}) \overset{\text{\ref{veta:akciaMatice}}}{=} [g]_{ZY} [f(\vec{v})]_{Y} \overset{\text{\ref{veta:akciaMatice}}}{=} [g(f(\vec{v}))]_{Z}
\]
Označme teraz $A = [g \circ f]_{ZX}$ a $B = [g]_{ZY} [f]_{YX}$. Pre všetky $\vec{v} \in V$ je $A[\vec{v}]_{X} = B[\vec{v}]_{X}$.
Špeciálne pre $\vec{v} = \vec{x}_{i}$ (kde $X=(\vec{x}_{1}, \dots, \vec{x}_{n})$) máme $[\vec{x}_{i}]_{X} = \vec{e}_{i}$.
Súčin matice $A$ s $i$-tym stĺpcom $\vec{e}_{i}$ je $i$-ty stĺpec matice $A$.
Teda $A$ a $B$ majú rovnaký $i$-ty stĺpec pre všetky $i=1,\dots,n$, a teda sú to rovnaké matice.
\end{proof}

\begin{priklad}
Pozrime sa najprv na rovinné rotácie z príkladu 3. Zrejme pre dva uhly $\theta, \phi$ platí $l_{\phi} \circ l_{\theta} = l_{\phi + \theta}$ (najprv otočiť doľava o $\theta$ a potom ešte o $\phi$ je to isté, ako otočiť doľava o $\theta + \phi$).
Podľa Vety \ref{veta:akciaMatice} musí pre každú bázu $X$ platiť $[l_{\phi} \circ l_{\theta}]_{XX} = [l_{\phi}]_{XX} [l_{\theta}]_{XX}$.
Z toho dostávame maticovú rovnosť:
\[
\begin{pmatrix}
\cos(\phi+\theta) & -\sin(\phi+\theta) \\
\sin(\phi+\theta) & \cos(\phi+\theta)
\end{pmatrix}
=
\begin{pmatrix}
\cos\phi & -\sin\phi \\
\sin\phi & \cos\phi
\end{pmatrix}
\begin{pmatrix}
\cos\theta & -\sin\theta \\
\sin\theta & \cos\theta
\end{pmatrix}
\]
Po vynásobení matíc napravo dostaneme rovnosť matíc:
\[
\begin{pmatrix}
\cos(\phi+\theta) & -\sin(\phi+\theta) \\
\sin(\phi+\theta) & \cos(\phi+\theta)
\end{pmatrix}
=
\begin{pmatrix}
\cos\phi\cos\theta - \sin\phi\sin\theta & -\cos\phi\sin\theta - \sin\phi\cos\theta \\
\sin\phi\cos\theta + \cos\phi\sin\theta & -\sin\phi\sin\theta + \cos\phi\cos\theta
\end{pmatrix}
\]
Porovnaním prvkov v týchto maticiach dostaneme známe súčtové vzorce:
\begin{align*}
\cos(\phi+\theta) &= \cos\phi\cos\theta - \sin\phi\sin\theta \\
\sin(\phi+\theta) &= \sin\phi\cos\theta + \cos\phi\sin\theta
\end{align*}
\end{priklad}

\begin{priklad}
Pozrime sa opäť na projekciu $P_q$ z príkladu 6. Zrejme platí $P_q \circ P_q = P_q$.
(Pretože $P_q(\vec{v})$ je už na priamke $q$ a teda jeho pravouhlou projekciou na priamku $q$ je on sám).
Z tohto pozorovania a z Vety \ref{veta:skladanieJeNasobenie} máme:
\[
[P_q \circ P_q]_{XX} = [P_q]_{XX} [P_q]_{XX}
\]
Zároveň $[P_q \circ P_q]_{XX} = [P_q]_{XX}$. Teda musí platiť:
\[
\begin{pmatrix}
1/2 & 1/2 \\
1/2 & 1/2
\end{pmatrix}
\begin{pmatrix}
1/2 & 1/2 \\
1/2 & 1/2
\end{pmatrix}
=
\begin{pmatrix}
1/2 & 1/2 \\
1/2 & 1/2
\end{pmatrix}
\]
A to je naozaj pravda, ako sa môžete sami presvedčiť.
\end{priklad}

\subsection{Inverzné lineárne zobrazenie a inverzná matica}

\begin{veta}
\label{veta:inverznaMatica}
Nech $V, U$ sú konečnorozmerné vektorové priestory, nech $f$ je bijektívne lineárne zobrazenie $f: V \rightarrow U$. Nech $X$ je báza $V$, $Y$ je báza $U$. Potom matica $[f^{-1}]_{XY}$ je inverzná k matici $[f]_{YX}$.
\end{veta}

\begin{proof}[Dôkaz]
Máme dokázať, že $[f^{-1}]_{XY} [f]_{YX} = I$ a $[f]_{YX} [f^{-1}]_{XY} = I$.
Počítajme:
\[
[f^{-1}]_{XY} [f]_{YX} \overset{\text{\ref{veta:skladanieJeNasobenie}}}{=} [f^{-1} \circ f]_{XX} = [\id]_{XX} = I
\]
Druhá rovnosť sa dokáže rovnako.
\end{proof}

\begin{priklad}
Zrejme inverzné zobrazenie k rovinnej rotácii doľava o $\theta$ je rovinná rotácia doprava o $\theta$ (alebo, čo je to isté, rotácia doľava o záporný uhol $-\theta$).
Teda $l_{\theta}^{-1} = l_{-\theta}$. Podľa Vety 13.4 má byť matica $[l_{-\theta}]_{XX}$ inverzná k matici $[l_{\theta}]_{XX}$. Počítajme:
\[
[l_{-\theta}]_{XX} = 
\begin{pmatrix}
\cos(-\theta) & -\sin(-\theta) \\
\sin(-\theta) & \cos(-\theta)
\end{pmatrix}
=
\begin{pmatrix}
\cos\theta & \sin\theta \\
-\sin\theta & \cos\theta
\end{pmatrix}
\]
Skúška:
\begin{multline*}
\begin{pmatrix}
\cos\theta & \sin\theta \\
-\sin\theta & \cos\theta
\end{pmatrix}
\begin{pmatrix}
\cos\theta & -\sin\theta \\
\sin\theta & \cos\theta
\end{pmatrix}
=\\
\begin{pmatrix}
\cos^2\theta + \sin^2\theta & -\cos\theta\sin\theta + \sin\theta\cos\theta \\
-\sin\theta\cos\theta + \cos\theta\sin\theta & \sin^2\theta + \cos^2\theta
\end{pmatrix}
=
\begin{pmatrix}
1 & 0 \\
0 & 1
\end{pmatrix}
= I
\end{multline*}
\end{priklad}

\begin{priklad}
Pozrime sa opäť na lineárne zobrazenie $ev_{1,2,3}$ z príkladu 5.
Presvedčte sa, že je bijektívne (aký význam má, že je bijektívne?).
Inverzné zobrazenie k $ev_{1,2,3}: \R^{2}[x] \rightarrow \R^{3}$ je zobrazenie, ktoré priraďuje usporiadaným trojiciam reálnych čísel polynómy.
Má vlastnosti:
\[
ev_{1,2,3}^{-1} \circ ev_{1,2,3} = \id_{\R^{2}[x]}
\]
\[
ev_{1,2,3} \circ ev_{1,2,3}^{-1} = \id_{\R^{3}}
\]
To znamená, že ak vezmeme ľubovoľné $y_{1}, y_{2}, y_{3} \in \R$, tak $ev_{1,2,3}^{-1}(y_{1}, y_{2}, y_{3})$ je polynóm $p$, pre ktorý platí:
\[
ev_{1,2,3}(p) = (y_{1}, y_{2}, y_{3})
\]
Ale $ev_{1,2,3}(p) = (p(1), p(2), p(3))$, a teda $p(1)=y_{1}$, $p(2)=y_{2}$, $p(3)=y_{3}$.

Ak si teda zvolíme povedzme trojicu $(1, 2, 5)$, potom $ev_{1,2,3}^{-1}(1, 2, 5)$ musí byť polynóm $p \in \R^{2}[x]$, taký, že $p(1)=1, p(2)=2, p(3)=5$.

Maticu inverznú k $[ev_{1,2,3}]_{EX}$ môžeme vypočítať:
\[
([ev_{1,2,3}]_{EX})^{-1}=
\begin{pmatrix}
1 & 1 & 1 \\
1 & 2 & 4 \\
1 & 3 & 9
\end{pmatrix}^{-1}
=
\begin{pmatrix}
3 & -3 & 1 \\
-\frac{5}{2} & 4 & -\frac{3}{2} \\
\frac{1}{2} & -1 & \frac{1}{2}
\end{pmatrix}
\]
A podľa Vety 13.4 je to matica $[ev_{1,2,3}^{-1}]_{XE}$.
Ak vezmeme teraz napríklad vektor $\vec{v}=(1, 2, 5)$, potom
\[
[ev_{1,2,3}^{-1}(\vec{v})]_{X} = [ev_{1,2,3}^{-1}]_{XE}[\vec{v}]_{E}=
\begin{pmatrix}
3 & -3 & 1 \\
-\frac{5}{2} & 4 & -\frac{3}{2} \\
\frac{1}{2} & -1 & \frac{1}{2}
\end{pmatrix}
\begin{pmatrix} 1\\2\\5
\end{pmatrix}
=
\begin{pmatrix}
2\\-2\\1
\end{pmatrix}
\]
čo sú súradnice polynómu $p(x) = x^2 - 2x + 2$ v báze $X$.
A naozaj máme $p(1)=1, p(2)=2, p(3)=5$ pre tento polynóm $p$.
\end{priklad}
