<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwh6emb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwh6emb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:surround-sound-3-1" {...props}></Icon>
