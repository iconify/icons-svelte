<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr7ok7mjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="dr7ok7mjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:text-solid" {...props}></Icon>
