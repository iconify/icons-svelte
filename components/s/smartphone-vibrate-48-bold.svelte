<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izjyqdbgb.css';
import '../../css/f/fqvg1ojpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="izjyqdbgb"/><path class="fqvg1ojpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smartphone-vibrate-48-bold" {...props}></Icon>
