<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxaqqbb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":384};
const content = `<path class="pxaqqbb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:rss" {...props}></Icon>
