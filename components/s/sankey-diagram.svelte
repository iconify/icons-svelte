<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvgqvkbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kvgqvkbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sankey-diagram" {...props}></Icon>
