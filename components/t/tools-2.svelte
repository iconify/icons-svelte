<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ix0gdjonx.css';
import '../../css/c/cpr0lubxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="ix0gdjonx"/><path class="cpr0lubxs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:tools-2" {...props}></Icon>
