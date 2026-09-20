<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw4x6rw-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw4x6rw-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:single-man-vintage-tv-bold" {...props}></Icon>
