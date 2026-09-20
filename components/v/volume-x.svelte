<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v07v--l5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v07v--l5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:volume-x" {...props}></Icon>
