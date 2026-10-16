<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0gim_b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n0gim_b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:waveform-48-bold" {...props}></Icon>
