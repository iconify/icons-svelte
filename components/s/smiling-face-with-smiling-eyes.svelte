<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dzw3x5b8o.css';
import '../../css/l/lvh0zsbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="dzw3x5b8o"/><path class="lvh0zsbby"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:smiling-face-with-smiling-eyes" {...props}></Icon>
