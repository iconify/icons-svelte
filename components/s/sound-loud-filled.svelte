<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcsywwuje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rcsywwuje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:sound-loud-filled" {...props}></Icon>
