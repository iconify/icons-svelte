<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/om4qpc7yf.css';
import '../../css/e/ejfa4k2ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="om4qpc7yf"/><path class="ejfa4k2ra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:speedometer" {...props}></Icon>
