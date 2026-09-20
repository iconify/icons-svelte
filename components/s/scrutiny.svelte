<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhdy70bcr.css';
import '../../css/l/l2895_5bw.css';
import '../../css/f/fo69pib0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uhdy70bcr"/><path class="l2895_5bw"/><path class="fo69pib0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scrutiny" {...props}></Icon>
