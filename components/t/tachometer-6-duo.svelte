<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rymil3blb.css';
import '../../css/t/tworusbgp.css';
import '../../css/q/qo8w8tbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rymil3blb"/><path class="tworusbgp"/><path class="qo8w8tbbo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tachometer-6-duo" {...props}></Icon>
