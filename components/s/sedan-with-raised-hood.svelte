<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq2m70lut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xq2m70lut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sedan-with-raised-hood" {...props}></Icon>
