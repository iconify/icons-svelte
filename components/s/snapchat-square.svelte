<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_2vdmzzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="g_2vdmzzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:snapchat-square" {...props}></Icon>
