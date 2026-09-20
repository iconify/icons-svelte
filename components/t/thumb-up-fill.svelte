<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_9ss8z2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_9ss8z2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:thumb-up-fill" {...props}></Icon>
