<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvg9dfb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvg9dfb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tilde" {...props}></Icon>
