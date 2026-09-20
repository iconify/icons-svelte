<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0t7-1nmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z0t7-1nmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:tv-solid" {...props}></Icon>
