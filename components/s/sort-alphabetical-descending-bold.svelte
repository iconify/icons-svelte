<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0w-96bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="y0w-96bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sort-alphabetical-descending-bold" {...props}></Icon>
