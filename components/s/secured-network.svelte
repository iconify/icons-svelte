<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/zdhvhb4hv.css';
import '../../css/r/rhpb7tbqf.css';
import '../../css/u/u_fqmub8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="zdhvhb4hv"/><path class="rhpb7tbqf"/><path class="u_fqmub8u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:secured-network" {...props}></Icon>
