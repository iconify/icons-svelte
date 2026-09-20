<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fid1iybje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fid1iybje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:scroll-to-bottom-line" {...props}></Icon>
