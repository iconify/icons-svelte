<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enc1vmb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="enc1vmb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:tumble-dry" {...props}></Icon>
