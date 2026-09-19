<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9k58leho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i9k58leho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:shoelace" {...props}></Icon>
