<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5zn_wegq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5zn_wegq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:sticky-note-sharp" {...props}></Icon>
