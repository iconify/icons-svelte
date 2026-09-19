<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6a1ky2xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1152,"height":1664};
const content = `<path class="i6a1ky2xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:thumb-tack" {...props}></Icon>
