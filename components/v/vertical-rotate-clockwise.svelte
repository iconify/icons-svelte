<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g34get5ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g34get5ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vertical-rotate-clockwise" {...props}></Icon>
