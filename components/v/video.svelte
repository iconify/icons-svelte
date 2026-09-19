<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clsdao61r.css';
import '../../css/z/zc3lmmbma.css';
import '../../css/v/vbv_9ysna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="clsdao61r"><path class="zc3lmmbma"/><path class="vbv_9ysna"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:video" {...props}></Icon>
