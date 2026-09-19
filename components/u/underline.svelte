<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0xo9w8dr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0xo9w8dr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:underline" {...props}></Icon>
