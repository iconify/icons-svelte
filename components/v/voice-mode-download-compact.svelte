<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvtmg0bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="cvtmg0bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:voice-mode-download-compact" {...props}></Icon>
