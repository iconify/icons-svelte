<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv_1wzb4e.css';
import '../../css/m/m2prtlavp.css';
import '../../css/w/w9bnwpm8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dv_1wzb4e"/><path class="m2prtlavp"/><path class="w9bnwpm8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:silo-media-server-dark" {...props}></Icon>
