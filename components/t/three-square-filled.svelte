<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b-l6dcceu.css';
import '../../css/r/r5jmk_bor.css';
import '../../css/i/i21ar1oaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b-l6dcceu"/><path class="r5jmk_bor"/><path class="i21ar1oaf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:three-square-filled" {...props}></Icon>
