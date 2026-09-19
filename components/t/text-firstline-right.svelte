<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk4sq3bim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk4sq3bim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-firstline-right" {...props}></Icon>
