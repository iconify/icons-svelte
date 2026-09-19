<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r5_qsukyp.css';
import '../../css/f/fi71x7bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":37,"height":32};
const content = `<g class="cuyn6tgcc"><path class="r5_qsukyp"/><path class="fi71x7bwr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:video" {...props}></Icon>
