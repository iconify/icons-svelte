<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwrz3wh0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fwrz3wh0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:scale-sharp" {...props}></Icon>
