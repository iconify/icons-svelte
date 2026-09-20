<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn_bipmzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kn_bipmzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-transportation-sail-ship-travel-boat-transportation-transport-ocean-ship-sea-water" {...props}></Icon>
