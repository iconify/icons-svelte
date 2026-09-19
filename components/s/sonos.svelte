<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkgd5826b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkgd5826b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sonos" {...props}></Icon>
