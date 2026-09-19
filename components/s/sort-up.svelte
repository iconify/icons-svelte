<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7f5jf0ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="y7f5jf0ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:sort-up" {...props}></Icon>
