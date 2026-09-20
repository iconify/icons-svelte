<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_3q33btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_3q33btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-strength-0-lock" {...props}></Icon>
