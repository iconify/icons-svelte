<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex7vb15ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ex7vb15ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:waveform-20" {...props}></Icon>
