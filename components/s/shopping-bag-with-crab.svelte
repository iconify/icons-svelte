<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8ksgsa2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s8ksgsa2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-crab" {...props}></Icon>
