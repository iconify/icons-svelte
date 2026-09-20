<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0amaqwhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s0amaqwhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:twenty-crm-light" {...props}></Icon>
