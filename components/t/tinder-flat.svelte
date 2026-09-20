<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8-6i4bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="n8-6i4bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:tinder-flat" {...props}></Icon>
