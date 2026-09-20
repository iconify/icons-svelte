<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x729vib_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x729vib_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:vectors-pen-draw" {...props}></Icon>
