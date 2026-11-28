<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k_2h7p16c.css';
import '../../css/t/t07weybnr.css';
import '../../css/v/vzue2ebav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="k_2h7p16c"/><path class="t07weybnr"/><path class="vzue2ebav"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-split-horizontal-duo" {...props}></Icon>
