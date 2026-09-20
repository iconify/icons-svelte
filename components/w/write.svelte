<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdiwyccpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="sdiwyccpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:write" {...props}></Icon>
