<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvt6bnbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tvt6bnbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:waveform" {...props}></Icon>
