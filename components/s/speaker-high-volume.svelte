<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h90lgebck.css';
import '../../css/q/qh1gefkwh.css';
import '../../css/i/inhki6bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="h90lgebck"/><path class="qh1gefkwh"/><path class="inhki6bwd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:speaker-high-volume" {...props}></Icon>
