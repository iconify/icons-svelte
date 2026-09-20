<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xducvmk_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xducvmk_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-hotel-pool-ladder-2-pool-stairs-swim-swimming-water-ladder" {...props}></Icon>
