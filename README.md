# ProjectElectricJava
Dimensionamento Elétrico Residencial Desenvolvido Em Java
\documentclass[a4paper,12pt]{article}
\usepackage[top=2cm, bottom=2cm, left=2.5cm, right=2.5cm]{geometry}

\usepackage{subfiles}
\usepackage[brazilian]{babel}
\usepackage{color}
\usepackage{graphicx}
\usepackage{cite}

\begin{document}
%\title{Dimencionamendo Elétrico}
%\author{Tulio Gomides De Souza}
%\date{\today}
%\maketitle
\section{Introdução}

\hspace{0.7cm} Imdispensável para maior parte da populção a utilização de energia elétrica. É essa energia que nos auxilia nos afazeres domésticos, nos deixa mais confortáveis em nossas casas, nos permite conversarmos com quem está distante e também nos proporciona lazer.

	Mas se uma instalação elétrica for mal dimencionada a mesma pode proporcinar grande perigo de acidentes que podem levar a obtos em situações mais graves, para sanar quande partes destes problemas existem normas para a instalação da rede elétrica.

\section{Levantamento de cargas elétricas}

\hspace{0.7cm} Para se instalar uma rede elétrica é necessário, um levantamento de cargas elétricas correta do local.

	O mesmo é feito uma previsão das a potências mínimas de iluminação e tomadas a serem instaladas no local, possibilitando determinar a potência total aparente, ativa e reativa da rede eletrica.

\section{Potência Aparente}
\hspace{0.7cm}  É o produto da ação da tensão e da corrente, sua unidade de medida é o Volt-Ampère (VA).
	
\section{Potência Ativa}

\hspace{0.7cm} É a parte da potência aparente que é transformada em potência mecânica, térmica ou luminosa, tendo como unidade de media o Watt(W).

\section{Potência Reativa}

\hspace{0.7cm} É a parte da potência aparente que é transformada em um campo magnético, tendo como unidade de media o Volt-Ampère (VAr).

\section{Fator De Potencia}

\hspace{0.7cm} Sendo a potência de ativa uma parcela de potência aparente, pode-se dizer que a mesma representa uma porcentagem da potência aparente que é transformada em potÊncia mecânica, termica ou luminosa.

	A isso damos o nome de fator de potência, nos projetos resindeciais, desejando-se saber o quanto da potência aparente foi transformada em potência ativa, aplica-se os seguintes valores de fotor de potência:
	
	Fator \textbf{1,0} para lâmpadas e \textbf{0,8} para tomadas de uso geral, a razão disto é que numa lâmpada toda sua potência é ativa então sua potência reativa é zero, então 100\% da potência aparente é transfomada em ativa, e em um aparelho de tomada a perdas em sua potência em media cerca de 80\% da mesma é transformada em ativa.
	
\section{Levantamento Da Carga De Iluminação}

\hspace{0.7cm}\textbf{ Recomendações da NBR 5410:2004.}

\subsection{Condições para se estabelecer a quantidade mínima de pontos de luz}

\begin{tabular}{|c|c|}
\hline 
\multicolumn{2}{|c|}{Prever pelo menos um ponto de luz no teto,comandado por um interruptor de parede} \\ 
\hline 
\multicolumn{2}{|c|}{Arandelas no banheiro devem estar distantes no mínimo, 60cm do limite do box } \\ 
\hline 
\end{tabular} 

\subsection{Condições para se estabelecer a potência mínima de iluminção}

\hspace{0.7cm} A carga de iluminção é feita em função a área do cômodo a ser dimencionado.

	Para área igual ou inferior a 6m² $\Longrightarrow$ Atribuir um mínimo de 100 VA.
	
	Para área superior a 6m² $\Longrightarrow$ Atribuir um mínimo de 100 VA para os primeiros 6m², acrescido de 60 VA para cada aumento de 4m² inteiros.
	
	\textbf{\textit{Nota: }} A NBR 5410:2004 não estabelece criterios para iluminação de áreas externas em recidências, ficando a cargo do projetista e do cliente.
	
\subsection{Exemplo dos calculos para carga de ilumonação}

\begin{tabular}{|c|c|c|c|}
\hline 
Dependências & Dimensões área (m²) & \multicolumn{2}{c|}{Potência de iluminação (VA)} \\ 
\hline 
Sala & A = 3,25 x 3,05 = 9,91 & 9,91 = 6 + $\overline{\textbf{3,91}}$ & 100 \\ 
\hline 
Copa & A = 3,10 x 3,05 = 9,45 & 9,45 = 6 + $\overline{\textbf{3,45}}$ & 100 \\ 
\hline 
Cozinha & A = 3,45 x 3,05 = 11,43 & 11,43 = 6 + 4 + $\overline{\textbf{1,43}}$ & 160 \\ 
\hline 
Dormitorio & A = 3,15 x 3,40 = 10,71 & 10,71 = 6 + 4 + $\overline{\textbf{0,71}}$ & 160 \\ 
\hline 
Banho & A = 1,80 x 2,30 = 4,14 & 4,14 $\rightarrow$ 100 & 100 \\ 
\hline 
Área de Serviço & A = 1,75 x 3,40 = 5,95 & 5,95 $\rightarrow$ 100 & 100 \\ 
\hline 
hall& A = 1,80 x 1,00 = 1,80 & 1,80 $\rightarrow$ 100  & 100 \\ 
\hline 
Área externa & - & - & 100 \\ 
\hline 
\end{tabular} 

\section{Levantamento Da Carga De Tomadas}

\hspace{0.7cm}\textbf{ Recomendações da NBR 5410:2004.}

\subsection{Condições para se estabelecer a quantidade mínima de pontos de tomadas}

\begin{tabular}{|c|}
\hline 
Ponto de tomada é o ponto onde a conexão do equipamento à instalação elétrica é feita \\ através de tomada corrente.O mesmo pode ter uma ou mais tomadas de corrente \\ 
\hline 
\end{tabular} 
\end{document}