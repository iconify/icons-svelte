<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkir8nb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jkir8nb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:screen-full" {...props}></Icon>
