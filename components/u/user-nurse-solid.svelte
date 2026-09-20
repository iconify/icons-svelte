<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1zfrcc8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z1zfrcc8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:user-nurse-solid" {...props}></Icon>
