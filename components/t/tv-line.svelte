<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otfnt6bcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otfnt6bcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:tv-line" {...props}></Icon>
