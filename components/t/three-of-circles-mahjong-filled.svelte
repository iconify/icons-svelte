<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiip_5bma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="aiip_5bma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:three-of-circles-mahjong-filled" {...props}></Icon>
