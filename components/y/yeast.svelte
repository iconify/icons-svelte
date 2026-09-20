<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxr1tjb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxr1tjb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:yeast" {...props}></Icon>
