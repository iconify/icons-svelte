<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y39xv8bno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y39xv8bno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:star-and-crescent-on-square" {...props}></Icon>
