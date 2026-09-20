<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isx_nccxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isx_nccxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ssh" {...props}></Icon>
