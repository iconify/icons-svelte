<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfh612bxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mfh612bxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:workbox" {...props}></Icon>
