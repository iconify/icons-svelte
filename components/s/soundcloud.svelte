<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6uon9bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="q6uon9bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:soundcloud" {...props}></Icon>
