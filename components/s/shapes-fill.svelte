<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzp181btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzp181btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shapes-fill" {...props}></Icon>
