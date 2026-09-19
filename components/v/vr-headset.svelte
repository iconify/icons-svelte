<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rawn7f28d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rawn7f28d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:vr-headset" {...props}></Icon>
