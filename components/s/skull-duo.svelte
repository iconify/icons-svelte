<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zvjmf6bdk.css';
import '../../css/r/r324r-ddk.css';
import '../../css/h/hk8-dea2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="zvjmf6bdk"/><path class="r324r-ddk"/><path class="hk8-dea2h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:skull-duo" {...props}></Icon>
