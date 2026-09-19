<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9yt772bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t9yt772bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:temperature-low" {...props}></Icon>
