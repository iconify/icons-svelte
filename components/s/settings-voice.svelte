<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znsu68bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znsu68bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:settings-voice" {...props}></Icon>
