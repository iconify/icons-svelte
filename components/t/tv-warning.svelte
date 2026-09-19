<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/grgc8lbgv.css';
import '../../css/x/xt0fr7bdi.css';
import '../../css/k/k1fp4vtcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="grgc8lbgv"/><path class="xt0fr7bdi"/><path class="k1fp4vtcf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:tv-warning" {...props}></Icon>
