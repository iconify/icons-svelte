<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jo0aru4tr.css';
import '../../css/r/rrxhurnze.css';
import '../../css/t/t_y7u4eyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jo0aru4tr"/><path class="rrxhurnze"/><path class="t_y7u4eyk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ruler-pen-broken" {...props}></Icon>
