<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn6614b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="fn6614b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:users-slash" {...props}></Icon>
