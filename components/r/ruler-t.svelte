<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-rsb333p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-rsb333p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:ruler-t" {...props}></Icon>
