<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtufn9bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtufn9bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:users" {...props}></Icon>
