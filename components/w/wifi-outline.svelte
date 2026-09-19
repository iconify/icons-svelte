<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdvk-d6wd.css';
import '../../css/i/ikeeb1b_d.css';
import '../../css/w/w_a4xnomr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<g class="gdvk-d6wd"><path class="ikeeb1b_d"/><path class="w_a4xnomr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:wifi-outline" {...props}></Icon>
