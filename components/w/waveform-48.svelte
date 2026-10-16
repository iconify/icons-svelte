<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4pi18-ok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x4pi18-ok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:waveform-48" {...props}></Icon>
