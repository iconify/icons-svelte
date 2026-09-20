<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiug0vbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hiug0vbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:shot" {...props}></Icon>
