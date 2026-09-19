<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxq501boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxq501boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:view-structure-up" {...props}></Icon>
