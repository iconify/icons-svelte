<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp00vd57h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dp00vd57h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:slider-vertical-filled" {...props}></Icon>
