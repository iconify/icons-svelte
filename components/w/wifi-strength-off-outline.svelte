<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlq_zyvnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlq_zyvnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-strength-off-outline" {...props}></Icon>
