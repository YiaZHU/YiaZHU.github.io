<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>AI + 胚胎发育方向综述文献库（100篇）</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

/* Override strong tags inside headings to maintain consistent weight */
h1 strong,
h2 strong,
h3 strong {
	font-weight: 600;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 10px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}

	table.collection-content {
		width: 100%;
		table-layout: fixed;
	}

	table.collection-content th,
	table.collection-content td {
		overflow-wrap: anywhere;
	}

	table.collection-content td > .user,
	table.collection-content td > time {
		white-space: pre-wrap;
	}
}

@page {
	margin: 1in;
}

.collection-content-wrapper {
	overflow-x: auto;
}

@media only print {
	.collection-content-wrapper {
		overflow-x: visible;
	}
}

.collection-content {
	font-size: 0.875rem;
}

.collection-content td {
	white-space: pre-wrap;
	word-break: break-word;
}

.column-list {
	display: flex;
	gap: 46px;
}

.column {
	min-width: 0;
	overflow: hidden;
}

.column > *:first-child {
	margin-top: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	padding-inline-start: 0;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol.numbered-list.numbered-list-digits-2 {
	padding-inline-start: 2em;
}

ol.numbered-list.numbered-list-digits-3plus {
	padding-inline-start: 2.4em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.page-description {
	margin-bottom: 2em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-flex;
	align-items: center;
	justify-content: center;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.callout img.notion-static-icon {
	width: 1em;
	height: 1em;
}

.callout p {
	margin: 0;
}

.callout h1,
.callout h2,
.callout h3 {
	margin: 0 0 0.6rem;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

blockquote.quote-large {
	font-size: 1.25em;
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", "Noto Sans Arabic", "Noto Sans Hebrew", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", "Noto Sans Arabic", "Noto Sans Hebrew", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", "Noto Sans Arabic", "Noto Sans Hebrew", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", "Noto Sans Arabic", "Noto Sans Hebrew", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", "Noto Sans Arabic", "Noto Sans Hebrew", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(44, 44, 43, 1);
}
.highlight-gray {
	color: rgba(125, 122, 117, 1);
	fill: rgba(125, 122, 117, 1);
}
.highlight-brown {
	color: rgba(159, 118, 90, 1);
	fill: rgba(159, 118, 90, 1);
}
.highlight-orange {
	color: rgba(210, 123, 45, 1);
	fill: rgba(210, 123, 45, 1);
}
.highlight-yellow {
	color: rgba(203, 148, 52, 1);
	fill: rgba(203, 148, 52, 1);
}
.highlight-teal {
	color: rgba(80, 148, 110, 1);
	fill: rgba(80, 148, 110, 1);
}
.highlight-blue {
	color: rgba(56, 125, 201, 1);
	fill: rgba(56, 125, 201, 1);
}
.highlight-purple {
	color: rgba(154, 107, 180, 1);
	fill: rgba(154, 107, 180, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(207, 81, 72, 1);
	fill: rgba(207, 81, 72, 1);
}
.highlight-default_background {
	color: rgba(44, 44, 43, 1);
}
.highlight-gray_background {
	background: rgba(42, 28, 0, 0.07);
}
.highlight-brown_background {
	background: rgba(139, 46, 0, 0.086);
}
.highlight-orange_background {
	background: rgba(224, 101, 1, 0.129);
}
.highlight-yellow_background {
	background: rgba(211, 168, 0, 0.137);
}
.highlight-teal_background {
	background: rgba(0, 100, 45, 0.09);
}
.highlight-blue_background {
	background: rgba(0, 124, 215, 0.094);
}
.highlight-purple_background {
	background: rgba(102, 0, 178, 0.078);
}
.highlight-pink_background {
	background: rgba(197, 0, 93, 0.086);
}
.highlight-red_background {
	background: rgba(223, 22, 0, 0.094);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(125, 122, 117, 1);
	fill: rgba(125, 122, 117, 1);
}
.block-color-brown {
	color: rgba(159, 118, 90, 1);
	fill: rgba(159, 118, 90, 1);
}
.block-color-orange {
	color: rgba(210, 123, 45, 1);
	fill: rgba(210, 123, 45, 1);
}
.block-color-yellow {
	color: rgba(203, 148, 52, 1);
	fill: rgba(203, 148, 52, 1);
}
.block-color-teal {
	color: rgba(80, 148, 110, 1);
	fill: rgba(80, 148, 110, 1);
}
.block-color-blue {
	color: rgba(56, 125, 201, 1);
	fill: rgba(56, 125, 201, 1);
}
.block-color-purple {
	color: rgba(154, 107, 180, 1);
	fill: rgba(154, 107, 180, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(207, 81, 72, 1);
	fill: rgba(207, 81, 72, 1);
}
.block-color-default_background {
	color: inherit;
	fill: inherit;
}
.block-color-gray_background {
	background: rgba(240, 239, 237, 1);
}
.block-color-brown_background {
	background: rgba(245, 237, 233, 1);
}
.block-color-orange_background {
	background: rgba(251, 235, 222, 1);
}
.block-color-yellow_background {
	background: rgba(249, 243, 220, 1);
}
.block-color-teal_background {
	background: rgba(232, 241, 236, 1);
}
.block-color-blue_background {
	background: rgba(229, 242, 252, 1);
}
.block-color-purple_background {
	background: rgba(243, 235, 249, 1);
}
.block-color-pink_background {
	background: rgba(250, 233, 241, 1);
}
.block-color-red_background {
	background: rgba(252, 233, 231, 1);
}
.select-value-color-default { background-color: rgba(42, 28, 0, 0.07); }
.select-value-color-gray { background-color: rgba(28, 19, 1, 0.11); }
.select-value-color-brown { background-color: rgba(127, 51, 0, 0.156); }
.select-value-color-orange { background-color: rgba(196, 88, 0, 0.203); }
.select-value-color-yellow { background-color: rgba(209, 156, 0, 0.282); }
.select-value-color-green { background-color: rgba(0, 96, 38, 0.156); }
.select-value-color-blue { background-color: rgba(0, 118, 217, 0.203); }
.select-value-color-purple { background-color: rgba(92, 0, 163, 0.141); }
.select-value-color-pink { background-color: rgba(183, 0, 78, 0.152); }
.select-value-color-red { background-color: rgba(206, 24, 0, 0.164); }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="33e790c9-45e8-80f9-9156-c960c3b1dffc" class="page serif"><header><h1 class="page-title" dir="auto">AI + 胚胎发育方向综述文献库（100篇）</h1><p class="page-description" dir="auto"></p></header><div class="page-body"><div style="display:contents" dir="ltr"><div id="33e790c9-45e8-8066-867c-d9f59ba6957c" class="collection-content"><h4 class="collection-title">一、综述与总览（11篇）</h4><div class="collection-content-wrapper"><table class="collection-content"><thead><tr><th><span class="icon property-icon"><img src="https://www.notion.so/icons/font_gray.svg" style="width:14px;height:14px;display:block"/></span>#</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>标题</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>期刊</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>年份</th></tr></thead><tbody><tr id="33e790c9-45e8-800e-a9ec-e02eea7fdfa5"><td class="cell-title"><a href="https://www.notion.so/1-33e790c945e8800ea9ece02eea7fdfa5?pvs=21">1</a></td><td class="cell-fXcE">Artificial Intelligence-Empowered Embryo Selection for IVF Applications: A Methodological Review</td><td class="cell-ROui"><em>Applied Sciences (MDPI)</em></td><td class="cell-K{\p">2025</td></tr><tr id="33e790c9-45e8-80c1-9efc-d3829b839901"><td class="cell-title"><a href="https://www.notion.so/2-33e790c945e880c19efcd3829b839901?pvs=21">2</a></td><td class="cell-fXcE">Embryo selection through artificial intelligence versus embryologists: a systematic review</td><td class="cell-ROui"><em>Human Reproduction Open</em></td><td class="cell-K{\p">2023</td></tr><tr id="33e790c9-45e8-8002-be9a-f3f96d2ca4d0"><td class="cell-title"><a href="https://www.notion.so/3-33e790c945e88002be9af3f96d2ca4d0?pvs=21">3</a></td><td class="cell-fXcE">AI in in-vitro fertilization (IVF): A new era of precision and personalization</td><td class="cell-ROui"><em>J Gynecol Obstet Hum Reprod</em></td><td class="cell-K{\p">2025</td></tr><tr id="33e790c9-45e8-80ad-8cb8-e584bf2d12e2"><td class="cell-title"><a href="https://www.notion.so/4-33e790c945e880ad8cb8e584bf2d12e2?pvs=21">4</a></td><td class="cell-fXcE">Machine learning approaches for image classification in developmental biology and clinical embryology</td><td class="cell-ROui"><em>Development</em></td><td class="cell-K{\p">2025</td></tr><tr id="33e790c9-45e8-8006-b270-e0db17b5d365"><td class="cell-title"><a href="https://www.notion.so/5-33e790c945e88006b270e0db17b5d365?pvs=21">5</a></td><td class="cell-fXcE">Deep learning for bioimage analysis in developmental biology</td><td class="cell-ROui"><em>Developmental Cell</em></td><td class="cell-K{\p">2021</td></tr><tr id="33e790c9-45e8-806e-bb99-dcfecf115c49"><td class="cell-title"><a href="https://www.notion.so/6-33e790c945e8806ebb99dcfecf115c49?pvs=21">6</a></td><td class="cell-fXcE">Investigating AI in predicting and evaluating sperm and embryo quality in IVF: a systematic review</td><td class="cell-ROui"><em>Discover Artificial Intelligence</em></td><td class="cell-K{\p">2025</td></tr><tr id="33e790c9-45e8-8050-a2f0-d7a96a161170"><td class="cell-title"><a href="https://www.notion.so/7-33e790c945e88050a2f0d7a96a161170?pvs=21">7</a></td><td class="cell-fXcE">Decoding the blueprints of embryo development with single-cell and spatial omics</td><td class="cell-ROui"><em>Seminars in Cell &amp; Dev Biol</em></td><td class="cell-K{\p">2025</td></tr><tr id="33e790c9-45e8-80cd-b5c3-f3eb2f65f005"><td class="cell-title"><a href="https://www.notion.so/8-33e790c945e880cdb5c3f3eb2f65f005?pvs=21">8</a></td><td class="cell-fXcE">Artificial Intelligence Revolution in Transcriptomics: From Single Cells to Spatial Atlases</td><td class="cell-ROui"><em>Advanced Science</em></td><td class="cell-K{\p">2025</td></tr><tr id="33e790c9-45e8-8018-86aa-cb6535a8de34"><td class="cell-title"><a href="https://www.notion.so/9-33e790c945e8801886aacb6535a8de34?pvs=21">9</a></td><td class="cell-fXcE">Foundation models in bioinformatics</td><td class="cell-ROui"><em>National Science Review</em></td><td class="cell-K{\p">2025</td></tr><tr id="33e790c9-45e8-8021-b279-ef0e5979f352"><td class="cell-title"><a href="https://www.notion.so/10-33e790c945e88021b279ef0e5979f352?pvs=21">10</a></td><td class="cell-fXcE">Single-cell foundation models: bringing artificial intelligence into cell biology</td><td class="cell-ROui"><em>Exp Mol Med</em></td><td class="cell-K{\p">2025</td></tr><tr id="33e790c9-45e8-80a1-ae22-c6b43097be9c"><td class="cell-title"><a href="https://www.notion.so/11-33e790c945e880a1ae22c6b43097be9c?pvs=21">11</a></td><td class="cell-fXcE">Non-invasive prediction of human embryonic ploidy using AI: a systematic review and meta-analysis</td><td class="cell-ROui"><em>eClinicalMedicine (Lancet)</em></td><td class="cell-K{\p">2024</td></tr></tbody></table></div><br/><br/></div></div><div style="display:contents" dir="auto"><hr id="33e790c9-45e8-8079-aa23-e9cf0b2273cb"/></div><div style="display:contents" dir="ltr"><div id="33e790c9-45e8-80cd-b63b-c9daf24c6c64" class="collection-content"><h4 class="collection-title">二、AI胚胎评分与IVF临床应用（14篇）</h4><div class="collection-content-wrapper"><table class="collection-content"><thead><tr><th><span class="icon property-icon"><img src="https://www.notion.so/icons/font_gray.svg" style="width:14px;height:14px;display:block"/></span>#</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>标题</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>期刊</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>年份</th></tr></thead><tbody><tr id="33e790c9-45e8-80ce-b510-c2f46b161e39"><td class="cell-title"><a href="https://www.notion.so/12-33e790c945e880ceb510c2f46b161e39?pvs=21">12</a></td><td class="cell-}f\]">MAIA platform for routine clinical testing: an AI embryo selection tool</td><td class="cell-qjsc"><em>Scientific Reports</em></td><td class="cell-k=wO">2025</td></tr><tr id="33e790c9-45e8-801c-b8b5-d52cd8f71cf0"><td class="cell-title"><a href="https://www.notion.so/13-33e790c945e8801cb8b5d52cd8f71cf0?pvs=21">13</a></td><td class="cell-}f\]">A generalized AI system for human embryo selection via multi-modal contrastive learning (IVFormer/VTCLR)</td><td class="cell-qjsc"><em>Cell Reports Medicine</em></td><td class="cell-k=wO">2024</td></tr><tr id="33e790c9-45e8-80db-a771-f383c6c04f15"><td class="cell-title"><a href="https://www.notion.so/14-33e790c945e880dba771f383c6c04f15?pvs=21">14</a></td><td class="cell-}f\]">Deep learning classification integrating embryo images with clinical information from ART cycles</td><td class="cell-qjsc"><em>Scientific Reports</em></td><td class="cell-k=wO">2025</td></tr><tr id="33e790c9-45e8-8076-a633-efd8f4523115"><td class="cell-title"><a href="https://www.notion.so/15-33e790c945e88076a633efd8f4523115?pvs=21">15</a></td><td class="cell-}f\]">Ensemble deep learning with advanced feature engineering for embryo evaluation in IVF</td><td class="cell-qjsc"><em>Scientific Reports</em></td><td class="cell-k=wO">2025</td></tr><tr id="33e790c9-45e8-801e-bafe-d19c8d5d01e9"><td class="cell-title"><a href="https://www.notion.so/16-33e790c945e8801ebafed19c8d5d01e9?pvs=21">16</a></td><td class="cell-}f\]">An AI algorithm to select most viable embryos considering current process in IVF labs</td><td class="cell-qjsc"><em>Frontiers in Artificial Intelligence</em></td><td class="cell-k=wO">2024</td></tr><tr id="33e790c9-45e8-8053-91f0-ce1c641422db"><td class="cell-title"><a href="https://www.notion.so/17-33e790c945e8805391f0ce1c641422db?pvs=21">17</a></td><td class="cell-}f\]">Development and validation of deep learning-based embryo selection across multiple days of transfer</td><td class="cell-qjsc"><em>Scientific Reports</em></td><td class="cell-k=wO">2023</td></tr><tr id="33e790c9-45e8-8058-9d35-ed035a4d0443"><td class="cell-title"><a href="https://www.notion.so/18-33e790c945e880589d35ed035a4d0443?pvs=21">18</a></td><td class="cell-}f\]">Characterization of an AI model for ranking static images of blastocyst stage embryos</td><td class="cell-qjsc"><em>Fertility &amp; Sterility</em></td><td class="cell-k=wO">2022</td></tr><tr id="33e790c9-45e8-8016-a799-df6266472869"><td class="cell-title"><a href="https://www.notion.so/19-33e790c945e88016a799df6266472869?pvs=21">19</a></td><td class="cell-}f\]">Consistency and objectivity of automated embryo assessments using deep neural networks</td><td class="cell-qjsc"><em>Fertility &amp; Sterility</em></td><td class="cell-k=wO">2020</td></tr><tr id="33e790c9-45e8-8030-8d45-cbacb2ef2506"><td class="cell-title"><a href="https://www.notion.so/20-33e790c945e880308d45cbacb2ef2506?pvs=21">20</a></td><td class="cell-}f\]">Machine learning predicts live-birth occurrence before in-vitro fertilization treatment</td><td class="cell-qjsc"><em>Scientific Reports</em></td><td class="cell-k=wO">2021</td></tr><tr id="33e790c9-45e8-80d0-af15-ec334a36d3a0"><td class="cell-title"><a href="https://www.notion.so/21-33e790c945e880d0af15ec334a36d3a0?pvs=21">21</a></td><td class="cell-}f\]">Embryo selection with artificial intelligence: how to evaluate and compare methods?</td><td class="cell-qjsc"><em>J Assist Reprod Genet</em></td><td class="cell-k=wO">2021</td></tr><tr id="33e790c9-45e8-80a7-9689-e94708bcc6a8"><td class="cell-title"><a href="https://www.notion.so/22-33e790c945e880a79689e94708bcc6a8?pvs=21">22</a></td><td class="cell-}f\]">Beyond black-box models: explainable AI for embryo ploidy prediction and patient-centric consultation</td><td class="cell-qjsc"><em>J Assist Reprod Genet</em></td><td class="cell-k=wO">2024</td></tr><tr id="33e790c9-45e8-8065-8ef0-d5d0513614fd"><td class="cell-title"><a href="https://www.notion.so/23-33e790c945e880658ef0d5d0513614fd?pvs=21">23</a></td><td class="cell-}f\]">Ethics of artificial intelligence in embryo assessment: Mapping the terrain</td><td class="cell-qjsc"><em>Human Reproduction</em></td><td class="cell-k=wO">2025</td></tr><tr id="33e790c9-45e8-8034-8b78-e177223557ff"><td class="cell-title"><a href="https://www.notion.so/24-33e790c945e880348b78e177223557ff?pvs=21">24</a></td><td class="cell-}f\]">The use of voting ensembles to improve the accuracy of deep neural networks as a non-invasive method to predict embryo ploidy status</td><td class="cell-qjsc"><em>J Assist Reprod Genet</em></td><td class="cell-k=wO">2023</td></tr><tr id="33e790c9-45e8-80b9-8765-cebce579c8d3"><td class="cell-title"><a href="https://www.notion.so/25-33e790c945e880b98765cebce579c8d3?pvs=21">25</a></td><td class="cell-}f\]">Automatic ploidy prediction and quality assessment of human blastocyst using time-lapse imaging</td><td class="cell-qjsc"><em>Scientific Reports</em></td><td class="cell-k=wO">2022</td></tr></tbody></table></div><br/><br/></div></div><div style="display:contents" dir="auto"><hr id="33e790c9-45e8-80be-81a0-df0971651eb8"/></div><div style="display:contents" dir="ltr"><div id="33e790c9-45e8-806e-b473-f9d1ac23a6e6" class="collection-content"><h4 class="collection-title">三、单细胞转录组学与AI算法（14篇）</h4><div class="collection-content-wrapper"><table class="collection-content"><thead><tr><th><span class="icon property-icon"><img src="https://www.notion.so/icons/font_gray.svg" style="width:14px;height:14px;display:block"/></span>#</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>标题</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>期刊</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>年份</th></tr></thead><tbody><tr id="33e790c9-45e8-80cc-913e-fbb03fbc6552"><td class="cell-title"><a href="https://www.notion.so/26-33e790c945e880cc913efbb03fbc6552?pvs=21">26</a></td><td class="cell-ck[s">Deep learning-based models for preimplantation mouse and human embryos based on scRNA-seq</td><td class="cell-^RyH"><em>Nature Methods</em></td><td class="cell-TvY|">2025</td></tr><tr id="33e790c9-45e8-8056-94e6-c6fb2d1bd958"><td class="cell-title"><a href="https://www.notion.so/27-33e790c945e8805694e6c6fb2d1bd958?pvs=21">27</a></td><td class="cell-ck[s">A comprehensive human embryo reference tool using scRNA-seq data</td><td class="cell-^RyH"><em>Nature Methods</em></td><td class="cell-TvY|">2025</td></tr><tr id="33e790c9-45e8-8004-9b54-e6348ce4b16f"><td class="cell-title"><a href="https://www.notion.so/28-33e790c945e880049b54e6348ce4b16f?pvs=21">28</a></td><td class="cell-ck[s">Deep learning in single-cell and spatial transcriptomics data analysis: advances and challenges</td><td class="cell-^RyH"><em>Briefings in Bioinformatics</em></td><td class="cell-TvY|">2025</td></tr><tr id="33e790c9-45e8-8018-93c1-cdf5ceb01a86"><td class="cell-title"><a href="https://www.notion.so/29-33e790c945e8801893c1cdf5ceb01a86?pvs=21">29</a></td><td class="cell-ck[s">Applications of AI to single-cell and spatial transcriptomics: current state-of-the-art and challenges</td><td class="cell-^RyH"><em>Frontiers in Bioinformatics</em></td><td class="cell-TvY|">2025</td></tr><tr id="33e790c9-45e8-80f7-8a3b-ea6a960e19ea"><td class="cell-title"><a href="https://www.notion.so/30-33e790c945e880f78a3bea6a960e19ea?pvs=21">30</a></td><td class="cell-ck[s">Advancements in scRNA-seq and spatial transcriptomics: transforming biomedical research</td><td class="cell-^RyH"><em>Acta Biochimica Polonica</em></td><td class="cell-TvY|">2025</td></tr><tr id="33e790c9-45e8-80a2-a352-e287d72e34d8"><td class="cell-title"><a href="https://www.notion.so/31-33e790c945e880a2a352e287d72e34d8?pvs=21">31</a></td><td class="cell-ck[s">Towards Applying Large Language Models to Complement Single-Cell Foundation Models</td><td class="cell-^RyH"><em>arXiv</em></td><td class="cell-TvY|">2025</td></tr><tr id="33e790c9-45e8-8040-8a75-e120efea215e"><td class="cell-title"><a href="https://www.notion.so/32-33e790c945e880408a75e120efea215e?pvs=21">32</a></td><td class="cell-ck[s">scGPT: toward building a foundation model for single-cell multi-omics using generative AI</td><td class="cell-^RyH"><em>Nature Methods</em></td><td class="cell-TvY|">2024</td></tr><tr id="33e790c9-45e8-8013-90a3-e95467962d1b"><td class="cell-title"><a href="https://www.notion.so/33-33e790c945e8801390a3e95467962d1b?pvs=21">33</a></td><td class="cell-ck[s">Geneformer: Transfer learning enables predictions in network biology</td><td class="cell-^RyH"><em>Nature</em></td><td class="cell-TvY|">2023</td></tr><tr id="33e790c9-45e8-804d-ad16-eb6d2e58161d"><td class="cell-title"><a href="https://www.notion.so/34-33e790c945e8804dad16eb6d2e58161d?pvs=21">34</a></td><td class="cell-ck[s">GeneCompass: Deciphering universal gene regulatory mechanisms with knowledge-informed cross-species foundation model</td><td class="cell-^RyH"><em>Nature</em></td><td class="cell-TvY|">2024</td></tr><tr id="33e790c9-45e8-803a-864a-d4075a9baf0c"><td class="cell-title"><a href="https://www.notion.so/35-33e790c945e8803a864ad4075a9baf0c?pvs=21">35</a></td><td class="cell-ck[s">A cell atlas foundation model for scalable search of similar human cells</td><td class="cell-^RyH"><em>Nature</em></td><td class="cell-TvY|">2025</td></tr><tr id="33e790c9-45e8-8019-8304-d80cc4f2da2c"><td class="cell-title"><a href="https://www.notion.so/36-33e790c945e880198304d80cc4f2da2c?pvs=21">36</a></td><td class="cell-ck[s">A foundation model of transcription across human cell types</td><td class="cell-^RyH"><em>Nature</em></td><td class="cell-TvY|">2025</td></tr><tr id="33e790c9-45e8-80c6-90a7-f3d270d914fc"><td class="cell-title"><a href="https://www.notion.so/37-33e790c945e880c690a7f3d270d914fc?pvs=21">37</a></td><td class="cell-ck[s">CELLama: foundation model for single cell and spatial transcriptomics by cell embedding leveraging language model abilities</td><td class="cell-^RyH"><em>bioRxiv</em></td><td class="cell-TvY|">2024</td></tr><tr id="33e790c9-45e8-8044-a86b-db4f76b6d3fb"><td class="cell-title"><a href="https://www.notion.so/38-33e790c945e88044a86bdb4f76b6d3fb?pvs=21">38</a></td><td class="cell-ck[s">Nicheformer: a foundation model for single-cell and spatial omics</td><td class="cell-^RyH"><em>bioRxiv</em></td><td class="cell-TvY|">2024</td></tr><tr id="33e790c9-45e8-8042-b452-d4211442eaa8"><td class="cell-title"><a href="https://www.notion.so/39-33e790c945e88042b452d4211442eaa8?pvs=21">39</a></td><td class="cell-ck[s">Zero-shot evaluation reveals limitations of single-cell foundation models</td><td class="cell-^RyH"><em>Genome Biology</em></td><td class="cell-TvY|">2025</td></tr></tbody></table></div><br/><br/></div></div><div style="display:contents" dir="auto"><hr id="33e790c9-45e8-808f-b12d-eb9a71cdfdd3"/></div><div style="display:contents" dir="ltr"><div id="33e790c9-45e8-8087-a0d0-d8f1ceb059c2" class="collection-content"><h4 class="collection-title">四、空间转录组学与胚胎图谱（9篇）</h4><div class="collection-content-wrapper"><table class="collection-content"><thead><tr><th><span class="icon property-icon"><img src="https://www.notion.so/icons/font_gray.svg" style="width:14px;height:14px;display:block"/></span>#</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>标题</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>期刊</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>年份</th></tr></thead><tbody><tr id="33e790c9-45e8-80dc-a91f-d6af9f0ead4d"><td class="cell-title"><a href="https://www.notion.so/40-33e790c945e880dca91fd6af9f0ead4d?pvs=21">40</a></td><td class="cell-W\yN">Integration of single-cell and spatial transcriptomics by SEU-TCA reveals the spatial origin of early cardiac progenitors</td><td class="cell-JM;K"><em>Genome Biology</em></td><td class="cell-H:jA">2025</td></tr><tr id="33e790c9-45e8-8057-a59e-e84679b5ed4b"><td class="cell-title"><a href="https://www.notion.so/41-33e790c945e88057a59ee84679b5ed4b?pvs=21">41</a></td><td class="cell-W\yN">Zebrahub-Multiome: Uncovering Gene Regulatory Network Dynamics During Zebrafish Embryogenesis</td><td class="cell-JM;K"><em>bioRxiv</em></td><td class="cell-H:jA">2024</td></tr><tr id="33e790c9-45e8-8038-ba64-e7e9f056063c"><td class="cell-title"><a href="https://www.notion.so/42-33e790c945e88038ba64e7e9f056063c?pvs=21">42</a></td><td class="cell-W\yN">A network regularized linear model to infer spatial expression pattern for single cell (glmSMA)</td><td class="cell-JM;K"><em>eLife</em></td><td class="cell-H:jA">2025</td></tr><tr id="33e790c9-45e8-808b-a2d4-ccfe960d5173"><td class="cell-title"><a href="https://www.notion.so/43-33e790c945e8808ba2d4ccfe960d5173?pvs=21">43</a></td><td class="cell-W\yN">Spatiotemporal transcriptomic atlas of mouse organogenesis using DNA proximity labeling</td><td class="cell-JM;K"><em>Cell</em></td><td class="cell-H:jA">2022</td></tr><tr id="33e790c9-45e8-80f0-9737-cf668e827c91"><td class="cell-title"><a href="https://www.notion.so/44-33e790c945e880f09737cf668e827c91?pvs=21">44</a></td><td class="cell-W\yN">Single-cell and spatial transcriptomics integration</td><td class="cell-JM;K"><em>PMC/bioRxiv</em></td><td class="cell-H:jA">2025</td></tr><tr id="33e790c9-45e8-80c0-8479-e33df7c2e08d"><td class="cell-title"><a href="https://www.notion.so/45-33e790c945e880c08479e33df7c2e08d?pvs=21">45</a></td><td class="cell-W\yN">Stereo-seq transcriptomic atlas of the zebrafish embryo</td><td class="cell-JM;K"><em>Cell</em></td><td class="cell-H:jA">2022</td></tr><tr id="33e790c9-45e8-8044-9277-e6e1d78e13be"><td class="cell-title"><a href="https://www.notion.so/46-33e790c945e880449277e6e1d78e13be?pvs=21">46</a></td><td class="cell-W\yN">Spatial atlas of the human early post-implantation embryo</td><td class="cell-JM;K"><em>Nature</em></td><td class="cell-H:jA">2023</td></tr><tr id="33e790c9-45e8-8067-8559-d0bfa6033188"><td class="cell-title"><a href="https://www.notion.so/47-33e790c945e880678559d0bfa6033188?pvs=21">47</a></td><td class="cell-W\yN">scGPT-spatial: continual pretraining of single-cell foundation model for spatial transcriptomics</td><td class="cell-JM;K"><em>bioRxiv</em></td><td class="cell-H:jA">2025</td></tr><tr id="33e790c9-45e8-80f6-bf4d-c6f628b73ab7"><td class="cell-title"><a href="https://www.notion.so/48-33e790c945e880f6bf4dc6f628b73ab7?pvs=21">48</a></td><td class="cell-W\yN">EpiAgent: foundation model for single-cell epigenomic data</td><td class="cell-JM;K"><em>bioRxiv</em></td><td class="cell-H:jA">2024</td></tr></tbody></table></div><br/><br/></div></div><div style="display:contents" dir="auto"><hr id="33e790c9-45e8-80bf-9f1e-fb2ed35427ae"/></div><div style="display:contents" dir="ltr"><div id="33e790c9-45e8-801b-86de-f97ca81338bc" class="collection-content"><h4 class="collection-title">五、基因调控网络推断与细胞命运预测（10篇）</h4><div class="collection-content-wrapper"><table class="collection-content"><thead><tr><th><span class="icon property-icon"><img src="https://www.notion.so/icons/font_gray.svg" style="width:14px;height:14px;display:block"/></span>#</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>标题</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>期刊</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>年份</th></tr></thead><tbody><tr id="33e790c9-45e8-8096-acaf-cdf270d05844"><td class="cell-title"><a href="https://www.notion.so/49-33e790c945e88096acafcdf270d05844?pvs=21">49</a></td><td class="cell-Z|o]">Machine learning methods for gene regulatory network inference</td><td class="cell-qNK|"><em>Briefings in Bioinformatics</em></td><td class="cell-^e^Q">2025</td></tr><tr id="33e790c9-45e8-8020-826d-d2e34d8c4856"><td class="cell-title"><a href="https://www.notion.so/50-33e790c945e88020826dd2e34d8c4856?pvs=21">50</a></td><td class="cell-Z|o]">Scalable identification of lineage-specific GRNs from metacells with NetID</td><td class="cell-qNK|"><em>Genome Biology</em></td><td class="cell-^e^Q">2024</td></tr><tr id="33e790c9-45e8-80f6-991a-d2d58e7b9f2a"><td class="cell-title"><a href="https://www.notion.so/51-33e790c945e880f6991ad2d58e7b9f2a?pvs=21">51</a></td><td class="cell-Z|o]">Inferring gene regulatory networks by hypergraph generative model (HyperG-VAE)</td><td class="cell-qNK|"><em>Cell Reports Methods</em></td><td class="cell-^e^Q">2025</td></tr><tr id="33e790c9-45e8-8018-9ec0-ee3249136a1b"><td class="cell-title"><a href="https://www.notion.so/52-33e790c945e880189ec0ee3249136a1b?pvs=21">52</a></td><td class="cell-Z|o]">Gene regulatory network inference during cell fate decisions by perturbation strategies</td><td class="cell-qNK|"><em>npj Systems Biology and Applications</em></td><td class="cell-^e^Q">2025</td></tr><tr id="33e790c9-45e8-80e7-8443-e1feea5871fe"><td class="cell-title"><a href="https://www.notion.so/53-33e790c945e880e78443e1feea5871fe?pvs=21">53</a></td><td class="cell-Z|o]">Gene regulatory network prediction using machine learning, deep learning, and hybrid approaches</td><td class="cell-qNK|"><em>Forestry Research</em></td><td class="cell-^e^Q">2025</td></tr><tr id="33e790c9-45e8-8060-9278-ea7f04d6e127"><td class="cell-title"><a href="https://www.notion.so/54-33e790c945e880609278ea7f04d6e127?pvs=21">54</a></td><td class="cell-Z|o]">A neural network-based model framework for cell-fate decisions and development (AGRN)</td><td class="cell-qNK|"><em>Communications Biology</em></td><td class="cell-^e^Q">2024</td></tr><tr id="33e790c9-45e8-80af-993c-cf742b7b34f1"><td class="cell-title"><a href="https://www.notion.so/55-33e790c945e880af993ccf742b7b34f1?pvs=21">55</a></td><td class="cell-Z|o]">A logic-incorporated gene regulatory network deciphers principles in cell fate decisions</td><td class="cell-qNK|"><em>eLife</em></td><td class="cell-^e^Q">2024</td></tr><tr id="33e790c9-45e8-8009-b937-c939cecfb5d4"><td class="cell-title"><a href="https://www.notion.so/56-33e790c945e88009b937c939cecfb5d4?pvs=21">56</a></td><td class="cell-Z|o]">Marr&#x27;s three levels for embryonic development: information, dynamical systems, gene networks</td><td class="cell-qNK|"><em>arXiv</em></td><td class="cell-^e^Q">2025</td></tr><tr id="33e790c9-45e8-8065-8808-c21572ed793d"><td class="cell-title"><a href="https://www.notion.so/57-33e790c945e880658808c21572ed793d?pvs=21">57</a></td><td class="cell-Z|o]">Systematic reconstruction of cellular trajectories across mouse embryogenesis</td><td class="cell-qNK|"><em>Nature Genetics</em></td><td class="cell-^e^Q">2022</td></tr><tr id="33e790c9-45e8-8004-b35e-f28daf264084"><td class="cell-title"><a href="https://www.notion.so/58-33e790c945e88004b35ef28daf264084?pvs=21">58</a></td><td class="cell-Z|o]">CellRank for directed single-cell fate mapping</td><td class="cell-qNK|"><em>Nature Methods</em></td><td class="cell-^e^Q">2022</td></tr></tbody></table></div><br/><br/></div></div><div style="display:contents" dir="auto"><hr id="33e790c9-45e8-80b5-911e-d136691d15fe"/></div><div style="display:contents" dir="ltr"><div id="33e790c9-45e8-80df-9517-dd11abdbe909" class="collection-content"><h4 class="collection-title">六、表观基因组学与染色质重编程（8篇）</h4><div class="collection-content-wrapper"><table class="collection-content"><thead><tr><th><span class="icon property-icon"><img src="https://www.notion.so/icons/font_gray.svg" style="width:14px;height:14px;display:block"/></span>#</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>标题</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>期刊</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>年份</th></tr></thead><tbody><tr id="33e790c9-45e8-8047-ae03-f1f1b1dafbc7"><td class="cell-title"><a href="https://www.notion.so/59-33e790c945e88047ae03f1f1b1dafbc7?pvs=21">59</a></td><td class="cell-Kb;Y">Chromatin accessibility landscape of mouse early embryos revealed by single-cell NanoATAC-seq2</td><td class="cell-laDd"><em>Science</em></td><td class="cell-VDQ&lt;">2025</td></tr><tr id="33e790c9-45e8-8046-83ee-e5c8c4365c90"><td class="cell-title"><a href="https://www.notion.so/60-33e790c945e8804683eee5c8c4365c90?pvs=21">60</a></td><td class="cell-Kb;Y">Chromatin accessibility dynamics during cell fate specifications in zebrafish early embryogenesis</td><td class="cell-laDd"><em>Nucleic Acids Research</em></td><td class="cell-VDQ&lt;">2024</td></tr><tr id="33e790c9-45e8-8001-a3b1-d2bff77cbc4d"><td class="cell-title"><a href="https://www.notion.so/61-33e790c945e88001a3b1d2bff77cbc4d?pvs=21">61</a></td><td class="cell-Kb;Y">An integrated chromatin accessibility and transcriptome landscape of human pre-implantation embryos (LiCAT-seq)</td><td class="cell-laDd"><em>Nature Communications</em></td><td class="cell-VDQ&lt;">2019</td></tr><tr id="33e790c9-45e8-8071-b871-feec897ccb04"><td class="cell-title"><a href="https://www.notion.so/62-33e790c945e88071b871feec897ccb04?pvs=21">62</a></td><td class="cell-Kb;Y">The landscape of accessible chromatin in mammalian preimplantation embryos (ATAC-seq)</td><td class="cell-laDd"><em>Nature</em></td><td class="cell-VDQ&lt;">2016</td></tr><tr id="33e790c9-45e8-807d-8ac7-e5a66305bef8"><td class="cell-title"><a href="https://www.notion.so/63-33e790c945e8807d8ac7e5a66305bef8?pvs=21">63</a></td><td class="cell-Kb;Y">Chromatin Analyses in Mouse Oocytes and Preimplantation Embryos (CUT&amp;RUN/ATAC-seq protocol)</td><td class="cell-laDd"><em>Methods in Molecular Biology</em></td><td class="cell-VDQ&lt;">2025</td></tr><tr id="33e790c9-45e8-8010-9768-fcd4aded4b40"><td class="cell-title"><a href="https://www.notion.so/64-33e790c945e880109768fcd4aded4b40?pvs=21">64</a></td><td class="cell-Kb;Y">EpiTrace infers cell mitotic age and evolution from single-cell ATAC-seq data</td><td class="cell-laDd"><em>Nature Biotechnology</em></td><td class="cell-VDQ&lt;">2023</td></tr><tr id="33e790c9-45e8-8074-bd67-e6db0dbdb423"><td class="cell-title"><a href="https://www.notion.so/65-33e790c945e88074bd67e6db0dbdb423?pvs=21">65</a></td><td class="cell-Kb;Y">Allelic reprogramming of the histone modification H3K4me3 in early mammalian development</td><td class="cell-laDd"><em>Nature</em></td><td class="cell-VDQ&lt;">2016</td></tr><tr id="33e790c9-45e8-80ac-b5b4-dbdc0dd233c9"><td class="cell-title"><a href="https://www.notion.so/66-33e790c945e880acb5b4dbdc0dd233c9?pvs=21">66</a></td><td class="cell-Kb;Y">Epigenome in early mammalian development: inheritance, reprogramming and establishment</td><td class="cell-laDd"><em>Trends in Cell Biology</em></td><td class="cell-VDQ&lt;">2017</td></tr></tbody></table></div><br/><br/></div></div><div style="display:contents" dir="auto"><hr id="33e790c9-45e8-80c0-86fc-c58c6c744dd2"/></div><div style="display:contents" dir="ltr"><div id="33e790c9-45e8-80e3-8390-f12d817fdf9c" class="collection-content"><h4 class="collection-title">七、干细胞胚胎模型与类胚体（10篇）</h4><div class="collection-content-wrapper"><table class="collection-content"><thead><tr><th><span class="icon property-icon"><img src="https://www.notion.so/icons/font_gray.svg" style="width:14px;height:14px;display:block"/></span>#</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>标题</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>期刊</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>年份</th></tr></thead><tbody><tr id="33e790c9-45e8-8047-b6bc-e792637b9eba"><td class="cell-title"><a href="https://www.notion.so/67-33e790c945e88047b6bce792637b9eba?pvs=21">67</a></td><td class="cell-sfNt">AI-based approach to dissect the variability of mouse stem cell-derived embryo models</td><td class="cell-xzTy"><em>Nature Communications</em></td><td class="cell-}a~w">2025</td></tr><tr id="33e790c9-45e8-8062-8123-e383ea0a17ec"><td class="cell-title"><a href="https://www.notion.so/68-33e790c945e880628123e383ea0a17ec?pvs=21">68</a></td><td class="cell-sfNt">Stem Cell and Synthetic Embryo Models: Advances, Applications, and Ethical Considerations</td><td class="cell-xzTy"><em>Stem Cell Reviews and Reports</em></td><td class="cell-}a~w">2025</td></tr><tr id="33e790c9-45e8-804d-87d0-faa9a12ec96f"><td class="cell-title"><a href="https://www.notion.so/69-33e790c945e8804d87d0faa9a12ec96f?pvs=21">69</a></td><td class="cell-sfNt">Topical Section: Embryonic models for Current Opinion in Genetics &amp; Development</td><td class="cell-xzTy"><em>Curr Opin Genet Dev</em></td><td class="cell-}a~w">2024</td></tr><tr id="33e790c9-45e8-804c-95e7-f19d09378654"><td class="cell-title"><a href="https://www.notion.so/70-33e790c945e8804c95e7f19d09378654?pvs=21">70</a></td><td class="cell-sfNt">Exploring the black box of human reproduction: endometrial organoids and assembloids</td><td class="cell-xzTy"><em>Frontiers in Cell and Developmental Biology</em></td><td class="cell-}a~w">2024</td></tr><tr id="33e790c9-45e8-80e2-b3e9-c05e37160483"><td class="cell-title"><a href="https://www.notion.so/71-33e790c945e880e2b3e9c05e37160483?pvs=21">71</a></td><td class="cell-sfNt">Modeling post-implantation stages of human development with stem-cell-derived peri-gastruloids</td><td class="cell-xzTy"><em>Nature</em></td><td class="cell-}a~w">2023</td></tr><tr id="33e790c9-45e8-80c6-87d3-cfc40120fcb5"><td class="cell-title"><a href="https://www.notion.so/72-33e790c945e880c687d3cfc40120fcb5?pvs=21">72</a></td><td class="cell-sfNt">Generation of Blastocyst-like Structures from Mouse Embryonic and Adult Cell Cultures (Blastoids)</td><td class="cell-xzTy"><em>Cell</em></td><td class="cell-}a~w">2019</td></tr><tr id="33e790c9-45e8-8005-83e1-e90965bcdb6d"><td class="cell-title"><a href="https://www.notion.so/73-33e790c945e8800583e1e90965bcdb6d?pvs=21">73</a></td><td class="cell-sfNt">Recent progress on organoids: Techniques, advantages and applications</td><td class="cell-xzTy"><em>Biomedicine &amp; Pharmacotherapy</em></td><td class="cell-}a~w">2025</td></tr><tr id="33e790c9-45e8-80e6-921d-cdce2282e89c"><td class="cell-title"><a href="https://www.notion.so/74-33e790c945e880e6921dcdce2282e89c?pvs=21">74</a></td><td class="cell-sfNt">Stem cell-based mammalian embryo models (review, 2023)</td><td class="cell-xzTy"><em>Curr Opin Genet Dev</em></td><td class="cell-}a~w">2024</td></tr><tr id="33e790c9-45e8-80dc-a9e0-cc6a15f1ea9d"><td class="cell-title"><a href="https://www.notion.so/75-33e790c945e880dca9e0cc6a15f1ea9d?pvs=21">75</a></td><td class="cell-sfNt">Machine learning-assisted high-content analysis of pluripotent stem cell-derived embryos in vitro</td><td class="cell-xzTy"><em>Stem Cell Reports</em></td><td class="cell-}a~w">2021</td></tr><tr id="33e790c9-45e8-801e-a936-e6413e9f3b74"><td class="cell-title"><a href="https://www.notion.so/76-33e790c945e8801ea936e6413e9f3b74?pvs=21">76</a></td><td class="cell-sfNt">Human blastoid model development and authentication</td><td class="cell-xzTy"><em>Nature</em></td><td class="cell-}a~w">2023</td></tr></tbody></table></div><br/><br/></div></div><div style="display:contents" dir="auto"><hr id="33e790c9-45e8-802b-98d4-ece7274df2cb"/></div><div style="display:contents" dir="ltr"><div id="33e790c9-45e8-806f-a4bb-eacb53cb2346" class="collection-content"><h4 class="collection-title">八、活体成像与图像分析（9篇）</h4><div class="collection-content-wrapper"><table class="collection-content"><thead><tr><th><span class="icon property-icon"><img src="https://www.notion.so/icons/font_gray.svg" style="width:14px;height:14px;display:block"/></span>#</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>标题</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>期刊</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>年份</th></tr></thead><tbody><tr id="33e790c9-45e8-8078-b4fa-c94c8e65b3c3"><td class="cell-title"><a href="https://www.notion.so/77-33e790c945e88078b4fac94c8e65b3c3?pvs=21">77</a></td><td class="cell-XFZa">Trans-scale live-imaging of an E5.5 mouse embryo using incubator-type biaxial light-sheet microscopy</td><td class="cell-B}:X"><em>Life Science Alliance</em></td><td class="cell-^kob">2025</td></tr><tr id="33e790c9-45e8-80ee-bcda-cf256a581edd"><td class="cell-title"><a href="https://www.notion.so/78-33e790c945e880eebcdacf256a581edd?pvs=21">78</a></td><td class="cell-XFZa">High-resolution line-scan Brillouin microscopy for live imaging of mechanical properties during embryo development</td><td class="cell-B}:X"><em>Nature Methods</em></td><td class="cell-^kob">2023</td></tr><tr id="33e790c9-45e8-80d0-8100-d4752f0a0f66"><td class="cell-title"><a href="https://www.notion.so/79-33e790c945e880d08100d4752f0a0f66?pvs=21">79</a></td><td class="cell-XFZa">Convolutional neural network transformer (CNNT) for microscopy image enhancement in zebrafish embryos</td><td class="cell-B}:X"><em>Scientific Reports</em></td><td class="cell-^kob">2024</td></tr><tr id="33e790c9-45e8-804c-a704-cb4461026ddc"><td class="cell-title"><a href="https://www.notion.so/80-33e790c945e8804ca704cb4461026ddc?pvs=21">80</a></td><td class="cell-XFZa">KimmelNet: a CNN-based model for staging zebrafish embryos across development</td><td class="cell-B}:X"><em>Development</em></td><td class="cell-^kob">2024</td></tr><tr id="33e790c9-45e8-80ac-af17-fa54ed63e895"><td class="cell-title"><a href="https://www.notion.so/81-33e790c945e880acaf17fa54ed63e895?pvs=21">81</a></td><td class="cell-XFZa">EmbryoNet: ResNet-based model to identify molecular defects in zebrafish embryos</td><td class="cell-B}:X"><em>Nature Methods</em></td><td class="cell-^kob">2023</td></tr><tr id="33e790c9-45e8-8055-8cd8-ee483d392dba"><td class="cell-title"><a href="https://www.notion.so/82-33e790c945e880558cd8ee483d392dba?pvs=21">82</a></td><td class="cell-XFZa">Quantitative imaging of cell dynamics in mouse embryos using light-sheet microscopy</td><td class="cell-B}:X"><em>Development</em></td><td class="cell-^kob">2014</td></tr><tr id="33e790c9-45e8-805a-af5f-f29e68d7dc22"><td class="cell-title"><a href="https://www.notion.so/83-33e790c945e8805aaf5ff29e68d7dc22?pvs=21">83</a></td><td class="cell-XFZa">In vivo imaging of zebrafish embryogenesis</td><td class="cell-B}:X"><em>Methods</em></td><td class="cell-^kob">2014</td></tr><tr id="33e790c9-45e8-802a-888f-dc447d03d2bd"><td class="cell-title"><a href="https://www.notion.so/84-33e790c945e8802a888fdc447d03d2bd?pvs=21">84</a></td><td class="cell-XFZa">Automated Processing of Zebrafish Imaging Data: A Survey</td><td class="cell-B}:X"><em>Zebrafish</em></td><td class="cell-^kob">2013</td></tr><tr id="33e790c9-45e8-8073-8ef8-fc24753acc00"><td class="cell-title"><a href="https://www.notion.so/85-33e790c945e880738ef8fc24753acc00?pvs=21">85</a></td><td class="cell-XFZa">Machine learning-assisted high-content analysis of pluripotent stem cell-derived embryos in vitro</td><td class="cell-B}:X"><em>Stem Cell Reports</em></td><td class="cell-^kob">2021</td></tr></tbody></table></div><br/><br/></div></div><div style="display:contents" dir="auto"><hr id="33e790c9-45e8-801b-8286-c9d167710ce4"/></div><div style="display:contents" dir="ltr"><div id="33e790c9-45e8-80d5-a2c0-f7e0aca6104e" class="collection-content"><h4 class="collection-title">九、多组学整合与计算框架（9篇）</h4><div class="collection-content-wrapper"><table class="collection-content"><thead><tr><th><span class="icon property-icon"><img src="https://www.notion.so/icons/font_gray.svg" style="width:14px;height:14px;display:block"/></span>#</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>标题</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>期刊</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>年份</th></tr></thead><tbody><tr id="33e790c9-45e8-8029-a233-e35d31a96758"><td class="cell-title"><a href="https://www.notion.so/86-33e790c945e88029a233e35d31a96758?pvs=21">86</a></td><td class="cell-p`pi">Generalized biological foundation model with unified nucleic acid and protein language (LucaOne)</td><td class="cell-YVW["><em>Nature Machine Intelligence</em></td><td class="cell-WUOX">2025</td></tr><tr id="33e790c9-45e8-801d-a018-ea0da0614cde"><td class="cell-title"><a href="https://www.notion.so/87-33e790c945e8801da018ea0da0614cde?pvs=21">87</a></td><td class="cell-p`pi">BioLLM: A standardized framework for integrating and benchmarking single-cell foundation models</td><td class="cell-YVW["><em>Patterns</em></td><td class="cell-WUOX">2025</td></tr><tr id="33e790c9-45e8-8073-b30c-f6022e7fc648"><td class="cell-title"><a href="https://www.notion.so/88-33e790c945e88073b30cf6022e7fc648?pvs=21">88</a></td><td class="cell-p`pi">scPROTEIN: a versatile deep graph contrastive learning framework for single-cell proteomics embedding</td><td class="cell-YVW["><em>Nature Methods</em></td><td class="cell-WUOX">2024</td></tr><tr id="33e790c9-45e8-80a4-b4c4-e6de09d1fe80"><td class="cell-title"><a href="https://www.notion.so/89-33e790c945e880a4b4c4e6de09d1fe80?pvs=21">89</a></td><td class="cell-p`pi">scmFormer integrates large-scale single-cell proteomics and transcriptomics data by multi-task transformer</td><td class="cell-YVW["><em>Advanced Science</em></td><td class="cell-WUOX">2024</td></tr><tr id="33e790c9-45e8-80d0-bd88-e96e5aeea250"><td class="cell-title"><a href="https://www.notion.so/90-33e790c945e880d0bd88e96e5aeea250?pvs=21">90</a></td><td class="cell-p`pi">MarsGT: multi-omics analysis for rare population inference using single-cell graph transformer</td><td class="cell-YVW["><em>Nature Communications</em></td><td class="cell-WUOX">2024</td></tr><tr id="33e790c9-45e8-8002-bc5c-e40152eb35d2"><td class="cell-title"><a href="https://www.notion.so/91-33e790c945e88002bc5ce40152eb35d2?pvs=21">91</a></td><td class="cell-p`pi">Multimodal data fusion for cancer biomarker discovery with deep learning</td><td class="cell-YVW["><em>npj Precision Oncology</em></td><td class="cell-WUOX">2023</td></tr><tr id="33e790c9-45e8-8068-864a-c8268c84f5e5"><td class="cell-title"><a href="https://www.notion.so/92-33e790c945e88068864ac8268c84f5e5?pvs=21">92</a></td><td class="cell-p`pi">MOFA+: a statistical framework for comprehensive integration of multi-modal single-cell data</td><td class="cell-YVW["><em>Genome Biology</em></td><td class="cell-WUOX">2020</td></tr><tr id="33e790c9-45e8-805e-b6e8-cbfbc929d134"><td class="cell-title"><a href="https://www.notion.so/93-33e790c945e8805eb6e8cbfbc929d134?pvs=21">93</a></td><td class="cell-p`pi">ArchR: an integrative and scalable software package for single-cell chromatin accessibility analysis</td><td class="cell-YVW["><em>Nature Genetics</em></td><td class="cell-WUOX">2021</td></tr><tr id="33e790c9-45e8-8089-a358-ced1260b7577"><td class="cell-title"><a href="https://www.notion.so/94-33e790c945e88089a358ced1260b7577?pvs=21">94</a></td><td class="cell-p`pi">Seurat v4: multi-modal integration of single-cell data</td><td class="cell-YVW["><em>Cell</em></td><td class="cell-WUOX">2021</td></tr></tbody></table></div><br/><br/></div></div><div style="display:contents" dir="auto"><hr id="33e790c9-45e8-8065-b5df-eaf67695107d"/></div><div style="display:contents" dir="ltr"><div id="33e790c9-45e8-8001-bff8-f5d4a3dcdf86" class="collection-content"><h4 class="collection-title">十、伦理、监管与临床转化（6篇）</h4><div class="collection-content-wrapper"><table class="collection-content"><thead><tr><th><span class="icon property-icon"><img src="https://www.notion.so/icons/font_gray.svg" style="width:14px;height:14px;display:block"/></span>#</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>标题</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>期刊</th><th><span class="icon property-icon"><img src="https://www.notion.so/icons/description_gray.svg" style="width:14px;height:14px;display:block"/></span>年份</th></tr></thead><tbody><tr id="33e790c9-45e8-809b-a04d-f92d7b4d7899"><td class="cell-title"><a href="https://www.notion.so/95-33e790c945e8809ba04df92d7b4d7899?pvs=21">95</a></td><td class="cell-gvCy">Artificial intelligence in reproductive medicine — an ethical perspective</td><td class="cell-~qh:"><em>Geburtshilfe Frauenheilkd</em></td><td class="cell-}{ZW">2023</td></tr><tr id="33e790c9-45e8-80dc-9c35-c3181dee2bf3"><td class="cell-title"><a href="https://www.notion.so/96-33e790c945e880dc9c35c3181dee2bf3?pvs=21">96</a></td><td class="cell-gvCy">Patient perspectives on the use of AI in health care: a scoping review</td><td class="cell-~qh:"><em>J Patient Centered Research</em></td><td class="cell-}{ZW">2024</td></tr><tr id="33e790c9-45e8-8090-85c7-d13f94c14010"><td class="cell-title"><a href="https://www.notion.so/97-33e790c945e8809085c7d13f94c14010?pvs=21">97</a></td><td class="cell-gvCy">The perception of AI and infertility care among patients undergoing fertility treatment</td><td class="cell-~qh:"><em>J Assist Reprod Genet</em></td><td class="cell-}{ZW">2025</td></tr><tr id="33e790c9-45e8-80b5-870e-c7d13f7652f0"><td class="cell-title"><a href="https://www.notion.so/98-33e790c945e880b5870ec7d13f7652f0?pvs=21">98</a></td><td class="cell-gvCy">AI as a door opener for a new era of human reproduction</td><td class="cell-~qh:"><em>Human Reproduction Open</em></td><td class="cell-}{ZW">2023</td></tr><tr id="33e790c9-45e8-80da-8634-ffc48c630195"><td class="cell-title"><a href="https://www.notion.so/99-33e790c945e880da8634ffc48c630195?pvs=21">99</a></td><td class="cell-gvCy">From hype to reality: data science enabling personalized medicine</td><td class="cell-~qh:"><em>BMC Medicine</em></td><td class="cell-}{ZW">2018</td></tr><tr id="33e790c9-45e8-803f-9da2-e6665003eba8"><td class="cell-title"><a href="https://www.notion.so/100-33e790c945e8803f9da2e6665003eba8?pvs=21">100</a></td><td class="cell-gvCy">Externally validated and clinically useful machine learning algorithms in oncology: a scoping review（方法学参考）</td><td class="cell-~qh:"><em>BMC Med Res Methodol</em></td><td class="cell-}{ZW">2025</td></tr></tbody></table></div><br/><br/></div></div><div style="display:contents" dir="auto"><hr id="33e790c9-45e8-8083-ab7d-e5a5a76f077c"/></div><div style="display:contents" dir="auto"><h2 id="33e790c9-45e8-800a-bbbd-cc5abea85708" class="">使用建议</h2></div><div style="display:contents" dir="auto"><p id="33e790c9-45e8-8061-941d-d9f8212cb861" class="">这100篇文献覆盖了该综述应包含的<strong>10个核心模块</strong>：</p></div><div style="display:contents" dir="auto"><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="33e790c9-45e8-8055-9884-fc0380dd1bfb" class="code code-wrap"><code class="language-Plain Text" style="white-space:pre-wrap;word-break:break-all">综述框架建议（一年写作规划）

第4-6月   文献精读 + 框架确定
├── 模块①②：总览 + IVF临床AI（确定切入点）
└── 模块⑨⑩：方法论 + 伦理（建立论证基础）

第7-9月   核心内容撰写
├── 模块③④⑤：单细胞/空间组学 + GRN（技术主线）
└── 模块⑥：表观组学（机制主线）

第10-12月   进阶内容撰写
├── 模块⑦：类胚体模型（前沿应用）
└── 模块⑧：活体成像AI（技术创新）

第1-3月 整合、修订、投稿
└── 全稿审改 + 图表制作 + 期刊选择</code></pre></div><div style="display:contents" dir="auto"><p id="33e790c9-45e8-8036-af3f-c3bc928f3ca0" class=""><strong>目标期刊建议</strong>（根据综述定位）：</p></div><div style="display:contents" dir="auto"><ul id="33e790c9-45e8-8059-ab53-da1610982e52" class="bulleted-list"><li style="list-style-type:disc">偏临床：<em>Human Reproduction Update</em>（IF ~15）, <em>Fertility &amp; Sterility</em></li></ul></div><div style="display:contents" dir="auto"><ul id="33e790c9-45e8-8053-ba00-fc082c187c63" class="bulleted-list"><li style="list-style-type:disc">偏技术：<em>Briefings in Bioinformatics</em>, <em>Nature Methods</em>（难度较高）</li></ul></div><div style="display:contents" dir="auto"><ul id="33e790c9-45e8-80f6-9a04-e9cc506e9751" class="bulleted-list"><li style="list-style-type:disc">偏综合：<em>Development</em>, <em>Cell Systems</em>, <em>iScience</em></li></ul></div></div></article><span class="sans" style="font-size:14px;padding-top:2em"></span></body></html>
