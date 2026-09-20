<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-yqddbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p-yqddbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:ukulele-16" {...props}></Icon>
