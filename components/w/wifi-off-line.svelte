<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzqfh5bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzqfh5bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:wifi-off-line" {...props}></Icon>
