<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rggip0b4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rggip0b4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:stretch-vertically" {...props}></Icon>
