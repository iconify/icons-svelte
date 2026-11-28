<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjd5uxb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjd5uxb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:server-info" {...props}></Icon>
