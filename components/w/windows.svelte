<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kngy64yfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":408};
const content = `<path class="kngy64yfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:windows" {...props}></Icon>
