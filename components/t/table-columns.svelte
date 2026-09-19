<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw0wuyiar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uw0wuyiar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:table-columns" {...props}></Icon>
