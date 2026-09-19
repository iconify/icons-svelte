<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjn7tl86z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fjn7tl86z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:soap" {...props}></Icon>
