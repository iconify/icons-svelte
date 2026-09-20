<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl6n36bmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vl6n36bmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wrench-and-hammer" {...props}></Icon>
