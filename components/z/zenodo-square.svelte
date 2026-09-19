<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nepf93bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="nepf93bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:zenodo-square" {...props}></Icon>
