<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc5lbibdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kc5lbibdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:volume-low-48-bold" {...props}></Icon>
