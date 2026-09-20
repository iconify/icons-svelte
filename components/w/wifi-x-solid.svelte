<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwm4jrbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwm4jrbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wifi-x-solid" {...props}></Icon>
