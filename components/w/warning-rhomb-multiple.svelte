<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfc6bvtpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfc6bvtpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:warning-rhomb-multiple" {...props}></Icon>
