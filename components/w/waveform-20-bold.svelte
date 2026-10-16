<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z89_jubnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z89_jubnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:waveform-20-bold" {...props}></Icon>
