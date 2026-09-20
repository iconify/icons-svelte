<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx0v8cc_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx0v8cc_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zorin" {...props}></Icon>
