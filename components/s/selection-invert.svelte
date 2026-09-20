<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl-9vxerp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl-9vxerp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:selection-invert" {...props}></Icon>
