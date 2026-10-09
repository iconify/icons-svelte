<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liot4-bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="liot4-bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wave-energy-converter-48-bold" {...props}></Icon>
