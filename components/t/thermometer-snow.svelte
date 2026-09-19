<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y16v6kbgq.css';
import '../../css/i/ir0h6mb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="y16v6kbgq"/><path class="ir0h6mb0g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:thermometer-snow" {...props}></Icon>
