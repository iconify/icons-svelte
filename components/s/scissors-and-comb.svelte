<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o63smnbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o63smnbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:scissors-and-comb" {...props}></Icon>
