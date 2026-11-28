<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl3pr2-vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl3pr2-vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:underline" {...props}></Icon>
