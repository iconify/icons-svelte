<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwtyhia0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwtyhia0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:twitter-x" {...props}></Icon>
