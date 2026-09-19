<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/a/ag4ld1ntb.css';
import '../../css/t/tmhwtbj8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n1lsf0bnc"><path class="ag4ld1ntb"/><path class="tmhwtbj8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:sc-instagram" {...props}></Icon>
