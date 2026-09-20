<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p25p1z9lo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p25p1z9lo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-plane" {...props}></Icon>
