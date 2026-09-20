<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkrebeele.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkrebeele"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:telegram" {...props}></Icon>
