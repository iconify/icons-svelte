<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsf58_ncg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bsf58_ncg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:search" {...props}></Icon>
