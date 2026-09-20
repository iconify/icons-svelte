<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sewx3-8el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sewx3-8el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:trophy-filled" {...props}></Icon>
