<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crjh0zb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crjh0zb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:yuanbao-line" {...props}></Icon>
