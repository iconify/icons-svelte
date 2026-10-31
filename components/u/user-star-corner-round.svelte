<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpeeh0b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpeeh0b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-star-corner-round" {...props}></Icon>
