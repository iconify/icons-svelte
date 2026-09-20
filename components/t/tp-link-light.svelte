<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uys6emowx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uys6emowx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tp-link-light" {...props}></Icon>
