<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpgv9kb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fpgv9kb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wave-energy-converter-48" {...props}></Icon>
