<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx8s6199m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kx8s6199m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:telephone" {...props}></Icon>
