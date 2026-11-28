<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i71m81irf.css';
import '../../css/d/d28o-tblo.css';
import '../../css/w/wwwii2bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="i71m81irf"/><path class="d28o-tblo"/><path class="wwwii2bho"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:unlock" {...props}></Icon>
