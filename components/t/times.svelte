<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl_h1w5_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl_h1w5_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:times" {...props}></Icon>
