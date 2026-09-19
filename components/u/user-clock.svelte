<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb8jpq1oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="zb8jpq1oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:user-clock" {...props}></Icon>
