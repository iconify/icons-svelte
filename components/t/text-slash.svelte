<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yymi86flf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="yymi86flf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:text-slash" {...props}></Icon>
