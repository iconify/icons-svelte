<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/a70aibbjc.css';
import '../../css/f/f48qsgb5t.css';
import '../../css/y/yj_y3dp7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="a70aibbjc"/><path class="f48qsgb5t wm-a"/><path class="yj_y3dp7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:vault-duo" {...props}></Icon>
