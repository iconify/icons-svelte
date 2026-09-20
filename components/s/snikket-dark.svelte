<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyssyt-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xyssyt-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:snikket-dark" {...props}></Icon>
