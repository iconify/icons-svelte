<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csg993q7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csg993q7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:set-left" {...props}></Icon>
