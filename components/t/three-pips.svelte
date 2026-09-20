<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fite9bvmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fite9bvmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:three-pips" {...props}></Icon>
