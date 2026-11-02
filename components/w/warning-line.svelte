<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if38d7ble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="if38d7ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:warning-line" {...props}></Icon>
