<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffll-1b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ffll-1b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:warning-rhomb" {...props}></Icon>
