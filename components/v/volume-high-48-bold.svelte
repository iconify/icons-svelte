<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc5lbibdl.css';
import '../../css/w/wna2nnb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kc5lbibdl"/><path class="wna2nnb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:volume-high-48-bold" {...props}></Icon>
