<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy5c86bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy5c86bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:saudia" {...props}></Icon>
