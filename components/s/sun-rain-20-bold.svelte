<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h28y0dbgc.css';
import '../../css/e/eixy3mbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h28y0dbgc"/><path class="eixy3mbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-rain-20-bold" {...props}></Icon>
