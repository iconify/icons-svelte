<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msv-82bfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msv-82bfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:unacademy" {...props}></Icon>
