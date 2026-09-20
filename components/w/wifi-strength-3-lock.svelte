<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1raw9-zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1raw9-zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-strength-3-lock" {...props}></Icon>
