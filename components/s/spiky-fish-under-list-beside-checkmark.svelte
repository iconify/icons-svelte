<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5ny2v5ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r5ny2v5ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spiky-fish-under-list-beside-checkmark" {...props}></Icon>
