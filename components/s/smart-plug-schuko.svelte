<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8twgrbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8twgrbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:smart-plug-schuko" {...props}></Icon>
