<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycty_-fbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ycty_-fbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spoon-beside-table-knife-in-eaved-gabled-building" {...props}></Icon>
