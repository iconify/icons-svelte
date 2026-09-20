<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcxy16pkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcxy16pkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:scissors" {...props}></Icon>
