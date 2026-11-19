<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7w4r_afr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7w4r_afr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:smart-camera" {...props}></Icon>
