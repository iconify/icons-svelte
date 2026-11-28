<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/yl-5e19tl.css';
import '../../css/r/rl9mryfun.css';
import '../../css/f/f2a5cbb2a.css';
import '../../css/c/cu24_jbbf.css';
import '../../css/d/du9ajlbpd.css';
import '../../css/d/d9ce6ac1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="yl-5e19tl"/><path class="rl9mryfun"/><path class="f2a5cbb2a"/><path class="cu24_jbbf"/><path class="du9ajlbpd"/><path class="d9ce6ac1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scan-face-duo" {...props}></Icon>
