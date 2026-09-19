<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsit20tsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsit20tsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sonos-era-300" {...props}></Icon>
