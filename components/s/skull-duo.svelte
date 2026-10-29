<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gg9qschrj.css';
import '../../css/w/w3qnxqbjy.css';
import '../../css/t/tjbgnmb3g.css';
import '../../css/o/oum2fkb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gg9qschrj"/><path class="w3qnxqbjy wm-a"/><path class="tjbgnmb3g"/><path class="oum2fkb0t wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:skull-duo" {...props}></Icon>
