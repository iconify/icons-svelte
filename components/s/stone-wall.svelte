<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpf011s-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fpf011s-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:stone-wall" {...props}></Icon>
