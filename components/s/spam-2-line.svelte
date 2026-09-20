<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct1chmerr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct1chmerr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:spam-2-line" {...props}></Icon>
