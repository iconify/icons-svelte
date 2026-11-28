<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0_1o_b6k.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rfq1tw_nw.css';
import '../../css/u/u8ejbjb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary u0_1o_b6k"/><g class="dt0cm9dhy primary"><path class="rfq1tw_nw"/><path class="u8ejbjb9g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:threads-duo" {...props}></Icon>
