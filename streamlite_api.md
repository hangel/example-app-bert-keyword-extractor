<div class="content container_ContentContainer__3105j">
<a name="api-reference" class="headerLink_HashLink___Wih5">
</a>
<h1 class="headerLink_HeaderContainer__68tak group">
<a aria-hidden="true" tabindex="-1" href="#api-reference">
<span class="icon icon-link">
</span>
</a>
API reference<div class="headerLink_CopyLink__Lvpqb">
<svg width="14" height="17" viewBox="0 0 14 17" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M10.7548 0.0313721C10.7051 0.0194702 10.6571 0.00793457 10.609 0H9.87278C9.83686 0.0178223 9.81891 0.0356445 9.783 0.0356445C9.20842 0.124878 8.70565 0.374573 8.29268 0.784851L4.14488 4.90521C3.57029 5.47601 3.283 6.18951 3.31892 7.01001C3.33686 7.38464 3.42665 7.74133 3.60621 8.09808L4.43217 7.27759C4.46809 7.25977 4.46809 7.18842 4.46809 7.15271C4.41421 6.59979 4.57582 6.11816 4.97085 5.72577L8.54405 2.17615L9.13659 1.58752C9.76504 0.998901 10.7167 0.998901 11.3452 1.58752C12.0095 2.21179 12.0095 3.2464 11.3452 3.90637L7.25123 7.97327C6.8562 8.36566 6.38936 8.54401 5.83273 8.49054C5.77885 8.47266 5.72499 8.47272 5.68908 8.50836L4.86311 9.32886C4.95289 9.36456 5.00676 9.40021 5.06062 9.41803C6.15593 9.81049 7.17941 9.66779 8.02333 8.84729C9.45979 7.45599 10.8783 6.06464 12.2609 4.6377C13.7333 3.12152 12.9971 0.606445 10.9501 0.0713501C10.8805 0.0614624 10.8164 0.0461426 10.7548 0.0313721ZM7.34082 7.47388C7.62811 7.2063 7.9154 6.9209 8.20269 6.6355C8.18016 6.62988 8.16114 6.62427 8.14401 6.6192C8.10655 6.60822 8.07805 6.59985 8.04109 6.59985C7.03556 6.15393 5.83253 6.3501 5.04246 7.11713C3.606 8.52625 2.1875 9.93542 0.768994 11.3624C0.14053 11.9867 -0.0928837 12.7715 0.032803 13.6277C0.194409 14.7515 0.840817 15.5184 1.9002 15.8752C2.97755 16.2319 3.94717 16.0001 4.75517 15.2152C5.6766 14.3118 6.59005 13.4004 7.50616 12.4864C7.96467 12.0289 8.42384 11.5708 8.88501 11.1127C9.56733 10.4348 9.81871 9.61432 9.67506 8.66895C9.63916 8.41925 9.56733 8.16949 9.42369 7.9198C9.13639 8.2052 8.8491 8.47272 8.57975 8.75812C8.54385 8.776 8.54385 8.84735 8.54385 8.90082C8.61567 9.41809 8.47203 9.8819 8.09495 10.2565C6.71235 11.6478 5.31181 13.0391 3.91125 14.4125C3.51623 14.8228 2.99551 14.9655 2.43889 14.8406C1.81042 14.6979 1.4154 14.3234 1.23584 13.7347C1.05629 13.1282 1.19993 12.5753 1.64882 12.1294C2.34011 11.4337 3.03141 10.747 3.72271 10.0603C4.41401 9.37354 5.10531 8.68677 5.79661 7.99115C6.17369 7.59869 6.65849 7.45599 7.19717 7.50952C7.25103 7.50952 7.3049 7.50952 7.34082 7.47388Z" fill="#808495">
</path>
</svg>
</div>
</h1>
<p>
Streamlit makes it easy for you to visualize, mutate, and share data. The API
reference is organized by activity type, like displaying data or optimizing
performance. Each section includes methods associated with the activity type,
including examples.</p>
<p>
Browse our API below and click to learn more about any of our available commands! 🎈</p>
<a name="display-almost-anything" class="headerLink_HashLink___Wih5">
</a>
<h2 class="headerLink_HeaderContainer__68tak group">
<a aria-hidden="true" tabindex="-1" href="#display-almost-anything">
<span class="icon icon-link">
</span>
</a>
Display almost anything<div class="headerLink_CopyLink__Lvpqb">
<svg width="14" height="17" viewBox="0 0 14 17" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M10.7548 0.0313721C10.7051 0.0194702 10.6571 0.00793457 10.609 0H9.87278C9.83686 0.0178223 9.81891 0.0356445 9.783 0.0356445C9.20842 0.124878 8.70565 0.374573 8.29268 0.784851L4.14488 4.90521C3.57029 5.47601 3.283 6.18951 3.31892 7.01001C3.33686 7.38464 3.42665 7.74133 3.60621 8.09808L4.43217 7.27759C4.46809 7.25977 4.46809 7.18842 4.46809 7.15271C4.41421 6.59979 4.57582 6.11816 4.97085 5.72577L8.54405 2.17615L9.13659 1.58752C9.76504 0.998901 10.7167 0.998901 11.3452 1.58752C12.0095 2.21179 12.0095 3.2464 11.3452 3.90637L7.25123 7.97327C6.8562 8.36566 6.38936 8.54401 5.83273 8.49054C5.77885 8.47266 5.72499 8.47272 5.68908 8.50836L4.86311 9.32886C4.95289 9.36456 5.00676 9.40021 5.06062 9.41803C6.15593 9.81049 7.17941 9.66779 8.02333 8.84729C9.45979 7.45599 10.8783 6.06464 12.2609 4.6377C13.7333 3.12152 12.9971 0.606445 10.9501 0.0713501C10.8805 0.0614624 10.8164 0.0461426 10.7548 0.0313721ZM7.34082 7.47388C7.62811 7.2063 7.9154 6.9209 8.20269 6.6355C8.18016 6.62988 8.16114 6.62427 8.14401 6.6192C8.10655 6.60822 8.07805 6.59985 8.04109 6.59985C7.03556 6.15393 5.83253 6.3501 5.04246 7.11713C3.606 8.52625 2.1875 9.93542 0.768994 11.3624C0.14053 11.9867 -0.0928837 12.7715 0.032803 13.6277C0.194409 14.7515 0.840817 15.5184 1.9002 15.8752C2.97755 16.2319 3.94717 16.0001 4.75517 15.2152C5.6766 14.3118 6.59005 13.4004 7.50616 12.4864C7.96467 12.0289 8.42384 11.5708 8.88501 11.1127C9.56733 10.4348 9.81871 9.61432 9.67506 8.66895C9.63916 8.41925 9.56733 8.16949 9.42369 7.9198C9.13639 8.2052 8.8491 8.47272 8.57975 8.75812C8.54385 8.776 8.54385 8.84735 8.54385 8.90082C8.61567 9.41809 8.47203 9.8819 8.09495 10.2565C6.71235 11.6478 5.31181 13.0391 3.91125 14.4125C3.51623 14.8228 2.99551 14.9655 2.43889 14.8406C1.81042 14.6979 1.4154 14.3234 1.23584 13.7347C1.05629 13.1282 1.19993 12.5753 1.64882 12.1294C2.34011 11.4337 3.03141 10.747 3.72271 10.0603C4.41401 9.37354 5.10531 8.68677 5.79661 7.99115C6.17369 7.59869 6.65849 7.45599 7.19717 7.50952C7.25103 7.50952 7.3049 7.50952 7.34082 7.47388Z" fill="#808495">
</path>
</svg>
</div>
</h2>
<section class="tileContainer_Container__qZUK_">
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/write-magic/st.write">
<h4 id="stwrite">
<a aria-hidden="true" tabindex="-1" href="#stwrite">
<span class="icon icon-link">
</span>
</a>
st.write</h4>
<p>
Write arguments to the app.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
write<span class="token punctuation">
(</span>
<span class="token string">
"Hello **world**!"</span>
<span class="token punctuation">
)</span>

st<span class="token punctuation">
.</span>
write<span class="token punctuation">
(</span>
my_data_frame<span class="token punctuation">
)</span>

st<span class="token punctuation">
.</span>
write<span class="token punctuation">
(</span>
my_mpl_figure<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/write-magic/magic">
<h4 id="magic">
<a aria-hidden="true" tabindex="-1" href="#magic">
<span class="icon icon-link">
</span>
</a>
Magic</h4>
<p>
Any time Streamlit sees either a variable or literal value on its own line, it automatically writes that to your app using <code>
st.write</code>
</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
<span class="token string">
"Hello **world**!"</span>

my_data_frame
my_mpl_figure</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
</section>
<a name="text-elements" class="headerLink_HashLink___Wih5">
</a>
<h2 class="headerLink_HeaderContainer__68tak group">
<a aria-hidden="true" tabindex="-1" href="#text-elements">
<span class="icon icon-link">
</span>
</a>
Text elements<div class="headerLink_CopyLink__Lvpqb">
<svg width="14" height="17" viewBox="0 0 14 17" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M10.7548 0.0313721C10.7051 0.0194702 10.6571 0.00793457 10.609 0H9.87278C9.83686 0.0178223 9.81891 0.0356445 9.783 0.0356445C9.20842 0.124878 8.70565 0.374573 8.29268 0.784851L4.14488 4.90521C3.57029 5.47601 3.283 6.18951 3.31892 7.01001C3.33686 7.38464 3.42665 7.74133 3.60621 8.09808L4.43217 7.27759C4.46809 7.25977 4.46809 7.18842 4.46809 7.15271C4.41421 6.59979 4.57582 6.11816 4.97085 5.72577L8.54405 2.17615L9.13659 1.58752C9.76504 0.998901 10.7167 0.998901 11.3452 1.58752C12.0095 2.21179 12.0095 3.2464 11.3452 3.90637L7.25123 7.97327C6.8562 8.36566 6.38936 8.54401 5.83273 8.49054C5.77885 8.47266 5.72499 8.47272 5.68908 8.50836L4.86311 9.32886C4.95289 9.36456 5.00676 9.40021 5.06062 9.41803C6.15593 9.81049 7.17941 9.66779 8.02333 8.84729C9.45979 7.45599 10.8783 6.06464 12.2609 4.6377C13.7333 3.12152 12.9971 0.606445 10.9501 0.0713501C10.8805 0.0614624 10.8164 0.0461426 10.7548 0.0313721ZM7.34082 7.47388C7.62811 7.2063 7.9154 6.9209 8.20269 6.6355C8.18016 6.62988 8.16114 6.62427 8.14401 6.6192C8.10655 6.60822 8.07805 6.59985 8.04109 6.59985C7.03556 6.15393 5.83253 6.3501 5.04246 7.11713C3.606 8.52625 2.1875 9.93542 0.768994 11.3624C0.14053 11.9867 -0.0928837 12.7715 0.032803 13.6277C0.194409 14.7515 0.840817 15.5184 1.9002 15.8752C2.97755 16.2319 3.94717 16.0001 4.75517 15.2152C5.6766 14.3118 6.59005 13.4004 7.50616 12.4864C7.96467 12.0289 8.42384 11.5708 8.88501 11.1127C9.56733 10.4348 9.81871 9.61432 9.67506 8.66895C9.63916 8.41925 9.56733 8.16949 9.42369 7.9198C9.13639 8.2052 8.8491 8.47272 8.57975 8.75812C8.54385 8.776 8.54385 8.84735 8.54385 8.90082C8.61567 9.41809 8.47203 9.8819 8.09495 10.2565C6.71235 11.6478 5.31181 13.0391 3.91125 14.4125C3.51623 14.8228 2.99551 14.9655 2.43889 14.8406C1.81042 14.6979 1.4154 14.3234 1.23584 13.7347C1.05629 13.1282 1.19993 12.5753 1.64882 12.1294C2.34011 11.4337 3.03141 10.747 3.72271 10.0603C4.41401 9.37354 5.10531 8.68677 5.79661 7.99115C6.17369 7.59869 6.65849 7.45599 7.19717 7.50952C7.25103 7.50952 7.3049 7.50952 7.34082 7.47388Z" fill="#808495">
</path>
</svg>
</div>
</h2>
<section class="tileContainer_Container__qZUK_">
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/text/st.markdown">
<img src="https://docs.streamlit.io/images/api/markdown.jpg" alt="screenshot">
<h4 id="markdown">
<a aria-hidden="true" tabindex="-1" href="#markdown">
<span class="icon icon-link">
</span>
</a>
Markdown</h4>
<p>
Display string formatted as Markdown.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
markdown<span class="token punctuation">
(</span>
<span class="token string">
"Hello **world**!"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/text/st.title">
<img src="https://docs.streamlit.io/images/api/title.jpg" alt="screenshot">
<h4 id="title">
<a aria-hidden="true" tabindex="-1" href="#title">
<span class="icon icon-link">
</span>
</a>
Title</h4>
<p>
Display text in title formatting.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
title<span class="token punctuation">
(</span>
<span class="token string">
"The app title"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/text/st.header">
<img src="https://docs.streamlit.io/images/api/header.jpg" alt="screenshot">
<h4 id="header">
<a aria-hidden="true" tabindex="-1" href="#header">
<span class="icon icon-link">
</span>
</a>
Header</h4>
<p>
Display text in header formatting.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
header<span class="token punctuation">
(</span>
<span class="token string">
"This is a header"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/text/st.subheader">
<img src="https://docs.streamlit.io/images/api/subheader.jpg" alt="screenshot">
<h4 id="subheader">
<a aria-hidden="true" tabindex="-1" href="#subheader">
<span class="icon icon-link">
</span>
</a>
Subheader</h4>
<p>
Display text in subheader formatting.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
subheader<span class="token punctuation">
(</span>
<span class="token string">
"This is a subheader"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/text/st.caption">
<img src="https://docs.streamlit.io/images/api/caption.jpg" alt="screenshot">
<h4 id="caption">
<a aria-hidden="true" tabindex="-1" href="#caption">
<span class="icon icon-link">
</span>
</a>
Caption</h4>
<p>
Display text in small font.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
caption<span class="token punctuation">
(</span>
<span class="token string">
"This is written small caption text"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/text/st.code">
<img src="https://docs.streamlit.io/images/api/code.jpg" alt="screenshot">
<h4 id="code-block">
<a aria-hidden="true" tabindex="-1" href="#code-block">
<span class="icon icon-link">
</span>
</a>
Code block</h4>
<p>
Display a code block with optional syntax highlighting.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
code<span class="token punctuation">
(</span>
<span class="token string">
"a = 1234"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/text/st.text">
<img src="https://docs.streamlit.io/images/api/text.jpg" alt="screenshot">
<h4 id="preformatted-text">
<a aria-hidden="true" tabindex="-1" href="#preformatted-text">
<span class="icon icon-link">
</span>
</a>
Preformatted text</h4>
<p>
Write fixed-width and preformatted text.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
text<span class="token punctuation">
(</span>
<span class="token string">
"Hello world"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/text/st.latex">
<img src="https://docs.streamlit.io/images/api/latex.jpg" alt="screenshot">
<h4 id="latex">
<a aria-hidden="true" tabindex="-1" href="#latex">
<span class="icon icon-link">
</span>
</a>
LaTeX</h4>
<p>
Display mathematical expressions formatted as LaTeX.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
latex<span class="token punctuation">
(</span>
<span class="token string">
"\int a x^2 \,dx"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
</section>
<a name="data-display-elements" class="headerLink_HashLink___Wih5">
</a>
<h2 class="headerLink_HeaderContainer__68tak group">
<a aria-hidden="true" tabindex="-1" href="#data-display-elements">
<span class="icon icon-link">
</span>
</a>
Data display elements<div class="headerLink_CopyLink__Lvpqb">
<svg width="14" height="17" viewBox="0 0 14 17" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M10.7548 0.0313721C10.7051 0.0194702 10.6571 0.00793457 10.609 0H9.87278C9.83686 0.0178223 9.81891 0.0356445 9.783 0.0356445C9.20842 0.124878 8.70565 0.374573 8.29268 0.784851L4.14488 4.90521C3.57029 5.47601 3.283 6.18951 3.31892 7.01001C3.33686 7.38464 3.42665 7.74133 3.60621 8.09808L4.43217 7.27759C4.46809 7.25977 4.46809 7.18842 4.46809 7.15271C4.41421 6.59979 4.57582 6.11816 4.97085 5.72577L8.54405 2.17615L9.13659 1.58752C9.76504 0.998901 10.7167 0.998901 11.3452 1.58752C12.0095 2.21179 12.0095 3.2464 11.3452 3.90637L7.25123 7.97327C6.8562 8.36566 6.38936 8.54401 5.83273 8.49054C5.77885 8.47266 5.72499 8.47272 5.68908 8.50836L4.86311 9.32886C4.95289 9.36456 5.00676 9.40021 5.06062 9.41803C6.15593 9.81049 7.17941 9.66779 8.02333 8.84729C9.45979 7.45599 10.8783 6.06464 12.2609 4.6377C13.7333 3.12152 12.9971 0.606445 10.9501 0.0713501C10.8805 0.0614624 10.8164 0.0461426 10.7548 0.0313721ZM7.34082 7.47388C7.62811 7.2063 7.9154 6.9209 8.20269 6.6355C8.18016 6.62988 8.16114 6.62427 8.14401 6.6192C8.10655 6.60822 8.07805 6.59985 8.04109 6.59985C7.03556 6.15393 5.83253 6.3501 5.04246 7.11713C3.606 8.52625 2.1875 9.93542 0.768994 11.3624C0.14053 11.9867 -0.0928837 12.7715 0.032803 13.6277C0.194409 14.7515 0.840817 15.5184 1.9002 15.8752C2.97755 16.2319 3.94717 16.0001 4.75517 15.2152C5.6766 14.3118 6.59005 13.4004 7.50616 12.4864C7.96467 12.0289 8.42384 11.5708 8.88501 11.1127C9.56733 10.4348 9.81871 9.61432 9.67506 8.66895C9.63916 8.41925 9.56733 8.16949 9.42369 7.9198C9.13639 8.2052 8.8491 8.47272 8.57975 8.75812C8.54385 8.776 8.54385 8.84735 8.54385 8.90082C8.61567 9.41809 8.47203 9.8819 8.09495 10.2565C6.71235 11.6478 5.31181 13.0391 3.91125 14.4125C3.51623 14.8228 2.99551 14.9655 2.43889 14.8406C1.81042 14.6979 1.4154 14.3234 1.23584 13.7347C1.05629 13.1282 1.19993 12.5753 1.64882 12.1294C2.34011 11.4337 3.03141 10.747 3.72271 10.0603C4.41401 9.37354 5.10531 8.68677 5.79661 7.99115C6.17369 7.59869 6.65849 7.45599 7.19717 7.50952C7.25103 7.50952 7.3049 7.50952 7.34082 7.47388Z" fill="#808495">
</path>
</svg>
</div>
</h2>
<section class="tileContainer_Container__qZUK_">
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/data/st.dataframe">
<img src="https://docs.streamlit.io/images/api/dataframe.jpg" alt="screenshot">
<h4 id="dataframes">
<a aria-hidden="true" tabindex="-1" href="#dataframes">
<span class="icon icon-link">
</span>
</a>
Dataframes</h4>
<p>
Display a dataframe as an interactive table.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
dataframe<span class="token punctuation">
(</span>
my_data_frame<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/data/st.table">
<img src="https://docs.streamlit.io/images/api/table.jpg" alt="screenshot">
<h4 id="static-tables">
<a aria-hidden="true" tabindex="-1" href="#static-tables">
<span class="icon icon-link">
</span>
</a>
Static tables</h4>
<p>
Display a static table.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
table<span class="token punctuation">
(</span>
my_data_frame<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/data/st.metric">
<img src="https://docs.streamlit.io/images/api/metric.jpg" alt="screenshot">
<h4 id="metrics">
<a aria-hidden="true" tabindex="-1" href="#metrics">
<span class="icon icon-link">
</span>
</a>
Metrics</h4>
<p>
Display a metric in big bold font, with an optional indicator of how the metric changed.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
metric<span class="token punctuation">
(</span>
<span class="token string">
"My metric"</span>
<span class="token punctuation">
,</span>
 <span class="token number">
42</span>
<span class="token punctuation">
,</span>
 <span class="token number">
2</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/data/st.json">
<img src="https://docs.streamlit.io/images/api/json.jpg" alt="screenshot">
<h4 id="dicts-and-json">
<a aria-hidden="true" tabindex="-1" href="#dicts-and-json">
<span class="icon icon-link">
</span>
</a>
Dicts and JSON</h4>
<p>
Display object or string as a pretty-printed JSON string.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
json<span class="token punctuation">
(</span>
my_data_frame<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
</section>
<a name="chart-elements" class="headerLink_HashLink___Wih5">
</a>
<h2 class="headerLink_HeaderContainer__68tak group">
<a aria-hidden="true" tabindex="-1" href="#chart-elements">
<span class="icon icon-link">
</span>
</a>
Chart elements<div class="headerLink_CopyLink__Lvpqb">
<svg width="14" height="17" viewBox="0 0 14 17" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M10.7548 0.0313721C10.7051 0.0194702 10.6571 0.00793457 10.609 0H9.87278C9.83686 0.0178223 9.81891 0.0356445 9.783 0.0356445C9.20842 0.124878 8.70565 0.374573 8.29268 0.784851L4.14488 4.90521C3.57029 5.47601 3.283 6.18951 3.31892 7.01001C3.33686 7.38464 3.42665 7.74133 3.60621 8.09808L4.43217 7.27759C4.46809 7.25977 4.46809 7.18842 4.46809 7.15271C4.41421 6.59979 4.57582 6.11816 4.97085 5.72577L8.54405 2.17615L9.13659 1.58752C9.76504 0.998901 10.7167 0.998901 11.3452 1.58752C12.0095 2.21179 12.0095 3.2464 11.3452 3.90637L7.25123 7.97327C6.8562 8.36566 6.38936 8.54401 5.83273 8.49054C5.77885 8.47266 5.72499 8.47272 5.68908 8.50836L4.86311 9.32886C4.95289 9.36456 5.00676 9.40021 5.06062 9.41803C6.15593 9.81049 7.17941 9.66779 8.02333 8.84729C9.45979 7.45599 10.8783 6.06464 12.2609 4.6377C13.7333 3.12152 12.9971 0.606445 10.9501 0.0713501C10.8805 0.0614624 10.8164 0.0461426 10.7548 0.0313721ZM7.34082 7.47388C7.62811 7.2063 7.9154 6.9209 8.20269 6.6355C8.18016 6.62988 8.16114 6.62427 8.14401 6.6192C8.10655 6.60822 8.07805 6.59985 8.04109 6.59985C7.03556 6.15393 5.83253 6.3501 5.04246 7.11713C3.606 8.52625 2.1875 9.93542 0.768994 11.3624C0.14053 11.9867 -0.0928837 12.7715 0.032803 13.6277C0.194409 14.7515 0.840817 15.5184 1.9002 15.8752C2.97755 16.2319 3.94717 16.0001 4.75517 15.2152C5.6766 14.3118 6.59005 13.4004 7.50616 12.4864C7.96467 12.0289 8.42384 11.5708 8.88501 11.1127C9.56733 10.4348 9.81871 9.61432 9.67506 8.66895C9.63916 8.41925 9.56733 8.16949 9.42369 7.9198C9.13639 8.2052 8.8491 8.47272 8.57975 8.75812C8.54385 8.776 8.54385 8.84735 8.54385 8.90082C8.61567 9.41809 8.47203 9.8819 8.09495 10.2565C6.71235 11.6478 5.31181 13.0391 3.91125 14.4125C3.51623 14.8228 2.99551 14.9655 2.43889 14.8406C1.81042 14.6979 1.4154 14.3234 1.23584 13.7347C1.05629 13.1282 1.19993 12.5753 1.64882 12.1294C2.34011 11.4337 3.03141 10.747 3.72271 10.0603C4.41401 9.37354 5.10531 8.68677 5.79661 7.99115C6.17369 7.59869 6.65849 7.45599 7.19717 7.50952C7.25103 7.50952 7.3049 7.50952 7.34082 7.47388Z" fill="#808495">
</path>
</svg>
</div>
</h2>
<section class="tileContainer_Container__qZUK_">
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/charts/st.line_chart">
<img src="https://docs.streamlit.io/images/api/line_chart.jpg" alt="screenshot">
<h4 id="simple-line-charts">
<a aria-hidden="true" tabindex="-1" href="#simple-line-charts">
<span class="icon icon-link">
</span>
</a>
Simple line charts</h4>
<p>
Display a line chart.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
line_chart<span class="token punctuation">
(</span>
my_data_frame<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/charts/st.area_chart">
<img src="https://docs.streamlit.io/images/api/area_chart.jpg" alt="screenshot">
<h4 id="simple-area-charts">
<a aria-hidden="true" tabindex="-1" href="#simple-area-charts">
<span class="icon icon-link">
</span>
</a>
Simple area charts</h4>
<p>
Display an area chart.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
area_chart<span class="token punctuation">
(</span>
my_data_frame<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/charts/st.bar_chart">
<img src="https://docs.streamlit.io/images/api/bar_chart.jpg" alt="screenshot">
<h4 id="simple-bar-charts">
<a aria-hidden="true" tabindex="-1" href="#simple-bar-charts">
<span class="icon icon-link">
</span>
</a>
Simple bar charts</h4>
<p>
Display a bar chart.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
bar_chart<span class="token punctuation">
(</span>
my_data_frame<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/charts/st.map">
<img src="https://docs.streamlit.io/images/api/map.jpg" alt="screenshot">
<h4 id="scatterplots-on-maps">
<a aria-hidden="true" tabindex="-1" href="#scatterplots-on-maps">
<span class="icon icon-link">
</span>
</a>
Scatterplots on maps</h4>
<p>
Display a map with points on it.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
<span class="token builtin">
map</span>
<span class="token punctuation">
(</span>
my_data_frame<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/charts/st.pyplot">
<img src="https://docs.streamlit.io/images/api/pyplot.jpg" alt="screenshot">
<h4 id="matplotlib">
<a aria-hidden="true" tabindex="-1" href="#matplotlib">
<span class="icon icon-link">
</span>
</a>
Matplotlib</h4>
<p>
Display a matplotlib.pyplot figure.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
pyplot<span class="token punctuation">
(</span>
my_mpl_figure<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/charts/st.altair_chart">
<img src="https://docs.streamlit.io/images/api/vega_lite_chart.jpg" alt="screenshot">
<h4 id="altair">
<a aria-hidden="true" tabindex="-1" href="#altair">
<span class="icon icon-link">
</span>
</a>
Altair</h4>
<p>
Display a chart using the Altair library.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
altair_chart<span class="token punctuation">
(</span>
my_altair_chart<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/charts/st.vega_lite_chart">
<img src="https://docs.streamlit.io/images/api/vega_lite_chart.jpg" alt="screenshot">
<h4 id="vega-lite">
<a aria-hidden="true" tabindex="-1" href="#vega-lite">
<span class="icon icon-link">
</span>
</a>
Vega-Lite</h4>
<p>
Display a chart using the Vega-Lite library.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
vega_lite_chart<span class="token punctuation">
(</span>
my_vega_lite_chart<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/charts/st.plotly_chart">
<img src="https://docs.streamlit.io/images/api/plotly_chart.jpg" alt="screenshot">
<h4 id="plotly">
<a aria-hidden="true" tabindex="-1" href="#plotly">
<span class="icon icon-link">
</span>
</a>
Plotly</h4>
<p>
Display an interactive Plotly chart.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
plotly_chart<span class="token punctuation">
(</span>
my_plotly_chart<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/charts/st.bokeh_chart">
<img src="https://docs.streamlit.io/images/api/bokeh_chart.jpg" alt="screenshot">
<h4 id="bokeh">
<a aria-hidden="true" tabindex="-1" href="#bokeh">
<span class="icon icon-link">
</span>
</a>
Bokeh</h4>
<p>
Display an interactive Bokeh chart.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
bokeh_chart<span class="token punctuation">
(</span>
my_bokeh_chart<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/charts/st.pydeck_chart">
<img src="https://docs.streamlit.io/images/api/pydeck_chart.jpg" alt="screenshot">
<h4 id="pydeck">
<a aria-hidden="true" tabindex="-1" href="#pydeck">
<span class="icon icon-link">
</span>
</a>
PyDeck</h4>
<p>
Display a chart using the PyDeck library.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
pydeck_chart<span class="token punctuation">
(</span>
my_pydeck_chart<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/charts/st.graphviz_chart">
<img src="https://docs.streamlit.io/images/api/graphviz_chart.jpg" alt="screenshot">
<h4 id="graphviz">
<a aria-hidden="true" tabindex="-1" href="#graphviz">
<span class="icon icon-link">
</span>
</a>
GraphViz</h4>
<p>
Display a graph using the dagre-d3 library.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
graphviz_chart<span class="token punctuation">
(</span>
my_graphviz_spec<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
</section>
<a name="input-widgets" class="headerLink_HashLink___Wih5">
</a>
<h2 class="headerLink_HeaderContainer__68tak group">
<a aria-hidden="true" tabindex="-1" href="#input-widgets">
<span class="icon icon-link">
</span>
</a>
Input widgets<div class="headerLink_CopyLink__Lvpqb">
<svg width="14" height="17" viewBox="0 0 14 17" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M10.7548 0.0313721C10.7051 0.0194702 10.6571 0.00793457 10.609 0H9.87278C9.83686 0.0178223 9.81891 0.0356445 9.783 0.0356445C9.20842 0.124878 8.70565 0.374573 8.29268 0.784851L4.14488 4.90521C3.57029 5.47601 3.283 6.18951 3.31892 7.01001C3.33686 7.38464 3.42665 7.74133 3.60621 8.09808L4.43217 7.27759C4.46809 7.25977 4.46809 7.18842 4.46809 7.15271C4.41421 6.59979 4.57582 6.11816 4.97085 5.72577L8.54405 2.17615L9.13659 1.58752C9.76504 0.998901 10.7167 0.998901 11.3452 1.58752C12.0095 2.21179 12.0095 3.2464 11.3452 3.90637L7.25123 7.97327C6.8562 8.36566 6.38936 8.54401 5.83273 8.49054C5.77885 8.47266 5.72499 8.47272 5.68908 8.50836L4.86311 9.32886C4.95289 9.36456 5.00676 9.40021 5.06062 9.41803C6.15593 9.81049 7.17941 9.66779 8.02333 8.84729C9.45979 7.45599 10.8783 6.06464 12.2609 4.6377C13.7333 3.12152 12.9971 0.606445 10.9501 0.0713501C10.8805 0.0614624 10.8164 0.0461426 10.7548 0.0313721ZM7.34082 7.47388C7.62811 7.2063 7.9154 6.9209 8.20269 6.6355C8.18016 6.62988 8.16114 6.62427 8.14401 6.6192C8.10655 6.60822 8.07805 6.59985 8.04109 6.59985C7.03556 6.15393 5.83253 6.3501 5.04246 7.11713C3.606 8.52625 2.1875 9.93542 0.768994 11.3624C0.14053 11.9867 -0.0928837 12.7715 0.032803 13.6277C0.194409 14.7515 0.840817 15.5184 1.9002 15.8752C2.97755 16.2319 3.94717 16.0001 4.75517 15.2152C5.6766 14.3118 6.59005 13.4004 7.50616 12.4864C7.96467 12.0289 8.42384 11.5708 8.88501 11.1127C9.56733 10.4348 9.81871 9.61432 9.67506 8.66895C9.63916 8.41925 9.56733 8.16949 9.42369 7.9198C9.13639 8.2052 8.8491 8.47272 8.57975 8.75812C8.54385 8.776 8.54385 8.84735 8.54385 8.90082C8.61567 9.41809 8.47203 9.8819 8.09495 10.2565C6.71235 11.6478 5.31181 13.0391 3.91125 14.4125C3.51623 14.8228 2.99551 14.9655 2.43889 14.8406C1.81042 14.6979 1.4154 14.3234 1.23584 13.7347C1.05629 13.1282 1.19993 12.5753 1.64882 12.1294C2.34011 11.4337 3.03141 10.747 3.72271 10.0603C4.41401 9.37354 5.10531 8.68677 5.79661 7.99115C6.17369 7.59869 6.65849 7.45599 7.19717 7.50952C7.25103 7.50952 7.3049 7.50952 7.34082 7.47388Z" fill="#808495">
</path>
</svg>
</div>
</h2>
<section class="tileContainer_Container__qZUK_">
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/widgets/st.button">
<img src="https://docs.streamlit.io/images/api/button.jpg" alt="screenshot">
<h4 id="button">
<a aria-hidden="true" tabindex="-1" href="#button">
<span class="icon icon-link">
</span>
</a>
Button</h4>
<p>
Display a button widget.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
clicked <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
button<span class="token punctuation">
(</span>
<span class="token string">
"Click me"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/widgets/st.download_button">
<img src="https://docs.streamlit.io/images/api/download_button.jpg" alt="screenshot">
<h4 id="download-button">
<a aria-hidden="true" tabindex="-1" href="#download-button">
<span class="icon icon-link">
</span>
</a>
Download button</h4>
<p>
Display a download button widget.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
download_button<span class="token punctuation">
(</span>
<span class="token string">
"Download file"</span>
<span class="token punctuation">
,</span>
 <span class="token builtin">
file</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/widgets/st.checkbox">
<img src="https://docs.streamlit.io/images/api/checkbox.jpg" alt="screenshot">
<h4 id="checkbox">
<a aria-hidden="true" tabindex="-1" href="#checkbox">
<span class="icon icon-link">
</span>
</a>
Checkbox</h4>
<p>
Display a checkbox widget.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
selected <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
checkbox<span class="token punctuation">
(</span>
<span class="token string">
"I agree"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/widgets/st.radio">
<img src="https://docs.streamlit.io/images/api/radio.jpg" alt="screenshot">
<h4 id="radio">
<a aria-hidden="true" tabindex="-1" href="#radio">
<span class="icon icon-link">
</span>
</a>
Radio</h4>
<p>
Display a radio button widget.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
choice <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
radio<span class="token punctuation">
(</span>
<span class="token string">
"Pick one"</span>
<span class="token punctuation">
,</span>
 <span class="token punctuation">
[</span>
<span class="token string">
"cats"</span>
<span class="token punctuation">
,</span>
 <span class="token string">
"dogs"</span>
<span class="token punctuation">
]</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/widgets/st.selectbox">
<img src="https://docs.streamlit.io/images/api/selectbox.jpg" alt="screenshot">
<h4 id="selectbox">
<a aria-hidden="true" tabindex="-1" href="#selectbox">
<span class="icon icon-link">
</span>
</a>
Selectbox</h4>
<p>
Display a select widget.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
choice <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
selectbox<span class="token punctuation">
(</span>
<span class="token string">
"Pick one"</span>
<span class="token punctuation">
,</span>
 <span class="token punctuation">
[</span>
<span class="token string">
"cats"</span>
<span class="token punctuation">
,</span>
 <span class="token string">
"dogs"</span>
<span class="token punctuation">
]</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/widgets/st.multiselect">
<img src="https://docs.streamlit.io/images/api/multiselect.jpg" alt="screenshot">
<h4 id="multiselect">
<a aria-hidden="true" tabindex="-1" href="#multiselect">
<span class="icon icon-link">
</span>
</a>
Multiselect</h4>
<p>
Display a multiselect widget. The multiselect widget starts as empty.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
choices <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
multiselect<span class="token punctuation">
(</span>
<span class="token string">
"Buy"</span>
<span class="token punctuation">
,</span>
 <span class="token punctuation">
[</span>
<span class="token string">
"milk"</span>
<span class="token punctuation">
,</span>
 <span class="token string">
"apples"</span>
<span class="token punctuation">
,</span>
 <span class="token string">
"potatoes"</span>
<span class="token punctuation">
]</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/widgets/st.slider">
<img src="https://docs.streamlit.io/images/api/slider.jpg" alt="screenshot">
<h4 id="slider">
<a aria-hidden="true" tabindex="-1" href="#slider">
<span class="icon icon-link">
</span>
</a>
Slider</h4>
<p>
Display a slider widget.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
number <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
slider<span class="token punctuation">
(</span>
<span class="token string">
"Pick a number"</span>
<span class="token punctuation">
,</span>
 <span class="token number">
0</span>
<span class="token punctuation">
,</span>
 <span class="token number">
100</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/widgets/st.select_slider">
<img src="https://docs.streamlit.io/images/api/select_slider.jpg" alt="screenshot">
<h4 id="select-slider">
<a aria-hidden="true" tabindex="-1" href="#select-slider">
<span class="icon icon-link">
</span>
</a>
Select-slider</h4>
<p>
Display a slider widget to select items from a list.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
size <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
select_slider<span class="token punctuation">
(</span>
<span class="token string">
"Pick a size"</span>
<span class="token punctuation">
,</span>
 <span class="token punctuation">
[</span>
<span class="token string">
"S"</span>
<span class="token punctuation">
,</span>
 <span class="token string">
"M"</span>
<span class="token punctuation">
,</span>
 <span class="token string">
"L"</span>
<span class="token punctuation">
]</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/widgets/st.text_input">
<img src="https://docs.streamlit.io/images/api/text_input.jpg" alt="screenshot">
<h4 id="text-input">
<a aria-hidden="true" tabindex="-1" href="#text-input">
<span class="icon icon-link">
</span>
</a>
Text input</h4>
<p>
Display a single-line text input widget.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
name <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
text_input<span class="token punctuation">
(</span>
<span class="token string">
"First name"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/widgets/st.number_input">
<img src="https://docs.streamlit.io/images/api/number_input.jpg" alt="screenshot">
<h4 id="number-input">
<a aria-hidden="true" tabindex="-1" href="#number-input">
<span class="icon icon-link">
</span>
</a>
Number input</h4>
<p>
Display a numeric input widget.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
choice <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
number_input<span class="token punctuation">
(</span>
<span class="token string">
"Pick a number"</span>
<span class="token punctuation">
,</span>
 <span class="token number">
0</span>
<span class="token punctuation">
,</span>
 <span class="token number">
10</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/widgets/st.text_area">
<img src="https://docs.streamlit.io/images/api/text_area.jpg" alt="screenshot">
<h4 id="text-area">
<a aria-hidden="true" tabindex="-1" href="#text-area">
<span class="icon icon-link">
</span>
</a>
Text-area</h4>
<p>
Display a multi-line text input widget.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
text <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
text_area<span class="token punctuation">
(</span>
<span class="token string">
"Text to translate"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/widgets/st.date_input">
<img src="https://docs.streamlit.io/images/api/date_input.jpg" alt="screenshot">
<h4 id="date-input">
<a aria-hidden="true" tabindex="-1" href="#date-input">
<span class="icon icon-link">
</span>
</a>
Date input</h4>
<p>
Display a date input widget.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
date <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
date_input<span class="token punctuation">
(</span>
<span class="token string">
"Your birthday"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/widgets/st.time_input">
<img src="https://docs.streamlit.io/images/api/time_input.jpg" alt="screenshot">
<h4 id="time-input">
<a aria-hidden="true" tabindex="-1" href="#time-input">
<span class="icon icon-link">
</span>
</a>
Time input</h4>
<p>
Display a time input widget.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
time <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
time_input<span class="token punctuation">
(</span>
<span class="token string">
"Meeting time"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/widgets/st.file_uploader">
<img src="https://docs.streamlit.io/images/api/file_uploader.jpg" alt="screenshot">
<h4 id="file-uploader">
<a aria-hidden="true" tabindex="-1" href="#file-uploader">
<span class="icon icon-link">
</span>
</a>
File Uploader</h4>
<p>
Display a file uploader widget.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
data <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
file_uploader<span class="token punctuation">
(</span>
<span class="token string">
"Upload a CSV"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/widgets/st.camera_input">
<img src="https://docs.streamlit.io/images/api/camera_input.jpg" alt="screenshot">
<h4 id="camera-input">
<a aria-hidden="true" tabindex="-1" href="#camera-input">
<span class="icon icon-link">
</span>
</a>
Camera input</h4>
<p>
Display a widget that allows users to upload images directly from a camera.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
image <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
camera_input<span class="token punctuation">
(</span>
<span class="token string">
"Take a picture"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/widgets/st.color_picker">
<img src="https://docs.streamlit.io/images/api/color_picker.jpg" alt="screenshot">
<h4 id="color-picker">
<a aria-hidden="true" tabindex="-1" href="#color-picker">
<span class="icon icon-link">
</span>
</a>
Color picker</h4>
<p>
Display a color picker widget.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
color <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
color_picker<span class="token punctuation">
(</span>
<span class="token string">
"Pick a color"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
</section>
<a name="media-elements" class="headerLink_HashLink___Wih5">
</a>
<h2 class="headerLink_HeaderContainer__68tak group">
<a aria-hidden="true" tabindex="-1" href="#media-elements">
<span class="icon icon-link">
</span>
</a>
Media elements<div class="headerLink_CopyLink__Lvpqb">
<svg width="14" height="17" viewBox="0 0 14 17" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M10.7548 0.0313721C10.7051 0.0194702 10.6571 0.00793457 10.609 0H9.87278C9.83686 0.0178223 9.81891 0.0356445 9.783 0.0356445C9.20842 0.124878 8.70565 0.374573 8.29268 0.784851L4.14488 4.90521C3.57029 5.47601 3.283 6.18951 3.31892 7.01001C3.33686 7.38464 3.42665 7.74133 3.60621 8.09808L4.43217 7.27759C4.46809 7.25977 4.46809 7.18842 4.46809 7.15271C4.41421 6.59979 4.57582 6.11816 4.97085 5.72577L8.54405 2.17615L9.13659 1.58752C9.76504 0.998901 10.7167 0.998901 11.3452 1.58752C12.0095 2.21179 12.0095 3.2464 11.3452 3.90637L7.25123 7.97327C6.8562 8.36566 6.38936 8.54401 5.83273 8.49054C5.77885 8.47266 5.72499 8.47272 5.68908 8.50836L4.86311 9.32886C4.95289 9.36456 5.00676 9.40021 5.06062 9.41803C6.15593 9.81049 7.17941 9.66779 8.02333 8.84729C9.45979 7.45599 10.8783 6.06464 12.2609 4.6377C13.7333 3.12152 12.9971 0.606445 10.9501 0.0713501C10.8805 0.0614624 10.8164 0.0461426 10.7548 0.0313721ZM7.34082 7.47388C7.62811 7.2063 7.9154 6.9209 8.20269 6.6355C8.18016 6.62988 8.16114 6.62427 8.14401 6.6192C8.10655 6.60822 8.07805 6.59985 8.04109 6.59985C7.03556 6.15393 5.83253 6.3501 5.04246 7.11713C3.606 8.52625 2.1875 9.93542 0.768994 11.3624C0.14053 11.9867 -0.0928837 12.7715 0.032803 13.6277C0.194409 14.7515 0.840817 15.5184 1.9002 15.8752C2.97755 16.2319 3.94717 16.0001 4.75517 15.2152C5.6766 14.3118 6.59005 13.4004 7.50616 12.4864C7.96467 12.0289 8.42384 11.5708 8.88501 11.1127C9.56733 10.4348 9.81871 9.61432 9.67506 8.66895C9.63916 8.41925 9.56733 8.16949 9.42369 7.9198C9.13639 8.2052 8.8491 8.47272 8.57975 8.75812C8.54385 8.776 8.54385 8.84735 8.54385 8.90082C8.61567 9.41809 8.47203 9.8819 8.09495 10.2565C6.71235 11.6478 5.31181 13.0391 3.91125 14.4125C3.51623 14.8228 2.99551 14.9655 2.43889 14.8406C1.81042 14.6979 1.4154 14.3234 1.23584 13.7347C1.05629 13.1282 1.19993 12.5753 1.64882 12.1294C2.34011 11.4337 3.03141 10.747 3.72271 10.0603C4.41401 9.37354 5.10531 8.68677 5.79661 7.99115C6.17369 7.59869 6.65849 7.45599 7.19717 7.50952C7.25103 7.50952 7.3049 7.50952 7.34082 7.47388Z" fill="#808495">
</path>
</svg>
</div>
</h2>
<section class="tileContainer_Container__qZUK_">
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/media/st.image">
<img src="https://docs.streamlit.io/images/api/image.jpg" alt="screenshot">
<h4 id="image">
<a aria-hidden="true" tabindex="-1" href="#image">
<span class="icon icon-link">
</span>
</a>
Image</h4>
<p>
Display an image or list of images.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
image<span class="token punctuation">
(</span>
numpy_array<span class="token punctuation">
)</span>

st<span class="token punctuation">
.</span>
image<span class="token punctuation">
(</span>
image_bytes<span class="token punctuation">
)</span>

st<span class="token punctuation">
.</span>
image<span class="token punctuation">
(</span>
<span class="token builtin">
file</span>
<span class="token punctuation">
)</span>

st<span class="token punctuation">
.</span>
image<span class="token punctuation">
(</span>
<span class="token string">
"https://example.com/myimage.jpg"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/media/st.audio">
<img src="https://docs.streamlit.io/images/api/audio.jpg" alt="screenshot">
<h4 id="audio">
<a aria-hidden="true" tabindex="-1" href="#audio">
<span class="icon icon-link">
</span>
</a>
Audio</h4>
<p>
Display an audio player.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
audio<span class="token punctuation">
(</span>
numpy_array<span class="token punctuation">
)</span>

st<span class="token punctuation">
.</span>
audio<span class="token punctuation">
(</span>
audio_bytes<span class="token punctuation">
)</span>

st<span class="token punctuation">
.</span>
audio<span class="token punctuation">
(</span>
<span class="token builtin">
file</span>
<span class="token punctuation">
)</span>

st<span class="token punctuation">
.</span>
audio<span class="token punctuation">
(</span>
<span class="token string">
"https://example.com/myaudio.mp3"</span>
<span class="token punctuation">
,</span>
 <span class="token builtin">
format</span>
<span class="token operator">
=</span>
<span class="token string">
"audio/mp3"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/media/st.video">
<img src="https://docs.streamlit.io/images/api/video.jpg" alt="screenshot">
<h4 id="video">
<a aria-hidden="true" tabindex="-1" href="#video">
<span class="icon icon-link">
</span>
</a>
Video</h4>
<p>
Display a video player.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
video<span class="token punctuation">
(</span>
numpy_array<span class="token punctuation">
)</span>

st<span class="token punctuation">
.</span>
video<span class="token punctuation">
(</span>
video_bytes<span class="token punctuation">
)</span>

st<span class="token punctuation">
.</span>
video<span class="token punctuation">
(</span>
<span class="token builtin">
file</span>
<span class="token punctuation">
)</span>

st<span class="token punctuation">
.</span>
video<span class="token punctuation">
(</span>
<span class="token string">
"https://example.com/myvideo.mp4"</span>
<span class="token punctuation">
,</span>
 <span class="token builtin">
format</span>
<span class="token operator">
=</span>
<span class="token string">
"video/mp4"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
</section>
<a name="layouts-and-containers" class="headerLink_HashLink___Wih5">
</a>
<h2 class="headerLink_HeaderContainer__68tak group">
<a aria-hidden="true" tabindex="-1" href="#layouts-and-containers">
<span class="icon icon-link">
</span>
</a>
Layouts and containers<div class="headerLink_CopyLink__Lvpqb">
<svg width="14" height="17" viewBox="0 0 14 17" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M10.7548 0.0313721C10.7051 0.0194702 10.6571 0.00793457 10.609 0H9.87278C9.83686 0.0178223 9.81891 0.0356445 9.783 0.0356445C9.20842 0.124878 8.70565 0.374573 8.29268 0.784851L4.14488 4.90521C3.57029 5.47601 3.283 6.18951 3.31892 7.01001C3.33686 7.38464 3.42665 7.74133 3.60621 8.09808L4.43217 7.27759C4.46809 7.25977 4.46809 7.18842 4.46809 7.15271C4.41421 6.59979 4.57582 6.11816 4.97085 5.72577L8.54405 2.17615L9.13659 1.58752C9.76504 0.998901 10.7167 0.998901 11.3452 1.58752C12.0095 2.21179 12.0095 3.2464 11.3452 3.90637L7.25123 7.97327C6.8562 8.36566 6.38936 8.54401 5.83273 8.49054C5.77885 8.47266 5.72499 8.47272 5.68908 8.50836L4.86311 9.32886C4.95289 9.36456 5.00676 9.40021 5.06062 9.41803C6.15593 9.81049 7.17941 9.66779 8.02333 8.84729C9.45979 7.45599 10.8783 6.06464 12.2609 4.6377C13.7333 3.12152 12.9971 0.606445 10.9501 0.0713501C10.8805 0.0614624 10.8164 0.0461426 10.7548 0.0313721ZM7.34082 7.47388C7.62811 7.2063 7.9154 6.9209 8.20269 6.6355C8.18016 6.62988 8.16114 6.62427 8.14401 6.6192C8.10655 6.60822 8.07805 6.59985 8.04109 6.59985C7.03556 6.15393 5.83253 6.3501 5.04246 7.11713C3.606 8.52625 2.1875 9.93542 0.768994 11.3624C0.14053 11.9867 -0.0928837 12.7715 0.032803 13.6277C0.194409 14.7515 0.840817 15.5184 1.9002 15.8752C2.97755 16.2319 3.94717 16.0001 4.75517 15.2152C5.6766 14.3118 6.59005 13.4004 7.50616 12.4864C7.96467 12.0289 8.42384 11.5708 8.88501 11.1127C9.56733 10.4348 9.81871 9.61432 9.67506 8.66895C9.63916 8.41925 9.56733 8.16949 9.42369 7.9198C9.13639 8.2052 8.8491 8.47272 8.57975 8.75812C8.54385 8.776 8.54385 8.84735 8.54385 8.90082C8.61567 9.41809 8.47203 9.8819 8.09495 10.2565C6.71235 11.6478 5.31181 13.0391 3.91125 14.4125C3.51623 14.8228 2.99551 14.9655 2.43889 14.8406C1.81042 14.6979 1.4154 14.3234 1.23584 13.7347C1.05629 13.1282 1.19993 12.5753 1.64882 12.1294C2.34011 11.4337 3.03141 10.747 3.72271 10.0603C4.41401 9.37354 5.10531 8.68677 5.79661 7.99115C6.17369 7.59869 6.65849 7.45599 7.19717 7.50952C7.25103 7.50952 7.3049 7.50952 7.34082 7.47388Z" fill="#808495">
</path>
</svg>
</div>
</h2>
<section class="tileContainer_Container__qZUK_">
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/layout/st.sidebar">
<img src="https://docs.streamlit.io/images/api/sidebar.jpg" alt="screenshot">
<h4 id="sidebar">
<a aria-hidden="true" tabindex="-1" href="#sidebar">
<span class="icon icon-link">
</span>
</a>
Sidebar</h4>
<p>
Display items in a sidebar.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
sidebar<span class="token punctuation">
.</span>
write<span class="token punctuation">
(</span>
<span class="token string">
"This lives in the sidebar"</span>
<span class="token punctuation">
)</span>

st<span class="token punctuation">
.</span>
sidebar<span class="token punctuation">
.</span>
button<span class="token punctuation">
(</span>
<span class="token string">
"Click me!"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/layout/st.columns">
<img src="https://docs.streamlit.io/images/api/columns.jpg" alt="screenshot">
<h4 id="columns">
<a aria-hidden="true" tabindex="-1" href="#columns">
<span class="icon icon-link">
</span>
</a>
Columns</h4>
<p>
Insert containers laid out as side-by-side columns.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
col1<span class="token punctuation">
,</span>
 col2 <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
columns<span class="token punctuation">
(</span>
<span class="token number">
2</span>
<span class="token punctuation">
)</span>

col1<span class="token punctuation">
.</span>
write<span class="token punctuation">
(</span>
<span class="token string">
"this is column 1"</span>
<span class="token punctuation">
)</span>

col2<span class="token punctuation">
.</span>
write<span class="token punctuation">
(</span>
<span class="token string">
"this is column 2"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/layout/st.expander">
<img src="https://docs.streamlit.io/images/api/expander.jpg" alt="screenshot">
<h4 id="expander">
<a aria-hidden="true" tabindex="-1" href="#expander">
<span class="icon icon-link">
</span>
</a>
Expander</h4>
<p>
Insert a multi-element container that can be expanded/collapsed.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
<span class="token keyword">
with</span>
 st<span class="token punctuation">
.</span>
expander<span class="token punctuation">
(</span>
<span class="token string">
"Open to see more"</span>
<span class="token punctuation">
)</span>
<span class="token punctuation">
:</span>

  st<span class="token punctuation">
.</span>
write<span class="token punctuation">
(</span>
<span class="token string">
"This is more content"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/layout/st.container">
<img src="https://docs.streamlit.io/images/api/container.jpg" alt="screenshot">
<h4 id="container">
<a aria-hidden="true" tabindex="-1" href="#container">
<span class="icon icon-link">
</span>
</a>
Container</h4>
<p>
Insert a multi-element container.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
c <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
container<span class="token punctuation">
(</span>
<span class="token punctuation">
)</span>

st<span class="token punctuation">
.</span>
write<span class="token punctuation">
(</span>
<span class="token string">
"This will show last"</span>
<span class="token punctuation">
)</span>

c<span class="token punctuation">
.</span>
write<span class="token punctuation">
(</span>
<span class="token string">
"This will show first"</span>
<span class="token punctuation">
)</span>

c<span class="token punctuation">
.</span>
write<span class="token punctuation">
(</span>
<span class="token string">
"This will show second"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/layout/st.empty">
<img src="https://docs.streamlit.io/images/api/empty.jpg" alt="screenshot">
<h4 id="empty">
<a aria-hidden="true" tabindex="-1" href="#empty">
<span class="icon icon-link">
</span>
</a>
Empty</h4>
<p>
Insert a single-element container.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
c <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
empty<span class="token punctuation">
(</span>
<span class="token punctuation">
)</span>

st<span class="token punctuation">
.</span>
write<span class="token punctuation">
(</span>
<span class="token string">
"This will show last"</span>
<span class="token punctuation">
)</span>

c<span class="token punctuation">
.</span>
write<span class="token punctuation">
(</span>
<span class="token string">
"This will be replaced"</span>
<span class="token punctuation">
)</span>

c<span class="token punctuation">
.</span>
write<span class="token punctuation">
(</span>
<span class="token string">
"This will show first"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
</section>
<a name="display-progress-and-status" class="headerLink_HashLink___Wih5">
</a>
<h2 class="headerLink_HeaderContainer__68tak group">
<a aria-hidden="true" tabindex="-1" href="#display-progress-and-status">
<span class="icon icon-link">
</span>
</a>
Display progress and status<div class="headerLink_CopyLink__Lvpqb">
<svg width="14" height="17" viewBox="0 0 14 17" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M10.7548 0.0313721C10.7051 0.0194702 10.6571 0.00793457 10.609 0H9.87278C9.83686 0.0178223 9.81891 0.0356445 9.783 0.0356445C9.20842 0.124878 8.70565 0.374573 8.29268 0.784851L4.14488 4.90521C3.57029 5.47601 3.283 6.18951 3.31892 7.01001C3.33686 7.38464 3.42665 7.74133 3.60621 8.09808L4.43217 7.27759C4.46809 7.25977 4.46809 7.18842 4.46809 7.15271C4.41421 6.59979 4.57582 6.11816 4.97085 5.72577L8.54405 2.17615L9.13659 1.58752C9.76504 0.998901 10.7167 0.998901 11.3452 1.58752C12.0095 2.21179 12.0095 3.2464 11.3452 3.90637L7.25123 7.97327C6.8562 8.36566 6.38936 8.54401 5.83273 8.49054C5.77885 8.47266 5.72499 8.47272 5.68908 8.50836L4.86311 9.32886C4.95289 9.36456 5.00676 9.40021 5.06062 9.41803C6.15593 9.81049 7.17941 9.66779 8.02333 8.84729C9.45979 7.45599 10.8783 6.06464 12.2609 4.6377C13.7333 3.12152 12.9971 0.606445 10.9501 0.0713501C10.8805 0.0614624 10.8164 0.0461426 10.7548 0.0313721ZM7.34082 7.47388C7.62811 7.2063 7.9154 6.9209 8.20269 6.6355C8.18016 6.62988 8.16114 6.62427 8.14401 6.6192C8.10655 6.60822 8.07805 6.59985 8.04109 6.59985C7.03556 6.15393 5.83253 6.3501 5.04246 7.11713C3.606 8.52625 2.1875 9.93542 0.768994 11.3624C0.14053 11.9867 -0.0928837 12.7715 0.032803 13.6277C0.194409 14.7515 0.840817 15.5184 1.9002 15.8752C2.97755 16.2319 3.94717 16.0001 4.75517 15.2152C5.6766 14.3118 6.59005 13.4004 7.50616 12.4864C7.96467 12.0289 8.42384 11.5708 8.88501 11.1127C9.56733 10.4348 9.81871 9.61432 9.67506 8.66895C9.63916 8.41925 9.56733 8.16949 9.42369 7.9198C9.13639 8.2052 8.8491 8.47272 8.57975 8.75812C8.54385 8.776 8.54385 8.84735 8.54385 8.90082C8.61567 9.41809 8.47203 9.8819 8.09495 10.2565C6.71235 11.6478 5.31181 13.0391 3.91125 14.4125C3.51623 14.8228 2.99551 14.9655 2.43889 14.8406C1.81042 14.6979 1.4154 14.3234 1.23584 13.7347C1.05629 13.1282 1.19993 12.5753 1.64882 12.1294C2.34011 11.4337 3.03141 10.747 3.72271 10.0603C4.41401 9.37354 5.10531 8.68677 5.79661 7.99115C6.17369 7.59869 6.65849 7.45599 7.19717 7.50952C7.25103 7.50952 7.3049 7.50952 7.34082 7.47388Z" fill="#808495">
</path>
</svg>
</div>
</h2>
<section class="tileContainer_Container__qZUK_">
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/status/st.progress">
<img src="https://docs.streamlit.io/images/api/progress.jpg" alt="screenshot">
<h4 id="progress-bar">
<a aria-hidden="true" tabindex="-1" href="#progress-bar">
<span class="icon icon-link">
</span>
</a>
Progress bar</h4>
<p>
Display a progress bar.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
<span class="token keyword">
for</span>
 i <span class="token keyword">
in</span>
 <span class="token builtin">
range</span>
<span class="token punctuation">
(</span>
<span class="token number">
101</span>
<span class="token punctuation">
)</span>
<span class="token punctuation">
:</span>

  st<span class="token punctuation">
.</span>
progress<span class="token punctuation">
(</span>
i<span class="token punctuation">
)</span>

  do_something_slow<span class="token punctuation">
(</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/status/st.spinner">
<img src="https://docs.streamlit.io/images/api/spinner.jpg" alt="screenshot">
<h4 id="spinner">
<a aria-hidden="true" tabindex="-1" href="#spinner">
<span class="icon icon-link">
</span>
</a>
Spinner</h4>
<p>
Temporarily displays a message while executing a block of code.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
<span class="token keyword">
with</span>
 st<span class="token punctuation">
.</span>
spinner<span class="token punctuation">
(</span>
<span class="token string">
"Please wait..."</span>
<span class="token punctuation">
)</span>
<span class="token punctuation">
:</span>

  do_something_slow<span class="token punctuation">
(</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/status/st.balloons">
<img src="https://docs.streamlit.io/images/api/balloons.jpg" alt="screenshot">
<h4 id="balloons">
<a aria-hidden="true" tabindex="-1" href="#balloons">
<span class="icon icon-link">
</span>
</a>
Balloons</h4>
<p>
Display celebratory balloons!</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
do_something<span class="token punctuation">
(</span>
<span class="token punctuation">
)</span>


<span class="token comment">
# Celebrate when all done!</span>

st<span class="token punctuation">
.</span>
balloons<span class="token punctuation">
(</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/status/st.snow">
<img src="https://docs.streamlit.io/images/api/snow.jpg" alt="screenshot">
<h4 id="snowflakes">
<a aria-hidden="true" tabindex="-1" href="#snowflakes">
<span class="icon icon-link">
</span>
</a>
Snowflakes</h4>
<p>
Display celebratory snowflakes!</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
do_something<span class="token punctuation">
(</span>
<span class="token punctuation">
)</span>


<span class="token comment">
# Celebrate when all done!</span>

st<span class="token punctuation">
.</span>
snow<span class="token punctuation">
(</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/status/st.error">
<img src="https://docs.streamlit.io/images/api/error.jpg" alt="screenshot">
<h4 id="error-box">
<a aria-hidden="true" tabindex="-1" href="#error-box">
<span class="icon icon-link">
</span>
</a>
Error box</h4>
<p>
Display error message.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
error<span class="token punctuation">
(</span>
<span class="token string">
"We encountered an error"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/status/st.warning">
<img src="https://docs.streamlit.io/images/api/warning.jpg" alt="screenshot">
<h4 id="warning-box">
<a aria-hidden="true" tabindex="-1" href="#warning-box">
<span class="icon icon-link">
</span>
</a>
Warning box</h4>
<p>
Display warning message.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
warning<span class="token punctuation">
(</span>
<span class="token string">
"Unable to fetch image. Skipping..."</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/status/st.info">
<img src="https://docs.streamlit.io/images/api/info.jpg" alt="screenshot">
<h4 id="info-box">
<a aria-hidden="true" tabindex="-1" href="#info-box">
<span class="icon icon-link">
</span>
</a>
Info box</h4>
<p>
Display an informational message.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
info<span class="token punctuation">
(</span>
<span class="token string">
"Dataset is updated every day at midnight."</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/status/st.success">
<img src="https://docs.streamlit.io/images/api/success.jpg" alt="screenshot">
<h4 id="success-box">
<a aria-hidden="true" tabindex="-1" href="#success-box">
<span class="icon icon-link">
</span>
</a>
Success box</h4>
<p>
Display a success message.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
success<span class="token punctuation">
(</span>
<span class="token string">
"Match found!"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/status/st.exception">
<img src="https://docs.streamlit.io/images/api/exception.jpg" alt="screenshot">
<h4 id="exception-output">
<a aria-hidden="true" tabindex="-1" href="#exception-output">
<span class="icon icon-link">
</span>
</a>
Exception output</h4>
<p>
Display an exception.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
e <span class="token operator">
=</span>
 RuntimeError<span class="token punctuation">
(</span>
<span class="token string">
"This is an exception of type RuntimeError"</span>
<span class="token punctuation">
)</span>

st<span class="token punctuation">
.</span>
exception<span class="token punctuation">
(</span>
e<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
</section>
<a name="control-flow" class="headerLink_HashLink___Wih5">
</a>
<h2 class="headerLink_HeaderContainer__68tak group">
<a aria-hidden="true" tabindex="-1" href="#control-flow">
<span class="icon icon-link">
</span>
</a>
Control flow<div class="headerLink_CopyLink__Lvpqb">
<svg width="14" height="17" viewBox="0 0 14 17" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M10.7548 0.0313721C10.7051 0.0194702 10.6571 0.00793457 10.609 0H9.87278C9.83686 0.0178223 9.81891 0.0356445 9.783 0.0356445C9.20842 0.124878 8.70565 0.374573 8.29268 0.784851L4.14488 4.90521C3.57029 5.47601 3.283 6.18951 3.31892 7.01001C3.33686 7.38464 3.42665 7.74133 3.60621 8.09808L4.43217 7.27759C4.46809 7.25977 4.46809 7.18842 4.46809 7.15271C4.41421 6.59979 4.57582 6.11816 4.97085 5.72577L8.54405 2.17615L9.13659 1.58752C9.76504 0.998901 10.7167 0.998901 11.3452 1.58752C12.0095 2.21179 12.0095 3.2464 11.3452 3.90637L7.25123 7.97327C6.8562 8.36566 6.38936 8.54401 5.83273 8.49054C5.77885 8.47266 5.72499 8.47272 5.68908 8.50836L4.86311 9.32886C4.95289 9.36456 5.00676 9.40021 5.06062 9.41803C6.15593 9.81049 7.17941 9.66779 8.02333 8.84729C9.45979 7.45599 10.8783 6.06464 12.2609 4.6377C13.7333 3.12152 12.9971 0.606445 10.9501 0.0713501C10.8805 0.0614624 10.8164 0.0461426 10.7548 0.0313721ZM7.34082 7.47388C7.62811 7.2063 7.9154 6.9209 8.20269 6.6355C8.18016 6.62988 8.16114 6.62427 8.14401 6.6192C8.10655 6.60822 8.07805 6.59985 8.04109 6.59985C7.03556 6.15393 5.83253 6.3501 5.04246 7.11713C3.606 8.52625 2.1875 9.93542 0.768994 11.3624C0.14053 11.9867 -0.0928837 12.7715 0.032803 13.6277C0.194409 14.7515 0.840817 15.5184 1.9002 15.8752C2.97755 16.2319 3.94717 16.0001 4.75517 15.2152C5.6766 14.3118 6.59005 13.4004 7.50616 12.4864C7.96467 12.0289 8.42384 11.5708 8.88501 11.1127C9.56733 10.4348 9.81871 9.61432 9.67506 8.66895C9.63916 8.41925 9.56733 8.16949 9.42369 7.9198C9.13639 8.2052 8.8491 8.47272 8.57975 8.75812C8.54385 8.776 8.54385 8.84735 8.54385 8.90082C8.61567 9.41809 8.47203 9.8819 8.09495 10.2565C6.71235 11.6478 5.31181 13.0391 3.91125 14.4125C3.51623 14.8228 2.99551 14.9655 2.43889 14.8406C1.81042 14.6979 1.4154 14.3234 1.23584 13.7347C1.05629 13.1282 1.19993 12.5753 1.64882 12.1294C2.34011 11.4337 3.03141 10.747 3.72271 10.0603C4.41401 9.37354 5.10531 8.68677 5.79661 7.99115C6.17369 7.59869 6.65849 7.45599 7.19717 7.50952C7.25103 7.50952 7.3049 7.50952 7.34082 7.47388Z" fill="#808495">
</path>
</svg>
</div>
</h2>
<section class="tileContainer_Container__qZUK_">
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/control-flow/st.form">
<h4 id="forms">
<a aria-hidden="true" tabindex="-1" href="#forms">
<span class="icon icon-link">
</span>
</a>
Forms</h4>
<p>
Create a form that batches elements together with a “Submit” button.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
<span class="token keyword">
with</span>
 st<span class="token punctuation">
.</span>
form<span class="token punctuation">
(</span>
key<span class="token operator">
=</span>
<span class="token string">
'my_form'</span>
<span class="token punctuation">
)</span>
<span class="token punctuation">
:</span>

    username <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
text_input<span class="token punctuation">
(</span>
<span class="token string">
"Username"</span>
<span class="token punctuation">
)</span>

    password <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
text_input<span class="token punctuation">
(</span>
<span class="token string">
"Password"</span>
<span class="token punctuation">
)</span>

    st<span class="token punctuation">
.</span>
form_submit_button<span class="token punctuation">
(</span>
<span class="token string">
"Login"</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/control-flow/st.stop">
<h4 id="stop-execution">
<a aria-hidden="true" tabindex="-1" href="#stop-execution">
<span class="icon icon-link">
</span>
</a>
Stop execution</h4>
<p>
Stops execution immediately.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
stop<span class="token punctuation">
(</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/control-flow/st.experimental_rerun">
<h4 id="rerun-script">
<a aria-hidden="true" tabindex="-1" href="#rerun-script">
<span class="icon icon-link">
</span>
</a>
Rerun script</h4>
<p>
Rerun the script immediately.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
experimental_rerun<span class="token punctuation">
(</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
</section>
<a name="utilities" class="headerLink_HashLink___Wih5">
</a>
<h2 class="headerLink_HeaderContainer__68tak group">
<a aria-hidden="true" tabindex="-1" href="#utilities">
<span class="icon icon-link">
</span>
</a>
Utilities<div class="headerLink_CopyLink__Lvpqb">
<svg width="14" height="17" viewBox="0 0 14 17" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M10.7548 0.0313721C10.7051 0.0194702 10.6571 0.00793457 10.609 0H9.87278C9.83686 0.0178223 9.81891 0.0356445 9.783 0.0356445C9.20842 0.124878 8.70565 0.374573 8.29268 0.784851L4.14488 4.90521C3.57029 5.47601 3.283 6.18951 3.31892 7.01001C3.33686 7.38464 3.42665 7.74133 3.60621 8.09808L4.43217 7.27759C4.46809 7.25977 4.46809 7.18842 4.46809 7.15271C4.41421 6.59979 4.57582 6.11816 4.97085 5.72577L8.54405 2.17615L9.13659 1.58752C9.76504 0.998901 10.7167 0.998901 11.3452 1.58752C12.0095 2.21179 12.0095 3.2464 11.3452 3.90637L7.25123 7.97327C6.8562 8.36566 6.38936 8.54401 5.83273 8.49054C5.77885 8.47266 5.72499 8.47272 5.68908 8.50836L4.86311 9.32886C4.95289 9.36456 5.00676 9.40021 5.06062 9.41803C6.15593 9.81049 7.17941 9.66779 8.02333 8.84729C9.45979 7.45599 10.8783 6.06464 12.2609 4.6377C13.7333 3.12152 12.9971 0.606445 10.9501 0.0713501C10.8805 0.0614624 10.8164 0.0461426 10.7548 0.0313721ZM7.34082 7.47388C7.62811 7.2063 7.9154 6.9209 8.20269 6.6355C8.18016 6.62988 8.16114 6.62427 8.14401 6.6192C8.10655 6.60822 8.07805 6.59985 8.04109 6.59985C7.03556 6.15393 5.83253 6.3501 5.04246 7.11713C3.606 8.52625 2.1875 9.93542 0.768994 11.3624C0.14053 11.9867 -0.0928837 12.7715 0.032803 13.6277C0.194409 14.7515 0.840817 15.5184 1.9002 15.8752C2.97755 16.2319 3.94717 16.0001 4.75517 15.2152C5.6766 14.3118 6.59005 13.4004 7.50616 12.4864C7.96467 12.0289 8.42384 11.5708 8.88501 11.1127C9.56733 10.4348 9.81871 9.61432 9.67506 8.66895C9.63916 8.41925 9.56733 8.16949 9.42369 7.9198C9.13639 8.2052 8.8491 8.47272 8.57975 8.75812C8.54385 8.776 8.54385 8.84735 8.54385 8.90082C8.61567 9.41809 8.47203 9.8819 8.09495 10.2565C6.71235 11.6478 5.31181 13.0391 3.91125 14.4125C3.51623 14.8228 2.99551 14.9655 2.43889 14.8406C1.81042 14.6979 1.4154 14.3234 1.23584 13.7347C1.05629 13.1282 1.19993 12.5753 1.64882 12.1294C2.34011 11.4337 3.03141 10.747 3.72271 10.0603C4.41401 9.37354 5.10531 8.68677 5.79661 7.99115C6.17369 7.59869 6.65849 7.45599 7.19717 7.50952C7.25103 7.50952 7.3049 7.50952 7.34082 7.47388Z" fill="#808495">
</path>
</svg>
</div>
</h2>
<section class="tileContainer_Container__qZUK_">
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/utilities/st.set_page_config">
<h4 id="set-page-title-favicon-and-more">
<a aria-hidden="true" tabindex="-1" href="#set-page-title-favicon-and-more">
<span class="icon icon-link">
</span>
</a>
Set page title, favicon, and more</h4>
<p>
Configures the default settings of the page.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
set_page_config<span class="token punctuation">
(</span>

  title<span class="token operator">
=</span>
<span class="token string">
"My app"</span>
<span class="token punctuation">
,</span>

  favicon<span class="token operator">
=</span>
<span class="token string">
":shark:"</span>
<span class="token punctuation">
,</span>

<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/utilities/st.echo">
<h4 id="echo">
<a aria-hidden="true" tabindex="-1" href="#echo">
<span class="icon icon-link">
</span>
</a>
Echo</h4>
<p>
Display some code on the app, then execute it. Useful for tutorials.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
<span class="token keyword">
with</span>
 st<span class="token punctuation">
.</span>
echo<span class="token punctuation">
(</span>
<span class="token punctuation">
)</span>
<span class="token punctuation">
:</span>

  st<span class="token punctuation">
.</span>
write<span class="token punctuation">
(</span>
<span class="token string">
'This code will be printed'</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/utilities/st.help">
<h4 id="get-help">
<a aria-hidden="true" tabindex="-1" href="#get-help">
<span class="icon icon-link">
</span>
</a>
Get help</h4>
<p>
Display object’s doc string, nicely formatted.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
<span class="token builtin">
help</span>
<span class="token punctuation">
(</span>
st<span class="token punctuation">
.</span>
write<span class="token punctuation">
)</span>

st<span class="token punctuation">
.</span>
<span class="token builtin">
help</span>
<span class="token punctuation">
(</span>
pd<span class="token punctuation">
.</span>
DataFrame<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/utilities/st.experimental_show">
<h4 id="stexperimental_show">
<a aria-hidden="true" tabindex="-1" href="#stexperimental_show">
<span class="icon icon-link">
</span>
</a>
st.experimental_show</h4>
<p>
Write arguments and argument names to your app for debugging purposes.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
df <span class="token operator">
=</span>
 pd<span class="token punctuation">
.</span>
DataFrame<span class="token punctuation">
(</span>
<span class="token punctuation">
{</span>

  <span class="token string">
'first column'</span>
<span class="token punctuation">
:</span>
 <span class="token punctuation">
[</span>
<span class="token number">
1</span>
<span class="token punctuation">
,</span>
 <span class="token number">
2</span>
<span class="token punctuation">
,</span>
 <span class="token number">
3</span>
<span class="token punctuation">
,</span>
 <span class="token number">
4</span>
<span class="token punctuation">
]</span>
<span class="token punctuation">
,</span>

  <span class="token string">
'second column'</span>
<span class="token punctuation">
:</span>
 <span class="token punctuation">
[</span>
<span class="token number">
10</span>
<span class="token punctuation">
,</span>
 <span class="token number">
20</span>
<span class="token punctuation">
,</span>
 <span class="token number">
30</span>
<span class="token punctuation">
,</span>
 <span class="token number">
40</span>
<span class="token punctuation">
]</span>
<span class="token punctuation">
,</span>

 <span class="token punctuation">
}</span>
<span class="token punctuation">
)</span>

st<span class="token punctuation">
.</span>
experimental_show<span class="token punctuation">
(</span>
df<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/utilities/st.experimental_get_query_params">
<h4 id="get-query-paramters">
<a aria-hidden="true" tabindex="-1" href="#get-query-paramters">
<span class="icon icon-link">
</span>
</a>
Get query paramters</h4>
<p>
Return the query parameters that are currently showing in the browser's URL bar.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
experimental_get_query_params<span class="token punctuation">
(</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/utilities/st.experimental_set_query_params">
<h4 id="set-query-paramters">
<a aria-hidden="true" tabindex="-1" href="#set-query-paramters">
<span class="icon icon-link">
</span>
</a>
Set query paramters</h4>
<p>
Set the query parameters that are shown in the browser's URL bar.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
experimental_set_query_params<span class="token punctuation">
(</span>

  show_map<span class="token operator">
=</span>
<span class="token boolean">
True</span>
<span class="token punctuation">
,</span>

  selected<span class="token operator">
=</span>
<span class="token punctuation">
[</span>
<span class="token string">
"asia"</span>
<span class="token punctuation">
]</span>

<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
</section>
<a name="mutate-charts" class="headerLink_HashLink___Wih5">
</a>
<h2 class="headerLink_HeaderContainer__68tak group">
<a aria-hidden="true" tabindex="-1" href="#mutate-charts">
<span class="icon icon-link">
</span>
</a>
Mutate charts<div class="headerLink_CopyLink__Lvpqb">
<svg width="14" height="17" viewBox="0 0 14 17" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M10.7548 0.0313721C10.7051 0.0194702 10.6571 0.00793457 10.609 0H9.87278C9.83686 0.0178223 9.81891 0.0356445 9.783 0.0356445C9.20842 0.124878 8.70565 0.374573 8.29268 0.784851L4.14488 4.90521C3.57029 5.47601 3.283 6.18951 3.31892 7.01001C3.33686 7.38464 3.42665 7.74133 3.60621 8.09808L4.43217 7.27759C4.46809 7.25977 4.46809 7.18842 4.46809 7.15271C4.41421 6.59979 4.57582 6.11816 4.97085 5.72577L8.54405 2.17615L9.13659 1.58752C9.76504 0.998901 10.7167 0.998901 11.3452 1.58752C12.0095 2.21179 12.0095 3.2464 11.3452 3.90637L7.25123 7.97327C6.8562 8.36566 6.38936 8.54401 5.83273 8.49054C5.77885 8.47266 5.72499 8.47272 5.68908 8.50836L4.86311 9.32886C4.95289 9.36456 5.00676 9.40021 5.06062 9.41803C6.15593 9.81049 7.17941 9.66779 8.02333 8.84729C9.45979 7.45599 10.8783 6.06464 12.2609 4.6377C13.7333 3.12152 12.9971 0.606445 10.9501 0.0713501C10.8805 0.0614624 10.8164 0.0461426 10.7548 0.0313721ZM7.34082 7.47388C7.62811 7.2063 7.9154 6.9209 8.20269 6.6355C8.18016 6.62988 8.16114 6.62427 8.14401 6.6192C8.10655 6.60822 8.07805 6.59985 8.04109 6.59985C7.03556 6.15393 5.83253 6.3501 5.04246 7.11713C3.606 8.52625 2.1875 9.93542 0.768994 11.3624C0.14053 11.9867 -0.0928837 12.7715 0.032803 13.6277C0.194409 14.7515 0.840817 15.5184 1.9002 15.8752C2.97755 16.2319 3.94717 16.0001 4.75517 15.2152C5.6766 14.3118 6.59005 13.4004 7.50616 12.4864C7.96467 12.0289 8.42384 11.5708 8.88501 11.1127C9.56733 10.4348 9.81871 9.61432 9.67506 8.66895C9.63916 8.41925 9.56733 8.16949 9.42369 7.9198C9.13639 8.2052 8.8491 8.47272 8.57975 8.75812C8.54385 8.776 8.54385 8.84735 8.54385 8.90082C8.61567 9.41809 8.47203 9.8819 8.09495 10.2565C6.71235 11.6478 5.31181 13.0391 3.91125 14.4125C3.51623 14.8228 2.99551 14.9655 2.43889 14.8406C1.81042 14.6979 1.4154 14.3234 1.23584 13.7347C1.05629 13.1282 1.19993 12.5753 1.64882 12.1294C2.34011 11.4337 3.03141 10.747 3.72271 10.0603C4.41401 9.37354 5.10531 8.68677 5.79661 7.99115C6.17369 7.59869 6.65849 7.45599 7.19717 7.50952C7.25103 7.50952 7.3049 7.50952 7.34082 7.47388Z" fill="#808495">
</path>
</svg>
</div>
</h2>
<section class="tileContainer_Container__qZUK_">
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/mutate">
<h4 id="add-rows">
<a aria-hidden="true" tabindex="-1" href="#add-rows">
<span class="icon icon-link">
</span>
</a>
Add rows</h4>
<p>
Append a dataframe to the bottom of the current one in certain elements, for optimized data updates.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
element <span class="token operator">
=</span>
 st<span class="token punctuation">
.</span>
line_chart<span class="token punctuation">
(</span>
df<span class="token punctuation">
)</span>

element<span class="token punctuation">
.</span>
add_rows<span class="token punctuation">
(</span>
df_with_extra_rows<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
</section>
<a name="state-management" class="headerLink_HashLink___Wih5">
</a>
<h2 class="headerLink_HeaderContainer__68tak group">
<a aria-hidden="true" tabindex="-1" href="#state-management">
<span class="icon icon-link">
</span>
</a>
State management<div class="headerLink_CopyLink__Lvpqb">
<svg width="14" height="17" viewBox="0 0 14 17" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M10.7548 0.0313721C10.7051 0.0194702 10.6571 0.00793457 10.609 0H9.87278C9.83686 0.0178223 9.81891 0.0356445 9.783 0.0356445C9.20842 0.124878 8.70565 0.374573 8.29268 0.784851L4.14488 4.90521C3.57029 5.47601 3.283 6.18951 3.31892 7.01001C3.33686 7.38464 3.42665 7.74133 3.60621 8.09808L4.43217 7.27759C4.46809 7.25977 4.46809 7.18842 4.46809 7.15271C4.41421 6.59979 4.57582 6.11816 4.97085 5.72577L8.54405 2.17615L9.13659 1.58752C9.76504 0.998901 10.7167 0.998901 11.3452 1.58752C12.0095 2.21179 12.0095 3.2464 11.3452 3.90637L7.25123 7.97327C6.8562 8.36566 6.38936 8.54401 5.83273 8.49054C5.77885 8.47266 5.72499 8.47272 5.68908 8.50836L4.86311 9.32886C4.95289 9.36456 5.00676 9.40021 5.06062 9.41803C6.15593 9.81049 7.17941 9.66779 8.02333 8.84729C9.45979 7.45599 10.8783 6.06464 12.2609 4.6377C13.7333 3.12152 12.9971 0.606445 10.9501 0.0713501C10.8805 0.0614624 10.8164 0.0461426 10.7548 0.0313721ZM7.34082 7.47388C7.62811 7.2063 7.9154 6.9209 8.20269 6.6355C8.18016 6.62988 8.16114 6.62427 8.14401 6.6192C8.10655 6.60822 8.07805 6.59985 8.04109 6.59985C7.03556 6.15393 5.83253 6.3501 5.04246 7.11713C3.606 8.52625 2.1875 9.93542 0.768994 11.3624C0.14053 11.9867 -0.0928837 12.7715 0.032803 13.6277C0.194409 14.7515 0.840817 15.5184 1.9002 15.8752C2.97755 16.2319 3.94717 16.0001 4.75517 15.2152C5.6766 14.3118 6.59005 13.4004 7.50616 12.4864C7.96467 12.0289 8.42384 11.5708 8.88501 11.1127C9.56733 10.4348 9.81871 9.61432 9.67506 8.66895C9.63916 8.41925 9.56733 8.16949 9.42369 7.9198C9.13639 8.2052 8.8491 8.47272 8.57975 8.75812C8.54385 8.776 8.54385 8.84735 8.54385 8.90082C8.61567 9.41809 8.47203 9.8819 8.09495 10.2565C6.71235 11.6478 5.31181 13.0391 3.91125 14.4125C3.51623 14.8228 2.99551 14.9655 2.43889 14.8406C1.81042 14.6979 1.4154 14.3234 1.23584 13.7347C1.05629 13.1282 1.19993 12.5753 1.64882 12.1294C2.34011 11.4337 3.03141 10.747 3.72271 10.0603C4.41401 9.37354 5.10531 8.68677 5.79661 7.99115C6.17369 7.59869 6.65849 7.45599 7.19717 7.50952C7.25103 7.50952 7.3049 7.50952 7.34082 7.47388Z" fill="#808495">
</path>
</svg>
</div>
</h2>
<section class="tileContainer_Container__qZUK_">
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/session-state">
<h4 id="session-state">
<a aria-hidden="true" tabindex="-1" href="#session-state">
<span class="icon icon-link">
</span>
</a>
Session state</h4>
<p>
Session state is a way to share variables between reruns, for each user session.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
st<span class="token punctuation">
.</span>
session_state<span class="token punctuation">
[</span>
<span class="token string">
'key'</span>
<span class="token punctuation">
]</span>
 <span class="token operator">
=</span>
 value</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
</section>
<a name="performance" class="headerLink_HashLink___Wih5">
</a>
<h2 class="headerLink_HeaderContainer__68tak group">
<a aria-hidden="true" tabindex="-1" href="#performance">
<span class="icon icon-link">
</span>
</a>
Performance<div class="headerLink_CopyLink__Lvpqb">
<svg width="14" height="17" viewBox="0 0 14 17" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M10.7548 0.0313721C10.7051 0.0194702 10.6571 0.00793457 10.609 0H9.87278C9.83686 0.0178223 9.81891 0.0356445 9.783 0.0356445C9.20842 0.124878 8.70565 0.374573 8.29268 0.784851L4.14488 4.90521C3.57029 5.47601 3.283 6.18951 3.31892 7.01001C3.33686 7.38464 3.42665 7.74133 3.60621 8.09808L4.43217 7.27759C4.46809 7.25977 4.46809 7.18842 4.46809 7.15271C4.41421 6.59979 4.57582 6.11816 4.97085 5.72577L8.54405 2.17615L9.13659 1.58752C9.76504 0.998901 10.7167 0.998901 11.3452 1.58752C12.0095 2.21179 12.0095 3.2464 11.3452 3.90637L7.25123 7.97327C6.8562 8.36566 6.38936 8.54401 5.83273 8.49054C5.77885 8.47266 5.72499 8.47272 5.68908 8.50836L4.86311 9.32886C4.95289 9.36456 5.00676 9.40021 5.06062 9.41803C6.15593 9.81049 7.17941 9.66779 8.02333 8.84729C9.45979 7.45599 10.8783 6.06464 12.2609 4.6377C13.7333 3.12152 12.9971 0.606445 10.9501 0.0713501C10.8805 0.0614624 10.8164 0.0461426 10.7548 0.0313721ZM7.34082 7.47388C7.62811 7.2063 7.9154 6.9209 8.20269 6.6355C8.18016 6.62988 8.16114 6.62427 8.14401 6.6192C8.10655 6.60822 8.07805 6.59985 8.04109 6.59985C7.03556 6.15393 5.83253 6.3501 5.04246 7.11713C3.606 8.52625 2.1875 9.93542 0.768994 11.3624C0.14053 11.9867 -0.0928837 12.7715 0.032803 13.6277C0.194409 14.7515 0.840817 15.5184 1.9002 15.8752C2.97755 16.2319 3.94717 16.0001 4.75517 15.2152C5.6766 14.3118 6.59005 13.4004 7.50616 12.4864C7.96467 12.0289 8.42384 11.5708 8.88501 11.1127C9.56733 10.4348 9.81871 9.61432 9.67506 8.66895C9.63916 8.41925 9.56733 8.16949 9.42369 7.9198C9.13639 8.2052 8.8491 8.47272 8.57975 8.75812C8.54385 8.776 8.54385 8.84735 8.54385 8.90082C8.61567 9.41809 8.47203 9.8819 8.09495 10.2565C6.71235 11.6478 5.31181 13.0391 3.91125 14.4125C3.51623 14.8228 2.99551 14.9655 2.43889 14.8406C1.81042 14.6979 1.4154 14.3234 1.23584 13.7347C1.05629 13.1282 1.19993 12.5753 1.64882 12.1294C2.34011 11.4337 3.03141 10.747 3.72271 10.0603C4.41401 9.37354 5.10531 8.68677 5.79661 7.99115C6.17369 7.59869 6.65849 7.45599 7.19717 7.50952C7.25103 7.50952 7.3049 7.50952 7.34082 7.47388Z" fill="#808495">
</path>
</svg>
</div>
</h2>
<section class="tileContainer_Container__qZUK_">
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/performance/st.cache">
<h4 id="caching">
<a aria-hidden="true" tabindex="-1" href="#caching">
<span class="icon icon-link">
</span>
</a>
Caching</h4>
<p>
Function decorator to memoize function executions.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
<span class="token decorator annotation punctuation">
@st<span class="token punctuation">
.</span>
cache</span>
<span class="token punctuation">
(</span>
ttl<span class="token operator">
=</span>
<span class="token number">
3600</span>
<span class="token punctuation">
)</span>

<span class="token keyword">
def</span>
 <span class="token function">
run_long_computation</span>
<span class="token punctuation">
(</span>
arg1<span class="token punctuation">
,</span>
 arg2<span class="token punctuation">
)</span>
<span class="token punctuation">
:</span>

  <span class="token comment">
# Do stuff here</span>

  <span class="token keyword">
return</span>
 computation_output</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/performance/st.experimental_memo">
<h4 id="memo">
<a aria-hidden="true" tabindex="-1" href="#memo">
<span class="icon icon-link">
</span>
</a>
Memo</h4>
<p>
Experimental function decorator to memoize function executions.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
<span class="token decorator annotation punctuation">
@st<span class="token punctuation">
.</span>
experimental_memo</span>

<span class="token keyword">
def</span>
 <span class="token function">
fetch_and_clean_data</span>
<span class="token punctuation">
(</span>
url<span class="token punctuation">
)</span>
<span class="token punctuation">
:</span>

  <span class="token comment">
# Fetch data from URL here, and then clean it up.</span>

  <span class="token keyword">
return</span>
 data</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/performance/st.experimental_singleton">
<h4 id="singleton">
<a aria-hidden="true" tabindex="-1" href="#singleton">
<span class="icon icon-link">
</span>
</a>
Singleton</h4>
<p>
Experimental function decorator to store singleton objects.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
<span class="token decorator annotation punctuation">
@st<span class="token punctuation">
.</span>
experimental_singleton</span>

<span class="token keyword">
def</span>
 <span class="token function">
get_database_session</span>
<span class="token punctuation">
(</span>
url<span class="token punctuation">
)</span>
<span class="token punctuation">
:</span>

  <span class="token comment">
# Create a database session object that points to the URL.</span>

  <span class="token keyword">
return</span>
 session</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/performance/st.experimental_memo.clear">
<h4 id="clear-memo">
<a aria-hidden="true" tabindex="-1" href="#clear-memo">
<span class="icon icon-link">
</span>
</a>
Clear memo</h4>
<p>
Clear all in-memory and on-disk memo caches.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
<span class="token decorator annotation punctuation">
@st<span class="token punctuation">
.</span>
experimental_memo</span>

<span class="token keyword">
def</span>
 <span class="token function">
fetch_and_clean_data</span>
<span class="token punctuation">
(</span>
url<span class="token punctuation">
)</span>
<span class="token punctuation">
:</span>

  <span class="token comment">
# Fetch data from URL here, and then clean it up.</span>

  <span class="token keyword">
return</span>
 data

<span class="token keyword">
if</span>
 st<span class="token punctuation">
.</span>
checkbox<span class="token punctuation">
(</span>
<span class="token string">
"Clear All"</span>
<span class="token punctuation">
)</span>
<span class="token punctuation">
:</span>

  <span class="token comment">
# Clear values from *all* memoized functions</span>

  st<span class="token punctuation">
.</span>
experimental_memo<span class="token punctuation">
.</span>
clear<span class="token punctuation">
(</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
<a class="refCard_Container__LoksC refCard_Third__Au4Xh" href="/library/api-reference/performance/st.experimental_singleton.clear">
<h4 id="clear-singleton">
<a aria-hidden="true" tabindex="-1" href="#clear-singleton">
<span class="icon icon-link">
</span>
</a>
Clear singleton</h4>
<p>
Clear all singleton caches.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
<span class="token decorator annotation punctuation">
@st<span class="token punctuation">
.</span>
experimental_singleton</span>

<span class="token keyword">
def</span>
 <span class="token function">
get_database_session</span>
<span class="token punctuation">
(</span>
url<span class="token punctuation">
)</span>
<span class="token punctuation">
:</span>

  <span class="token comment">
# Create a database session object that points to the URL.</span>

  <span class="token keyword">
return</span>
 session

<span class="token keyword">
if</span>
 st<span class="token punctuation">
.</span>
button<span class="token punctuation">
(</span>
<span class="token string">
"Clear All"</span>
<span class="token punctuation">
)</span>
<span class="token punctuation">
:</span>

  <span class="token comment">
# Clears all singleton caches:</span>

  st<span class="token punctuation">
.</span>
experimental_singleton<span class="token punctuation">
.</span>
clear<span class="token punctuation">
(</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
</section>
<a name="personalization" class="headerLink_HashLink___Wih5">
</a>
<h2 class="headerLink_HeaderContainer__68tak group">
<a aria-hidden="true" tabindex="-1" href="#personalization">
<span class="icon icon-link">
</span>
</a>
Personalization<div class="headerLink_CopyLink__Lvpqb">
<svg width="14" height="17" viewBox="0 0 14 17" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M10.7548 0.0313721C10.7051 0.0194702 10.6571 0.00793457 10.609 0H9.87278C9.83686 0.0178223 9.81891 0.0356445 9.783 0.0356445C9.20842 0.124878 8.70565 0.374573 8.29268 0.784851L4.14488 4.90521C3.57029 5.47601 3.283 6.18951 3.31892 7.01001C3.33686 7.38464 3.42665 7.74133 3.60621 8.09808L4.43217 7.27759C4.46809 7.25977 4.46809 7.18842 4.46809 7.15271C4.41421 6.59979 4.57582 6.11816 4.97085 5.72577L8.54405 2.17615L9.13659 1.58752C9.76504 0.998901 10.7167 0.998901 11.3452 1.58752C12.0095 2.21179 12.0095 3.2464 11.3452 3.90637L7.25123 7.97327C6.8562 8.36566 6.38936 8.54401 5.83273 8.49054C5.77885 8.47266 5.72499 8.47272 5.68908 8.50836L4.86311 9.32886C4.95289 9.36456 5.00676 9.40021 5.06062 9.41803C6.15593 9.81049 7.17941 9.66779 8.02333 8.84729C9.45979 7.45599 10.8783 6.06464 12.2609 4.6377C13.7333 3.12152 12.9971 0.606445 10.9501 0.0713501C10.8805 0.0614624 10.8164 0.0461426 10.7548 0.0313721ZM7.34082 7.47388C7.62811 7.2063 7.9154 6.9209 8.20269 6.6355C8.18016 6.62988 8.16114 6.62427 8.14401 6.6192C8.10655 6.60822 8.07805 6.59985 8.04109 6.59985C7.03556 6.15393 5.83253 6.3501 5.04246 7.11713C3.606 8.52625 2.1875 9.93542 0.768994 11.3624C0.14053 11.9867 -0.0928837 12.7715 0.032803 13.6277C0.194409 14.7515 0.840817 15.5184 1.9002 15.8752C2.97755 16.2319 3.94717 16.0001 4.75517 15.2152C5.6766 14.3118 6.59005 13.4004 7.50616 12.4864C7.96467 12.0289 8.42384 11.5708 8.88501 11.1127C9.56733 10.4348 9.81871 9.61432 9.67506 8.66895C9.63916 8.41925 9.56733 8.16949 9.42369 7.9198C9.13639 8.2052 8.8491 8.47272 8.57975 8.75812C8.54385 8.776 8.54385 8.84735 8.54385 8.90082C8.61567 9.41809 8.47203 9.8819 8.09495 10.2565C6.71235 11.6478 5.31181 13.0391 3.91125 14.4125C3.51623 14.8228 2.99551 14.9655 2.43889 14.8406C1.81042 14.6979 1.4154 14.3234 1.23584 13.7347C1.05629 13.1282 1.19993 12.5753 1.64882 12.1294C2.34011 11.4337 3.03141 10.747 3.72271 10.0603C4.41401 9.37354 5.10531 8.68677 5.79661 7.99115C6.17369 7.59869 6.65849 7.45599 7.19717 7.50952C7.25103 7.50952 7.3049 7.50952 7.34082 7.47388Z" fill="#808495">
</path>
</svg>
</div>
</h2>
<section class="tileContainer_Container__qZUK_">
<a class="refCard_Container__LoksC refCard_Half__LNH50" href="/library/api-reference/personalization/st.experimental_user">
<h4 id="user-info">
<a aria-hidden="true" tabindex="-1" href="#user-info">
<span class="icon icon-link">
</span>
</a>
User info</h4>
<p>
<code>
st.experimental_user</code>
 returns information about the logged-in user of private apps on Streamlit Cloud.</p>
<section class="code_Container__v4rq_">
<div class="code-toolbar">
<pre class="language-python" tabindex="0">
<code class="language-python">
<span class="token keyword">
if</span>
 st<span class="token punctuation">
.</span>
experimental_user<span class="token punctuation">
.</span>
email <span class="token operator">
==</span>
 <span class="token string">
"foo@corp.com"</span>
<span class="token punctuation">
:</span>

  st<span class="token punctuation">
.</span>
write<span class="token punctuation">
(</span>
<span class="token string">
"Welcome back, "</span>
<span class="token punctuation">
,</span>
 st<span class="token punctuation">
.</span>
experimental_user<span class="token punctuation">
.</span>
email<span class="token punctuation">
)</span>

<span class="token keyword">
else</span>
<span class="token punctuation">
:</span>

  st<span class="token punctuation">
.</span>
write<span class="token punctuation">
(</span>
<span class="token string">
"You are not authorized to view this page."</span>
<span class="token punctuation">
)</span>
</code>
</pre>
<div class="toolbar">
<div class="toolbar-item">
<button class="copy-to-clipboard-button" type="button" data-copy-state="copy">
<span>
Copy</span>
</button>
</div>
</div>
</div>
</section>
</a>
</section>
<section class="helpful_FormContainer__aXrIB">
<form name="helpful" method="POST" data-netlify="true" data-netlify-honeypot="bot-field" class="helpful_Form__O7ORb">
<input type="hidden" name="form-name" value="helpful">
<input type="hidden" name="url" value="/library/api-reference">
<input type="hidden" name="was_helpful" value="true">
<input type="hidden" name="improvements" value="">
<input type="hidden" name="notes" value="">
<section class="helpful_Container__V1dv8">
<p class="helpful_Title__lQBy3">
Was this page helpful?</p>
<section class="helpful_CtaContainer__8FIxs">
<button class="helpful_Button__Xv_VK">
<i class="helpful_Icon___MVCB">
thumb_up</i>
Yes</button>
<button class="helpful_Button__Xv_VK">
 <i class="helpful_Icon___MVCB">
thumb_down</i>
No</button>
</section>
</section>
</form>
<section>
<section class="suggestEdits_Container__eBMj0">
<i class="suggestEdits_Icon__MtLji">
edit</i>
<a class="suggestEdits_Link__JC0oe" href="https://github.com/streamlit/docs/tree/main/content/library/api/api-reference.md" target="_blank" rel="noopener noreferrer">
Suggest edits</a>
</section>
</section>
</section>
</div>
