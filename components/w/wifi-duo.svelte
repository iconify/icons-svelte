<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qym2g0yhd.css';
import '../../css/c/cvygwcb1l.css';
import '../../css/a/a5ognjdal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="qym2g0yhd"/><path class="cvygwcb1l"/><path class="a5ognjdal"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wifi-duo" {...props}></Icon>
