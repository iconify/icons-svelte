<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xanv8655i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="xanv8655i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-facebook" {...props}></Icon>
