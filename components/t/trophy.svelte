<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv37jub_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sv37jub_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:trophy" {...props}></Icon>
