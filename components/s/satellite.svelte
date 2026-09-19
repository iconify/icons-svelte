<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7sb9bv6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":1025};
const content = `<path class="e7sb9bv6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:satellite" {...props}></Icon>
