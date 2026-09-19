<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbzv8sbul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1536};
const content = `<path class="vbzv8sbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:stethoscope" {...props}></Icon>
