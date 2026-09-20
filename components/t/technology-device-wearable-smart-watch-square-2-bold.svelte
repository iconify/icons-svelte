<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmz1djcqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmz1djcqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:technology-device-wearable-smart-watch-square-2-bold" {...props}></Icon>
