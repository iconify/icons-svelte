<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2f6oxbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2f6oxbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:tablet" {...props}></Icon>
