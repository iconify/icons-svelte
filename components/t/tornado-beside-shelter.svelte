<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/extss2joy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="extss2joy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tornado-beside-shelter" {...props}></Icon>
