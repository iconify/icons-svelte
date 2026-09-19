<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh-t99bfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="nh-t99bfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:skypeonline" {...props}></Icon>
