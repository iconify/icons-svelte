<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0vpjqb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y0vpjqb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wifi-off-20-bold" {...props}></Icon>
