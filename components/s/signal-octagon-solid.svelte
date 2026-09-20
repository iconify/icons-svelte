<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmhw54u1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmhw54u1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:signal-octagon-solid" {...props}></Icon>
