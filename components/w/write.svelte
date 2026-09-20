<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edw-f3fjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="edw-f3fjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:write" {...props}></Icon>
