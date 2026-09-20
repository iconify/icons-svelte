<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmevn97iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmevn97iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:user-circle" {...props}></Icon>
