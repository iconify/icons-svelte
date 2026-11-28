<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw9dhccbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lw9dhccbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:waveform" {...props}></Icon>
