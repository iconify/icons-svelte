<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m15x6e6na.css';
import '../../css/k/knxlbdceq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m15x6e6na"/><path class="knxlbdceq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xbull" {...props}></Icon>
