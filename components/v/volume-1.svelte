<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wng3pnz_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wng3pnz_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:volume-1" {...props}></Icon>
