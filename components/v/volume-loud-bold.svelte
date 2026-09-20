<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fp7ovzjoy.css';
import '../../css/a/avhjy34yu.css';
import '../../css/i/i_grj_bxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fp7ovzjoy"/><path class="avhjy34yu"/><path class="i_grj_bxx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:volume-loud-bold" {...props}></Icon>
