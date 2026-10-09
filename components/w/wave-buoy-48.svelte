<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud8-gub-u.css';
import '../../css/d/da77vd8hl.css';
import '../../css/r/rrj52fbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ud8-gub-u"/><path class="da77vd8hl"/><path class="rrj52fbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wave-buoy-48" {...props}></Icon>
