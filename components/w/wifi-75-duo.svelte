<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hy9dkzbqr.css';
import '../../css/h/hyxs7bcqn.css';
import '../../css/n/ndn6ppj7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="hy9dkzbqr"/><path class="hyxs7bcqn"/><path class="ndn6ppj7v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:wifi-75-duo" {...props}></Icon>
