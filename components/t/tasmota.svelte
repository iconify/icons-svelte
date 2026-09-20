<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb8o1sbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb8o1sbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tasmota" {...props}></Icon>
