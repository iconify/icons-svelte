<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxs8qs1ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sxs8qs1ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:the-new-york-times" {...props}></Icon>
