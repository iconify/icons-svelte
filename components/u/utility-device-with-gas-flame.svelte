<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/araq3t5cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="araq3t5cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:utility-device-with-gas-flame" {...props}></Icon>
