<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2cw-qbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2cw-qbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wifi-off-duotone-round" {...props}></Icon>
