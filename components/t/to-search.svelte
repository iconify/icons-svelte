<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu5wmynag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lu5wmynag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:to-search" {...props}></Icon>
