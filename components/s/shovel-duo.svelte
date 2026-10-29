<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/krhckl9yo.css';
import '../../css/x/xkg1wybgt.css';
import '../../css/f/fjzpsmbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="krhckl9yo"/><path class="wm-a xkg1wybgt"/><path class="fjzpsmbxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shovel-duo" {...props}></Icon>
