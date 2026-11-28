<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fparf6bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="fparf6bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sort-alphabetical-descending-fill" {...props}></Icon>
