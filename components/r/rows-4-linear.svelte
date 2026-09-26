<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/weddopsmh.css';
import '../../css/l/l4trkhdsa.css';
import '../../css/n/nm9cb2_cm.css';
import '../../css/b/b2vvr6bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="weddopsmh"/><path class="l4trkhdsa"/><path class="nm9cb2_cm"/><path class="b2vvr6bvh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rows-4-linear" {...props}></Icon>
