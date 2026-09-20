<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erj0l9c7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="erj0l9c7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sedan-under-wrench" {...props}></Icon>
