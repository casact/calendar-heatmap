# calendar-heatmap

GitHub-style calendar heatmap, rendered as a matplotlib figure or a
self-contained, hoverable SVG.

<svg class="cal-heatmap" viewBox="0 0 810 186" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Calendar heatmap" font-family="-apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, &quot;Noto Sans&quot;, Helvetica, Arial, sans-serif">
<style>
.cal-heatmap .cal-heatmap-cell { cursor: default; transition: stroke 0.1s ease; }
.cal-heatmap .cal-heatmap-cell:hover { stroke: #1c6ea8; stroke-width: 1.5; }
</style>
<text x="405.0" y="16" text-anchor="middle" font-size="14" font-weight="bold" class="cal-heatmap-title">Daily insurance claim counts, 2025 (hover a day)</text>
<text x="28" y="36" font-size="12" fill="#656d76" class="cal-heatmap-label">Jan</text>
<text x="84" y="36" font-size="12" fill="#656d76" class="cal-heatmap-label">Feb</text>
<text x="140" y="36" font-size="12" fill="#656d76" class="cal-heatmap-label">Mar</text>
<text x="210" y="36" font-size="12" fill="#656d76" class="cal-heatmap-label">Apr</text>
<text x="266" y="36" font-size="12" fill="#656d76" class="cal-heatmap-label">May</text>
<text x="322" y="36" font-size="12" fill="#656d76" class="cal-heatmap-label">Jun</text>
<text x="392" y="36" font-size="12" fill="#656d76" class="cal-heatmap-label">Jul</text>
<text x="448" y="36" font-size="12" fill="#656d76" class="cal-heatmap-label">Aug</text>
<text x="518" y="36" font-size="12" fill="#656d76" class="cal-heatmap-label">Sep</text>
<text x="574" y="36" font-size="12" fill="#656d76" class="cal-heatmap-label">Oct</text>
<text x="630" y="36" font-size="12" fill="#656d76" class="cal-heatmap-label">Nov</text>
<text x="700" y="36" font-size="12" fill="#656d76" class="cal-heatmap-label">Dec</text>
<text x="22" y="68" text-anchor="end" font-size="12" fill="#656d76" class="cal-heatmap-label">Mon</text>
<text x="22" y="96" text-anchor="end" font-size="12" fill="#656d76" class="cal-heatmap-label">Wed</text>
<text x="22" y="124" text-anchor="end" font-size="12" fill="#656d76" class="cal-heatmap-label">Fri</text>
<rect class="cal-heatmap-cell" x="28" y="86" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on January 1, 2025</title></rect>
<rect class="cal-heatmap-cell" x="28" y="100" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on January 2, 2025</title></rect>
<rect class="cal-heatmap-cell" x="28" y="114" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on January 3, 2025</title></rect>
<rect class="cal-heatmap-cell" x="28" y="128" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on January 4, 2025</title></rect>
<rect class="cal-heatmap-cell" x="28" y="44" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on January 5, 2025</title></rect>
<rect class="cal-heatmap-cell" x="28" y="58" width="11" height="11" rx="2" ry="2" fill="#ebedf0"><title>0 claims on January 6, 2025</title></rect>
<rect class="cal-heatmap-cell" x="28" y="72" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on January 7, 2025</title></rect>
<rect class="cal-heatmap-cell" x="42" y="86" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on January 8, 2025</title></rect>
<rect class="cal-heatmap-cell" x="42" y="100" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on January 9, 2025</title></rect>
<rect class="cal-heatmap-cell" x="42" y="114" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on January 10, 2025</title></rect>
<rect class="cal-heatmap-cell" x="42" y="128" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on January 11, 2025</title></rect>
<rect class="cal-heatmap-cell" x="42" y="44" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on January 12, 2025</title></rect>
<rect class="cal-heatmap-cell" x="42" y="58" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on January 13, 2025</title></rect>
<rect class="cal-heatmap-cell" x="42" y="72" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on January 14, 2025</title></rect>
<rect class="cal-heatmap-cell" x="56" y="86" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>2 claims on January 15, 2025</title></rect>
<rect class="cal-heatmap-cell" x="56" y="100" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>1 claim on January 16, 2025</title></rect>
<rect class="cal-heatmap-cell" x="56" y="114" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on January 17, 2025</title></rect>
<rect class="cal-heatmap-cell" x="56" y="128" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on January 18, 2025</title></rect>
<rect class="cal-heatmap-cell" x="56" y="44" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on January 19, 2025</title></rect>
<rect class="cal-heatmap-cell" x="56" y="58" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on January 20, 2025</title></rect>
<rect class="cal-heatmap-cell" x="56" y="72" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on January 21, 2025</title></rect>
<rect class="cal-heatmap-cell" x="70" y="86" width="11" height="11" rx="2" ry="2" fill="#ebedf0"><title>0 claims on January 22, 2025</title></rect>
<rect class="cal-heatmap-cell" x="70" y="100" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>2 claims on January 23, 2025</title></rect>
<rect class="cal-heatmap-cell" x="70" y="114" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on January 24, 2025</title></rect>
<rect class="cal-heatmap-cell" x="70" y="128" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on January 25, 2025</title></rect>
<rect class="cal-heatmap-cell" x="70" y="44" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on January 26, 2025</title></rect>
<rect class="cal-heatmap-cell" x="70" y="58" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on January 27, 2025</title></rect>
<rect class="cal-heatmap-cell" x="70" y="72" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on January 28, 2025</title></rect>
<rect class="cal-heatmap-cell" x="84" y="86" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on January 29, 2025</title></rect>
<rect class="cal-heatmap-cell" x="84" y="100" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>1 claim on January 30, 2025</title></rect>
<rect class="cal-heatmap-cell" x="84" y="114" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on January 31, 2025</title></rect>
<rect class="cal-heatmap-cell" x="84" y="128" width="11" height="11" rx="2" ry="2" fill="#ebedf0"><title>0 claims on February 1, 2025</title></rect>
<rect class="cal-heatmap-cell" x="84" y="44" width="11" height="11" rx="2" ry="2" fill="#ebedf0"><title>0 claims on February 2, 2025</title></rect>
<rect class="cal-heatmap-cell" x="84" y="58" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>2 claims on February 3, 2025</title></rect>
<rect class="cal-heatmap-cell" x="84" y="72" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>2 claims on February 4, 2025</title></rect>
<rect class="cal-heatmap-cell" x="98" y="86" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on February 5, 2025</title></rect>
<rect class="cal-heatmap-cell" x="98" y="100" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on February 6, 2025</title></rect>
<rect class="cal-heatmap-cell" x="98" y="114" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>1 claim on February 7, 2025</title></rect>
<rect class="cal-heatmap-cell" x="98" y="128" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on February 8, 2025</title></rect>
<rect class="cal-heatmap-cell" x="98" y="44" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>2 claims on February 9, 2025</title></rect>
<rect class="cal-heatmap-cell" x="98" y="58" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on February 10, 2025</title></rect>
<rect class="cal-heatmap-cell" x="98" y="72" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on February 11, 2025</title></rect>
<rect class="cal-heatmap-cell" x="112" y="86" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on February 12, 2025</title></rect>
<rect class="cal-heatmap-cell" x="112" y="100" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on February 13, 2025</title></rect>
<rect class="cal-heatmap-cell" x="112" y="114" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on February 14, 2025</title></rect>
<rect class="cal-heatmap-cell" x="112" y="128" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on February 15, 2025</title></rect>
<rect class="cal-heatmap-cell" x="112" y="44" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on February 16, 2025</title></rect>
<rect class="cal-heatmap-cell" x="112" y="58" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on February 17, 2025</title></rect>
<rect class="cal-heatmap-cell" x="112" y="72" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on February 18, 2025</title></rect>
<rect class="cal-heatmap-cell" x="126" y="86" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>2 claims on February 19, 2025</title></rect>
<rect class="cal-heatmap-cell" x="126" y="100" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on February 20, 2025</title></rect>
<rect class="cal-heatmap-cell" x="126" y="114" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on February 21, 2025</title></rect>
<rect class="cal-heatmap-cell" x="126" y="128" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on February 22, 2025</title></rect>
<rect class="cal-heatmap-cell" x="126" y="44" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>9 claims on February 23, 2025</title></rect>
<rect class="cal-heatmap-cell" x="126" y="58" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on February 24, 2025</title></rect>
<rect class="cal-heatmap-cell" x="126" y="72" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>2 claims on February 25, 2025</title></rect>
<rect class="cal-heatmap-cell" x="140" y="86" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>6 claims on February 26, 2025</title></rect>
<rect class="cal-heatmap-cell" x="140" y="100" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on February 27, 2025</title></rect>
<rect class="cal-heatmap-cell" x="140" y="114" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>6 claims on February 28, 2025</title></rect>
<rect class="cal-heatmap-cell" x="140" y="128" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>6 claims on March 1, 2025</title></rect>
<rect class="cal-heatmap-cell" x="140" y="44" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on March 2, 2025</title></rect>
<rect class="cal-heatmap-cell" x="140" y="58" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on March 3, 2025</title></rect>
<rect class="cal-heatmap-cell" x="140" y="72" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>2 claims on March 4, 2025</title></rect>
<rect class="cal-heatmap-cell" x="154" y="86" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on March 5, 2025</title></rect>
<rect class="cal-heatmap-cell" x="154" y="100" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on March 6, 2025</title></rect>
<rect class="cal-heatmap-cell" x="154" y="114" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>2 claims on March 7, 2025</title></rect>
<rect class="cal-heatmap-cell" x="154" y="128" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on March 8, 2025</title></rect>
<rect class="cal-heatmap-cell" x="154" y="44" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>6 claims on March 9, 2025</title></rect>
<rect class="cal-heatmap-cell" x="154" y="58" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on March 10, 2025</title></rect>
<rect class="cal-heatmap-cell" x="154" y="72" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on March 11, 2025</title></rect>
<rect class="cal-heatmap-cell" x="168" y="86" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on March 12, 2025</title></rect>
<rect class="cal-heatmap-cell" x="168" y="100" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on March 13, 2025</title></rect>
<rect class="cal-heatmap-cell" x="168" y="114" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on March 14, 2025</title></rect>
<rect class="cal-heatmap-cell" x="168" y="128" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on March 15, 2025</title></rect>
<rect class="cal-heatmap-cell" x="168" y="44" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on March 16, 2025</title></rect>
<rect class="cal-heatmap-cell" x="168" y="58" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on March 17, 2025</title></rect>
<rect class="cal-heatmap-cell" x="168" y="72" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on March 18, 2025</title></rect>
<rect class="cal-heatmap-cell" x="182" y="86" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on March 19, 2025</title></rect>
<rect class="cal-heatmap-cell" x="182" y="100" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>6 claims on March 20, 2025</title></rect>
<rect class="cal-heatmap-cell" x="182" y="114" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on March 21, 2025</title></rect>
<rect class="cal-heatmap-cell" x="182" y="128" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on March 22, 2025</title></rect>
<rect class="cal-heatmap-cell" x="182" y="44" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>6 claims on March 23, 2025</title></rect>
<rect class="cal-heatmap-cell" x="182" y="58" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>2 claims on March 24, 2025</title></rect>
<rect class="cal-heatmap-cell" x="182" y="72" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on March 25, 2025</title></rect>
<rect class="cal-heatmap-cell" x="196" y="86" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on March 26, 2025</title></rect>
<rect class="cal-heatmap-cell" x="196" y="100" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on March 27, 2025</title></rect>
<rect class="cal-heatmap-cell" x="196" y="114" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on March 28, 2025</title></rect>
<rect class="cal-heatmap-cell" x="196" y="128" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on March 29, 2025</title></rect>
<rect class="cal-heatmap-cell" x="196" y="44" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on March 30, 2025</title></rect>
<rect class="cal-heatmap-cell" x="196" y="58" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on March 31, 2025</title></rect>
<rect class="cal-heatmap-cell" x="196" y="72" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on April 1, 2025</title></rect>
<rect class="cal-heatmap-cell" x="210" y="86" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on April 2, 2025</title></rect>
<rect class="cal-heatmap-cell" x="210" y="100" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on April 3, 2025</title></rect>
<rect class="cal-heatmap-cell" x="210" y="114" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on April 4, 2025</title></rect>
<rect class="cal-heatmap-cell" x="210" y="128" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on April 5, 2025</title></rect>
<rect class="cal-heatmap-cell" x="210" y="44" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>9 claims on April 6, 2025</title></rect>
<rect class="cal-heatmap-cell" x="210" y="58" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on April 7, 2025</title></rect>
<rect class="cal-heatmap-cell" x="210" y="72" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on April 8, 2025</title></rect>
<rect class="cal-heatmap-cell" x="224" y="86" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on April 9, 2025</title></rect>
<rect class="cal-heatmap-cell" x="224" y="100" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on April 10, 2025</title></rect>
<rect class="cal-heatmap-cell" x="224" y="114" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>13 claims on April 11, 2025</title></rect>
<rect class="cal-heatmap-cell" x="224" y="128" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>9 claims on April 12, 2025</title></rect>
<rect class="cal-heatmap-cell" x="224" y="44" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on April 13, 2025</title></rect>
<rect class="cal-heatmap-cell" x="224" y="58" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on April 14, 2025</title></rect>
<rect class="cal-heatmap-cell" x="224" y="72" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on April 15, 2025</title></rect>
<rect class="cal-heatmap-cell" x="238" y="86" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>13 claims on April 16, 2025</title></rect>
<rect class="cal-heatmap-cell" x="238" y="100" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on April 17, 2025</title></rect>
<rect class="cal-heatmap-cell" x="238" y="114" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on April 18, 2025</title></rect>
<rect class="cal-heatmap-cell" x="238" y="128" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>2 claims on April 19, 2025</title></rect>
<rect class="cal-heatmap-cell" x="238" y="44" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on April 20, 2025</title></rect>
<rect class="cal-heatmap-cell" x="238" y="58" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on April 21, 2025</title></rect>
<rect class="cal-heatmap-cell" x="238" y="72" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on April 22, 2025</title></rect>
<rect class="cal-heatmap-cell" x="252" y="86" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on April 23, 2025</title></rect>
<rect class="cal-heatmap-cell" x="252" y="100" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on April 24, 2025</title></rect>
<rect class="cal-heatmap-cell" x="252" y="114" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>15 claims on April 25, 2025</title></rect>
<rect class="cal-heatmap-cell" x="252" y="128" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>6 claims on April 26, 2025</title></rect>
<rect class="cal-heatmap-cell" x="252" y="44" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>9 claims on April 27, 2025</title></rect>
<rect class="cal-heatmap-cell" x="252" y="58" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on April 28, 2025</title></rect>
<rect class="cal-heatmap-cell" x="252" y="72" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>9 claims on April 29, 2025</title></rect>
<rect class="cal-heatmap-cell" x="266" y="86" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>9 claims on April 30, 2025</title></rect>
<rect class="cal-heatmap-cell" x="266" y="100" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on May 1, 2025</title></rect>
<rect class="cal-heatmap-cell" x="266" y="114" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>6 claims on May 2, 2025</title></rect>
<rect class="cal-heatmap-cell" x="266" y="128" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on May 3, 2025</title></rect>
<rect class="cal-heatmap-cell" x="266" y="44" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on May 4, 2025</title></rect>
<rect class="cal-heatmap-cell" x="266" y="58" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on May 5, 2025</title></rect>
<rect class="cal-heatmap-cell" x="266" y="72" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on May 6, 2025</title></rect>
<rect class="cal-heatmap-cell" x="280" y="86" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>18 claims on May 7, 2025</title></rect>
<rect class="cal-heatmap-cell" x="280" y="100" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>12 claims on May 8, 2025</title></rect>
<rect class="cal-heatmap-cell" x="280" y="114" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on May 9, 2025</title></rect>
<rect class="cal-heatmap-cell" x="280" y="128" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on May 10, 2025</title></rect>
<rect class="cal-heatmap-cell" x="280" y="44" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on May 11, 2025</title></rect>
<rect class="cal-heatmap-cell" x="280" y="58" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>12 claims on May 12, 2025</title></rect>
<rect class="cal-heatmap-cell" x="280" y="72" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>17 claims on May 13, 2025</title></rect>
<rect class="cal-heatmap-cell" x="294" y="86" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>6 claims on May 14, 2025</title></rect>
<rect class="cal-heatmap-cell" x="294" y="100" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>15 claims on May 15, 2025</title></rect>
<rect class="cal-heatmap-cell" x="294" y="114" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on May 16, 2025</title></rect>
<rect class="cal-heatmap-cell" x="294" y="128" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>17 claims on May 17, 2025</title></rect>
<rect class="cal-heatmap-cell" x="294" y="44" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on May 18, 2025</title></rect>
<rect class="cal-heatmap-cell" x="294" y="58" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>12 claims on May 19, 2025</title></rect>
<rect class="cal-heatmap-cell" x="294" y="72" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on May 20, 2025</title></rect>
<rect class="cal-heatmap-cell" x="308" y="86" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on May 21, 2025</title></rect>
<rect class="cal-heatmap-cell" x="308" y="100" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>13 claims on May 22, 2025</title></rect>
<rect class="cal-heatmap-cell" x="308" y="114" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>12 claims on May 23, 2025</title></rect>
<rect class="cal-heatmap-cell" x="308" y="128" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>20 claims on May 24, 2025</title></rect>
<rect class="cal-heatmap-cell" x="308" y="44" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on May 25, 2025</title></rect>
<rect class="cal-heatmap-cell" x="308" y="58" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on May 26, 2025</title></rect>
<rect class="cal-heatmap-cell" x="308" y="72" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on May 27, 2025</title></rect>
<rect class="cal-heatmap-cell" x="322" y="86" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on May 28, 2025</title></rect>
<rect class="cal-heatmap-cell" x="322" y="100" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on May 29, 2025</title></rect>
<rect class="cal-heatmap-cell" x="322" y="114" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on May 30, 2025</title></rect>
<rect class="cal-heatmap-cell" x="322" y="128" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>18 claims on May 31, 2025</title></rect>
<rect class="cal-heatmap-cell" x="322" y="44" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>13 claims on June 1, 2025</title></rect>
<rect class="cal-heatmap-cell" x="322" y="58" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>9 claims on June 2, 2025</title></rect>
<rect class="cal-heatmap-cell" x="322" y="72" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>15 claims on June 3, 2025</title></rect>
<rect class="cal-heatmap-cell" x="336" y="86" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>15 claims on June 4, 2025</title></rect>
<rect class="cal-heatmap-cell" x="336" y="100" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>15 claims on June 5, 2025</title></rect>
<rect class="cal-heatmap-cell" x="336" y="114" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on June 6, 2025</title></rect>
<rect class="cal-heatmap-cell" x="336" y="128" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>18 claims on June 7, 2025</title></rect>
<rect class="cal-heatmap-cell" x="336" y="44" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on June 8, 2025</title></rect>
<rect class="cal-heatmap-cell" x="336" y="58" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on June 9, 2025</title></rect>
<rect class="cal-heatmap-cell" x="336" y="72" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>18 claims on June 10, 2025</title></rect>
<rect class="cal-heatmap-cell" x="350" y="86" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on June 11, 2025</title></rect>
<rect class="cal-heatmap-cell" x="350" y="100" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>15 claims on June 12, 2025</title></rect>
<rect class="cal-heatmap-cell" x="350" y="114" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>22 claims on June 13, 2025</title></rect>
<rect class="cal-heatmap-cell" x="350" y="128" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>15 claims on June 14, 2025</title></rect>
<rect class="cal-heatmap-cell" x="350" y="44" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>13 claims on June 15, 2025</title></rect>
<rect class="cal-heatmap-cell" x="350" y="58" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on June 16, 2025</title></rect>
<rect class="cal-heatmap-cell" x="350" y="72" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>20 claims on June 17, 2025</title></rect>
<rect class="cal-heatmap-cell" x="364" y="86" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>15 claims on June 18, 2025</title></rect>
<rect class="cal-heatmap-cell" x="364" y="100" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on June 19, 2025</title></rect>
<rect class="cal-heatmap-cell" x="364" y="114" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>19 claims on June 20, 2025</title></rect>
<rect class="cal-heatmap-cell" x="364" y="128" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>12 claims on June 21, 2025</title></rect>
<rect class="cal-heatmap-cell" x="364" y="44" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on June 22, 2025</title></rect>
<rect class="cal-heatmap-cell" x="364" y="58" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on June 23, 2025</title></rect>
<rect class="cal-heatmap-cell" x="364" y="72" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>15 claims on June 24, 2025</title></rect>
<rect class="cal-heatmap-cell" x="378" y="86" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>12 claims on June 25, 2025</title></rect>
<rect class="cal-heatmap-cell" x="378" y="100" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>18 claims on June 26, 2025</title></rect>
<rect class="cal-heatmap-cell" x="378" y="114" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>17 claims on June 27, 2025</title></rect>
<rect class="cal-heatmap-cell" x="378" y="128" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on June 28, 2025</title></rect>
<rect class="cal-heatmap-cell" x="378" y="44" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>17 claims on June 29, 2025</title></rect>
<rect class="cal-heatmap-cell" x="378" y="58" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on June 30, 2025</title></rect>
<rect class="cal-heatmap-cell" x="378" y="72" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>9 claims on July 1, 2025</title></rect>
<rect class="cal-heatmap-cell" x="392" y="86" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on July 2, 2025</title></rect>
<rect class="cal-heatmap-cell" x="392" y="100" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>15 claims on July 3, 2025</title></rect>
<rect class="cal-heatmap-cell" x="392" y="114" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>12 claims on July 4, 2025</title></rect>
<rect class="cal-heatmap-cell" x="392" y="128" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>17 claims on July 5, 2025</title></rect>
<rect class="cal-heatmap-cell" x="392" y="44" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>17 claims on July 6, 2025</title></rect>
<rect class="cal-heatmap-cell" x="392" y="58" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>13 claims on July 7, 2025</title></rect>
<rect class="cal-heatmap-cell" x="392" y="72" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on July 8, 2025</title></rect>
<rect class="cal-heatmap-cell" x="406" y="86" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>19 claims on July 9, 2025</title></rect>
<rect class="cal-heatmap-cell" x="406" y="100" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>12 claims on July 10, 2025</title></rect>
<rect class="cal-heatmap-cell" x="406" y="114" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on July 11, 2025</title></rect>
<rect class="cal-heatmap-cell" x="406" y="128" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>15 claims on July 12, 2025</title></rect>
<rect class="cal-heatmap-cell" x="406" y="44" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>24 claims on July 13, 2025</title></rect>
<rect class="cal-heatmap-cell" x="406" y="58" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on July 14, 2025</title></rect>
<rect class="cal-heatmap-cell" x="406" y="72" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>18 claims on July 15, 2025</title></rect>
<rect class="cal-heatmap-cell" x="420" y="86" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on July 16, 2025</title></rect>
<rect class="cal-heatmap-cell" x="420" y="100" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>15 claims on July 17, 2025</title></rect>
<rect class="cal-heatmap-cell" x="420" y="114" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>22 claims on July 18, 2025</title></rect>
<rect class="cal-heatmap-cell" x="420" y="128" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>15 claims on July 19, 2025</title></rect>
<rect class="cal-heatmap-cell" x="420" y="44" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>24 claims on July 20, 2025</title></rect>
<rect class="cal-heatmap-cell" x="420" y="58" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>13 claims on July 21, 2025</title></rect>
<rect class="cal-heatmap-cell" x="420" y="72" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on July 22, 2025</title></rect>
<rect class="cal-heatmap-cell" x="434" y="86" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>13 claims on July 23, 2025</title></rect>
<rect class="cal-heatmap-cell" x="434" y="100" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>12 claims on July 24, 2025</title></rect>
<rect class="cal-heatmap-cell" x="434" y="114" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>15 claims on July 25, 2025</title></rect>
<rect class="cal-heatmap-cell" x="434" y="128" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on July 26, 2025</title></rect>
<rect class="cal-heatmap-cell" x="434" y="44" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on July 27, 2025</title></rect>
<rect class="cal-heatmap-cell" x="434" y="58" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on July 28, 2025</title></rect>
<rect class="cal-heatmap-cell" x="434" y="72" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>23 claims on July 29, 2025</title></rect>
<rect class="cal-heatmap-cell" x="448" y="86" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on July 30, 2025</title></rect>
<rect class="cal-heatmap-cell" x="448" y="100" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>22 claims on July 31, 2025</title></rect>
<rect class="cal-heatmap-cell" x="448" y="114" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on August 1, 2025</title></rect>
<rect class="cal-heatmap-cell" x="448" y="128" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on August 2, 2025</title></rect>
<rect class="cal-heatmap-cell" x="448" y="44" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>27 claims on August 3, 2025</title></rect>
<rect class="cal-heatmap-cell" x="448" y="58" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on August 4, 2025</title></rect>
<rect class="cal-heatmap-cell" x="448" y="72" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>9 claims on August 5, 2025</title></rect>
<rect class="cal-heatmap-cell" x="462" y="86" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>13 claims on August 6, 2025</title></rect>
<rect class="cal-heatmap-cell" x="462" y="100" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on August 7, 2025</title></rect>
<rect class="cal-heatmap-cell" x="462" y="114" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>17 claims on August 8, 2025</title></rect>
<rect class="cal-heatmap-cell" x="462" y="128" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>20 claims on August 9, 2025</title></rect>
<rect class="cal-heatmap-cell" x="462" y="44" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on August 10, 2025</title></rect>
<rect class="cal-heatmap-cell" x="462" y="58" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on August 11, 2025</title></rect>
<rect class="cal-heatmap-cell" x="462" y="72" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>13 claims on August 12, 2025</title></rect>
<rect class="cal-heatmap-cell" x="476" y="86" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>19 claims on August 13, 2025</title></rect>
<rect class="cal-heatmap-cell" x="476" y="100" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on August 14, 2025</title></rect>
<rect class="cal-heatmap-cell" x="476" y="114" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on August 15, 2025</title></rect>
<rect class="cal-heatmap-cell" x="476" y="128" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on August 16, 2025</title></rect>
<rect class="cal-heatmap-cell" x="476" y="44" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>20 claims on August 17, 2025</title></rect>
<rect class="cal-heatmap-cell" x="476" y="58" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>22 claims on August 18, 2025</title></rect>
<rect class="cal-heatmap-cell" x="476" y="72" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on August 19, 2025</title></rect>
<rect class="cal-heatmap-cell" x="490" y="86" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>15 claims on August 20, 2025</title></rect>
<rect class="cal-heatmap-cell" x="490" y="100" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>9 claims on August 21, 2025</title></rect>
<rect class="cal-heatmap-cell" x="490" y="114" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on August 22, 2025</title></rect>
<rect class="cal-heatmap-cell" x="490" y="128" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on August 23, 2025</title></rect>
<rect class="cal-heatmap-cell" x="490" y="44" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on August 24, 2025</title></rect>
<rect class="cal-heatmap-cell" x="490" y="58" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on August 25, 2025</title></rect>
<rect class="cal-heatmap-cell" x="490" y="72" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>12 claims on August 26, 2025</title></rect>
<rect class="cal-heatmap-cell" x="504" y="86" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>9 claims on August 27, 2025</title></rect>
<rect class="cal-heatmap-cell" x="504" y="100" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on August 28, 2025</title></rect>
<rect class="cal-heatmap-cell" x="504" y="114" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>9 claims on August 29, 2025</title></rect>
<rect class="cal-heatmap-cell" x="504" y="128" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on August 30, 2025</title></rect>
<rect class="cal-heatmap-cell" x="504" y="44" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on August 31, 2025</title></rect>
<rect class="cal-heatmap-cell" x="504" y="58" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>12 claims on September 1, 2025</title></rect>
<rect class="cal-heatmap-cell" x="504" y="72" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>15 claims on September 2, 2025</title></rect>
<rect class="cal-heatmap-cell" x="518" y="86" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>19 claims on September 3, 2025</title></rect>
<rect class="cal-heatmap-cell" x="518" y="100" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>13 claims on September 4, 2025</title></rect>
<rect class="cal-heatmap-cell" x="518" y="114" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>17 claims on September 5, 2025</title></rect>
<rect class="cal-heatmap-cell" x="518" y="128" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>12 claims on September 6, 2025</title></rect>
<rect class="cal-heatmap-cell" x="518" y="44" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on September 7, 2025</title></rect>
<rect class="cal-heatmap-cell" x="518" y="58" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on September 8, 2025</title></rect>
<rect class="cal-heatmap-cell" x="518" y="72" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>18 claims on September 9, 2025</title></rect>
<rect class="cal-heatmap-cell" x="532" y="86" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>16 claims on September 10, 2025</title></rect>
<rect class="cal-heatmap-cell" x="532" y="100" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on September 11, 2025</title></rect>
<rect class="cal-heatmap-cell" x="532" y="114" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>24 claims on September 12, 2025</title></rect>
<rect class="cal-heatmap-cell" x="532" y="128" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>12 claims on September 13, 2025</title></rect>
<rect class="cal-heatmap-cell" x="532" y="44" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>15 claims on September 14, 2025</title></rect>
<rect class="cal-heatmap-cell" x="532" y="58" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>13 claims on September 15, 2025</title></rect>
<rect class="cal-heatmap-cell" x="532" y="72" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on September 16, 2025</title></rect>
<rect class="cal-heatmap-cell" x="546" y="86" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>20 claims on September 17, 2025</title></rect>
<rect class="cal-heatmap-cell" x="546" y="100" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>17 claims on September 18, 2025</title></rect>
<rect class="cal-heatmap-cell" x="546" y="114" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on September 19, 2025</title></rect>
<rect class="cal-heatmap-cell" x="546" y="128" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on September 20, 2025</title></rect>
<rect class="cal-heatmap-cell" x="546" y="44" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>13 claims on September 21, 2025</title></rect>
<rect class="cal-heatmap-cell" x="546" y="58" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on September 22, 2025</title></rect>
<rect class="cal-heatmap-cell" x="546" y="72" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on September 23, 2025</title></rect>
<rect class="cal-heatmap-cell" x="560" y="86" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on September 24, 2025</title></rect>
<rect class="cal-heatmap-cell" x="560" y="100" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on September 25, 2025</title></rect>
<rect class="cal-heatmap-cell" x="560" y="114" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on September 26, 2025</title></rect>
<rect class="cal-heatmap-cell" x="560" y="128" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on September 27, 2025</title></rect>
<rect class="cal-heatmap-cell" x="560" y="44" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>12 claims on September 28, 2025</title></rect>
<rect class="cal-heatmap-cell" x="560" y="58" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on September 29, 2025</title></rect>
<rect class="cal-heatmap-cell" x="560" y="72" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on September 30, 2025</title></rect>
<rect class="cal-heatmap-cell" x="574" y="86" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on October 1, 2025</title></rect>
<rect class="cal-heatmap-cell" x="574" y="100" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>12 claims on October 2, 2025</title></rect>
<rect class="cal-heatmap-cell" x="574" y="114" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>12 claims on October 3, 2025</title></rect>
<rect class="cal-heatmap-cell" x="574" y="128" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on October 4, 2025</title></rect>
<rect class="cal-heatmap-cell" x="574" y="44" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>13 claims on October 5, 2025</title></rect>
<rect class="cal-heatmap-cell" x="574" y="58" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on October 6, 2025</title></rect>
<rect class="cal-heatmap-cell" x="574" y="72" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on October 7, 2025</title></rect>
<rect class="cal-heatmap-cell" x="588" y="86" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on October 8, 2025</title></rect>
<rect class="cal-heatmap-cell" x="588" y="100" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on October 9, 2025</title></rect>
<rect class="cal-heatmap-cell" x="588" y="114" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on October 10, 2025</title></rect>
<rect class="cal-heatmap-cell" x="588" y="128" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on October 11, 2025</title></rect>
<rect class="cal-heatmap-cell" x="588" y="44" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on October 12, 2025</title></rect>
<rect class="cal-heatmap-cell" x="588" y="58" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on October 13, 2025</title></rect>
<rect class="cal-heatmap-cell" x="588" y="72" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on October 14, 2025</title></rect>
<rect class="cal-heatmap-cell" x="602" y="86" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on October 15, 2025</title></rect>
<rect class="cal-heatmap-cell" x="602" y="100" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on October 16, 2025</title></rect>
<rect class="cal-heatmap-cell" x="602" y="114" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on October 17, 2025</title></rect>
<rect class="cal-heatmap-cell" x="602" y="128" width="11" height="11" rx="2" ry="2" fill="#216e39"><title>14 claims on October 18, 2025</title></rect>
<rect class="cal-heatmap-cell" x="602" y="44" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>9 claims on October 19, 2025</title></rect>
<rect class="cal-heatmap-cell" x="602" y="58" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on October 20, 2025</title></rect>
<rect class="cal-heatmap-cell" x="602" y="72" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on October 21, 2025</title></rect>
<rect class="cal-heatmap-cell" x="616" y="86" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on October 22, 2025</title></rect>
<rect class="cal-heatmap-cell" x="616" y="100" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on October 23, 2025</title></rect>
<rect class="cal-heatmap-cell" x="616" y="114" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on October 24, 2025</title></rect>
<rect class="cal-heatmap-cell" x="616" y="128" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on October 25, 2025</title></rect>
<rect class="cal-heatmap-cell" x="616" y="44" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>13 claims on October 26, 2025</title></rect>
<rect class="cal-heatmap-cell" x="616" y="58" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on October 27, 2025</title></rect>
<rect class="cal-heatmap-cell" x="616" y="72" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on October 28, 2025</title></rect>
<rect class="cal-heatmap-cell" x="630" y="86" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>6 claims on October 29, 2025</title></rect>
<rect class="cal-heatmap-cell" x="630" y="100" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on October 30, 2025</title></rect>
<rect class="cal-heatmap-cell" x="630" y="114" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on October 31, 2025</title></rect>
<rect class="cal-heatmap-cell" x="630" y="128" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on November 1, 2025</title></rect>
<rect class="cal-heatmap-cell" x="630" y="44" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>9 claims on November 2, 2025</title></rect>
<rect class="cal-heatmap-cell" x="630" y="58" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on November 3, 2025</title></rect>
<rect class="cal-heatmap-cell" x="630" y="72" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>13 claims on November 4, 2025</title></rect>
<rect class="cal-heatmap-cell" x="644" y="86" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>9 claims on November 5, 2025</title></rect>
<rect class="cal-heatmap-cell" x="644" y="100" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>2 claims on November 6, 2025</title></rect>
<rect class="cal-heatmap-cell" x="644" y="114" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on November 7, 2025</title></rect>
<rect class="cal-heatmap-cell" x="644" y="128" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>6 claims on November 8, 2025</title></rect>
<rect class="cal-heatmap-cell" x="644" y="44" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on November 9, 2025</title></rect>
<rect class="cal-heatmap-cell" x="644" y="58" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on November 10, 2025</title></rect>
<rect class="cal-heatmap-cell" x="644" y="72" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on November 11, 2025</title></rect>
<rect class="cal-heatmap-cell" x="658" y="86" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>1 claim on November 12, 2025</title></rect>
<rect class="cal-heatmap-cell" x="658" y="100" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on November 13, 2025</title></rect>
<rect class="cal-heatmap-cell" x="658" y="114" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on November 14, 2025</title></rect>
<rect class="cal-heatmap-cell" x="658" y="128" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>9 claims on November 15, 2025</title></rect>
<rect class="cal-heatmap-cell" x="658" y="44" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>11 claims on November 16, 2025</title></rect>
<rect class="cal-heatmap-cell" x="658" y="58" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on November 17, 2025</title></rect>
<rect class="cal-heatmap-cell" x="658" y="72" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>1 claim on November 18, 2025</title></rect>
<rect class="cal-heatmap-cell" x="672" y="86" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on November 19, 2025</title></rect>
<rect class="cal-heatmap-cell" x="672" y="100" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>1 claim on November 20, 2025</title></rect>
<rect class="cal-heatmap-cell" x="672" y="114" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on November 21, 2025</title></rect>
<rect class="cal-heatmap-cell" x="672" y="128" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>6 claims on November 22, 2025</title></rect>
<rect class="cal-heatmap-cell" x="672" y="44" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on November 23, 2025</title></rect>
<rect class="cal-heatmap-cell" x="672" y="58" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>10 claims on November 24, 2025</title></rect>
<rect class="cal-heatmap-cell" x="672" y="72" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>7 claims on November 25, 2025</title></rect>
<rect class="cal-heatmap-cell" x="686" y="86" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>1 claim on November 26, 2025</title></rect>
<rect class="cal-heatmap-cell" x="686" y="100" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>6 claims on November 27, 2025</title></rect>
<rect class="cal-heatmap-cell" x="686" y="114" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on November 28, 2025</title></rect>
<rect class="cal-heatmap-cell" x="686" y="128" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on November 29, 2025</title></rect>
<rect class="cal-heatmap-cell" x="686" y="44" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on November 30, 2025</title></rect>
<rect class="cal-heatmap-cell" x="686" y="58" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on December 1, 2025</title></rect>
<rect class="cal-heatmap-cell" x="686" y="72" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>2 claims on December 2, 2025</title></rect>
<rect class="cal-heatmap-cell" x="700" y="86" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on December 3, 2025</title></rect>
<rect class="cal-heatmap-cell" x="700" y="100" width="11" height="11" rx="2" ry="2" fill="#30a14e"><title>9 claims on December 4, 2025</title></rect>
<rect class="cal-heatmap-cell" x="700" y="114" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on December 5, 2025</title></rect>
<rect class="cal-heatmap-cell" x="700" y="128" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on December 6, 2025</title></rect>
<rect class="cal-heatmap-cell" x="700" y="44" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on December 7, 2025</title></rect>
<rect class="cal-heatmap-cell" x="700" y="58" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on December 8, 2025</title></rect>
<rect class="cal-heatmap-cell" x="700" y="72" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>6 claims on December 9, 2025</title></rect>
<rect class="cal-heatmap-cell" x="714" y="86" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on December 10, 2025</title></rect>
<rect class="cal-heatmap-cell" x="714" y="100" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>2 claims on December 11, 2025</title></rect>
<rect class="cal-heatmap-cell" x="714" y="114" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>8 claims on December 12, 2025</title></rect>
<rect class="cal-heatmap-cell" x="714" y="128" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>6 claims on December 13, 2025</title></rect>
<rect class="cal-heatmap-cell" x="714" y="44" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on December 14, 2025</title></rect>
<rect class="cal-heatmap-cell" x="714" y="58" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on December 15, 2025</title></rect>
<rect class="cal-heatmap-cell" x="714" y="72" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>2 claims on December 16, 2025</title></rect>
<rect class="cal-heatmap-cell" x="728" y="86" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>6 claims on December 17, 2025</title></rect>
<rect class="cal-heatmap-cell" x="728" y="100" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>4 claims on December 18, 2025</title></rect>
<rect class="cal-heatmap-cell" x="728" y="114" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on December 19, 2025</title></rect>
<rect class="cal-heatmap-cell" x="728" y="128" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on December 20, 2025</title></rect>
<rect class="cal-heatmap-cell" x="728" y="44" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on December 21, 2025</title></rect>
<rect class="cal-heatmap-cell" x="728" y="58" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on December 22, 2025</title></rect>
<rect class="cal-heatmap-cell" x="728" y="72" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on December 23, 2025</title></rect>
<rect class="cal-heatmap-cell" x="742" y="86" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on December 24, 2025</title></rect>
<rect class="cal-heatmap-cell" x="742" y="100" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on December 25, 2025</title></rect>
<rect class="cal-heatmap-cell" x="742" y="114" width="11" height="11" rx="2" ry="2" fill="#40c463"><title>5 claims on December 26, 2025</title></rect>
<rect class="cal-heatmap-cell" x="742" y="128" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>3 claims on December 27, 2025</title></rect>
<rect class="cal-heatmap-cell" x="742" y="44" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>2 claims on December 28, 2025</title></rect>
<rect class="cal-heatmap-cell" x="742" y="58" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>2 claims on December 29, 2025</title></rect>
<rect class="cal-heatmap-cell" x="742" y="72" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>2 claims on December 30, 2025</title></rect>
<rect class="cal-heatmap-cell" x="756" y="86" width="11" height="11" rx="2" ry="2" fill="#9be9a8"><title>1 claim on December 31, 2025</title></rect>
<text x="702" y="162" text-anchor="end" font-size="12" fill="#656d76" class="cal-heatmap-label">Less</text>
<rect x="708" y="152" width="11" height="11" rx="2" ry="2" fill="#ebedf0"></rect>
<rect x="722" y="152" width="11" height="11" rx="2" ry="2" fill="#9be9a8"></rect>
<rect x="736" y="152" width="11" height="11" rx="2" ry="2" fill="#40c463"></rect>
<rect x="750" y="152" width="11" height="11" rx="2" ry="2" fill="#30a14e"></rect>
<rect x="764" y="152" width="11" height="11" rx="2" ry="2" fill="#216e39"></rect>
<text x="782" y="162" font-size="12" fill="#656d76" class="cal-heatmap-label">More</text>
</svg>

*Synthetic daily insurance claim counts for a year — claims trend higher in
summer and lower in the colder months. Generated by
[`examples/generate_example.py`](examples/generate_example.py). Hover a day
to see its claim count — this is the actual `.to_svg()` output, embedded
directly (not via `<img>`, which would sandbox it and disable hover
entirely). GitHub's markdown renderer strips `<style>` tags, so the blue
hover ring you'd see in a plain HTML page doesn't show here, but the
`<title>` tooltip and all the colors/fonts do, since those are set as SVG
attributes rather than CSS.*

## Install

```bash
pip install calendar-heatmap
```

## Usage

```python
from datetime import date
import matplotlib.pyplot as plt
from calendar_heatmap import CalendarHeatmap

data = {
    date(2026, 1, 3): 4,
    date(2026, 1, 4): 1,
    date(2026, 2, 14): 9,
}

heatmap = CalendarHeatmap(data)

ax = heatmap.plot(title="Activity in the last year")
plt.show()
```

`data` maps each active date to a numeric value (e.g. a commit count); dates
missing from `data` are treated as zero. Anything with a `.to_dict()` method,
such as a pandas `Series` indexed by date, works too.

`CalendarHeatmap(data, ...)` computes the calendar window and color buckets
once; call `.plot()` and/or `.to_svg()` on it as many times as you like to
render that same data in either form.

### `.plot()` — matplotlib

```python
ax = heatmap.plot(ax=None, title="Activity in the last year")
```

Draws onto a matplotlib `Axes` and returns it, so it composes with the rest
of the matplotlib API — pass `ax=` to draw into an existing figure/subplot,
save the figure with `ax.figure.savefig(...)`, etc.

- `ax` — Axes to draw onto. A new figure/Axes is created if omitted.
- `show_legend`, `legend_labels` — control the "Less → More" legend.
- `title` — optional title above the calendar.
- `font_family` — font (or ordered fallback list) for the title, tick labels,
  and legend text. See
  [`examples/generate_example.py`](examples/generate_example.py) for an
  example that matches GitHub's own UI font stack.

### `.to_svg()` — interactive SVG

```python
svg = heatmap.to_svg(title="Activity in the last year", path="heatmap.svg")
```

Renders a self-contained SVG string with a native `<title>` tooltip on every
cell and a CSS `:hover` highlight — meant to be embedded directly in an HTML
page (not via `<img>`, which sandboxes the SVG from the page's CSS entirely).
GitHub's own README/markdown renderer strips `<style>` tags, so the hover
highlight and font only apply outside of GitHub's markdown sanitizer; the
`<title>` tooltip itself is unaffected.

- `show_legend`, `legend_labels`, `title` — same as `.plot()`.
- `font_family` — CSS `font-family` value for the SVG's text (default
  `"sans-serif"`).
- `label_color` — CSS color for the month/day-of-week labels and legend text.
- `tooltip_fn` — a `(date, value) -> str` callable producing each cell's
  tooltip text. Defaults to `"{value} on {date}"`.
- `path` — if given, also writes the SVG markup to this file path.

### Shared options (constructor)

- `start`, `end` — bound the calendar window explicitly (defaults to the
  `weeks` weeks before `end`, snapped back to the preceding Sunday).
- `weeks` — width of the default window, in weeks (default `53`).
- `colors` — sequence of fill colors for increasing activity buckets, low to
  high (default: GitHub's green ramp).
- `zero_color` — fill color for zero/missing days.

## Development

```bash
pip install -e ".[test]"
pytest
```
