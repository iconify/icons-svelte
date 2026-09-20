<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysq-5acba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ysq-5acba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sedan-with-raised-hood-under-wrench" {...props}></Icon>
