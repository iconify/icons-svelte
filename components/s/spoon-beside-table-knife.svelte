<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le02kybtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="le02kybtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spoon-beside-table-knife" {...props}></Icon>
