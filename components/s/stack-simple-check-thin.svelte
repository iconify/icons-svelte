<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyzuv-nov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="kyzuv-nov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:stack-simple-check-thin" {...props}></Icon>
