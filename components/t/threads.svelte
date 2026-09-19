<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5m0l1bto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n5m0l1bto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:threads" {...props}></Icon>
