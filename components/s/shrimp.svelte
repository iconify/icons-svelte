<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir91d7qdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ir91d7qdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:shrimp" {...props}></Icon>
