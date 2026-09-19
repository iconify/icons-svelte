<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up4k305kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="up4k305kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:shapes-outline" {...props}></Icon>
