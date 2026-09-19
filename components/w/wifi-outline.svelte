<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss6umgmez.css';
import '../../css/x/xelml5b_j.css';
import '../../css/u/u51rzi9rf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ss6umgmez"/><path class="xelml5b_j"/><path class="u51rzi9rf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:wifi-outline" {...props}></Icon>
