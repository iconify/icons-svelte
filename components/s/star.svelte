<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umm606kxf.css';
import '../../css/u/uh31r0biy.css';
import '../../css/d/d471ab08e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":41,"height":41,"top":-0.5};
const content = `<g class="umm606kxf"><path class="uh31r0biy"/><path class="d471ab08e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-stickies-color:star" {...props}></Icon>
