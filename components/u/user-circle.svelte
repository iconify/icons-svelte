<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/u/u3sx6_b3g.css';
import '../../css/c/cej4cjp9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ud95brdct"/><circle class="u3sx6_b3g"/><path class="cej4cjp9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:user-circle" {...props}></Icon>
