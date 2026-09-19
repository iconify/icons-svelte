<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxc7n1kon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hxc7n1kon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:wallet" {...props}></Icon>
