<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctd37yfjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctd37yfjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:voicemail" {...props}></Icon>
