<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7fz9o70k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="h7fz9o70k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:ubuntu" {...props}></Icon>
