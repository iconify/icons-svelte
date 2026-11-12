<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdofmibhs.css';
import '../../css/t/trvimmbgr.css';
import '../../css/d/ds9su0blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rdofmibhs"/><path class="trvimmbgr"/><circle class="ds9su0blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:world-monitor-light" {...props}></Icon>
