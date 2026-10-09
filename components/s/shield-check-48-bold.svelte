<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce0cywmuu.css';
import '../../css/x/xnv-ktb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ce0cywmuu"/><path class="xnv-ktb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-check-48-bold" {...props}></Icon>
