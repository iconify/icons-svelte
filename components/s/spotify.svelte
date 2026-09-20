<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a15ueac_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="a15ueac_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:spotify" {...props}></Icon>
