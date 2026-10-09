<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppm3_br9v.css';
import '../../css/r/rh3ta1ono.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ppm3_br9v"/><path class="rh3ta1ono"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thumbs-up-48" {...props}></Icon>
