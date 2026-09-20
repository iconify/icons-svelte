<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5exk6e-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="f5exk6e-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:veterinary-14" {...props}></Icon>
