<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3ba3acpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":710};
const content = `<path class="g3ba3acpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:simplepie" {...props}></Icon>
