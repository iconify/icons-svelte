<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxmj7wz7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="fxmj7wz7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:sim-card" {...props}></Icon>
