<!-- # Обязательное приложение \label{app:A}
Test app A

# Примеры кода/таблиц/исходников \label{app:B}
## Подраздел приложения \label{app:B1}
## test Б2 \label{app:B2}
%#### test \label{app:B4}
## test Б4 \label{app:B4}
## test Б5 \label{app:B5}
test tab

/Dissertation/md/files/table_test.csv  'Tab1\label{tab:tab1}'

\listoftodos

# Примеры кода на \LaTeX и `markdown`

And now^[with `markdown` v2.4] you can also use inlined footnotes with^[inlineFootnotes].

| Right | Left | Default | Center |
|------:|:-----|:--------|:------:|
|    12 | 12   | 12      |   12   |
|   123 | 123  | 123     |  123   |
|     1 | 1    | 1       |   1    |
: Demonstration of pipe table syntax

Here is [my link][FOO]
[Foo]: /bar/baz

See [my website][].
[my website]: http://foo.bar.baz

**Term 1**
Definition 1
: test pic test~\ref{fig:test}
: test pic test2~\ref{fig:test2}
Term 2 with *inline markup*
: Definition 2
: Here we can reference\textbf{Figure~\ref{fig:test}}

Term 1
: Definition 1 Table 1~\ref{tab:tab1}
Term 2 with *inline markup*
: Definition 2

Here's our logo (hover to see the title text):

Inline-style:
\setkeys{Gin}{width=0.5\linewidth}
![test](123.png "Logo Title test2")

other one:
\setkeys{Gin}{width=\linewidth}
![test2](123.png "Logo Title test2")

\setkeys{Gin}{width=.5\linewidth}
![exampleimage](123.png "An exemplary image")

\section{Форматирование текста}\label{sec:ch1/sec1}

Мы можем сделать \textbf{жирный текст} и \textit{курсив}.

\section{Ссылки}\label{sec:ch1/sec2}

Ссылки на собственные работы:~\cite{vakbib1, confbib1}.
Сошлёмся на приложения: Приложение~\cref{app:A}, Приложение~\cref{app:B2}.
%Сошлёмся на формулу: формула~\cref{eq:equation1}.
Сошлёмся на изображение: рисунок~\cref{fig:test}.

Стандартной практикой является добавление к ссылкам префикса, характеризующего тип элемента.
Это не является строгим требованием, но~позволяет лучше ориентироваться в документах большого размера.
Например, для ссылок на~рисунки используется префикс \textit{fig},
для ссылки на~таблицу "--- \textit{tab}.

В таблице 1 \cref{tab:tab1} приложения B4~\cref{app:B4} приложения B5~\cref{app:B5} приведён список рекомендуемых
к использованию стандартных префиксов. -->