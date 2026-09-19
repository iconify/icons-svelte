<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4nlppewx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="u4nlppewx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:truck-plane" {...props}></Icon>
