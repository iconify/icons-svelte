<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpd3-cc6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpd3-cc6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:wrench" {...props}></Icon>
