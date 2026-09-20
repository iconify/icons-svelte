<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xixbvxbcd.css';
import '../../css/s/sboz3ieoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xixbvxbcd"/><path class="sboz3ieoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:sd-card-download-bold" {...props}></Icon>
