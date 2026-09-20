<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le-9h2bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="le-9h2bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tooltip-image" {...props}></Icon>
