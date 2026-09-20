<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m501iv-7c.css';
import '../../css/d/ddz586lyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m501iv-7c"/><path class="ddz586lyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sponsorblock" {...props}></Icon>
