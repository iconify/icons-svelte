<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wad-esvma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wad-esvma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tachometer-alt-filled" {...props}></Icon>
