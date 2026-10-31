<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/g/g0ccqzb9w.css';
import '../../css/w/w1fhcebii.css';
import '../../css/x/xeddqab8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="g0ccqzb9w wm-shadow"/><path class="w1fhcebii wm-shadow"/><path class="xeddqab8p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:wifi-low" {...props}></Icon>
