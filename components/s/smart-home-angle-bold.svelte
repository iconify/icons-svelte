<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/st9wqpxoy.css';
import '../../css/a/afwe0cb7c.css';
import '../../css/n/nl4g2jbjn.css';
import '../../css/a/asu_8f8hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="st9wqpxoy"/><path class="afwe0cb7c"/><path class="nl4g2jbjn"/><path class="asu_8f8hx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smart-home-angle-bold" {...props}></Icon>
