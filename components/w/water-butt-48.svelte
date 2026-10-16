<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdvp-0bcn.css';
import '../../css/h/hbbh9n7le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kdvp-0bcn"/><path class="hbbh9n7le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:water-butt-48" {...props}></Icon>
