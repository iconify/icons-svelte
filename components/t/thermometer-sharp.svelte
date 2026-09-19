<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p745bwb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p745bwb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:thermometer-sharp" {...props}></Icon>
