<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcjn2w3es.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcjn2w3es"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:spade-filled" {...props}></Icon>
