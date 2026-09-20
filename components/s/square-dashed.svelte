<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfx2vkxbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfx2vkxbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:square-dashed" {...props}></Icon>
