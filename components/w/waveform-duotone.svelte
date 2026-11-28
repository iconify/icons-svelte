<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb2b7xbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary wb2b7xbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:waveform-duotone" {...props}></Icon>
