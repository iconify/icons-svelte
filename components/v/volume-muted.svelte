<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khjpa1jsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="khjpa1jsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:volume-muted" {...props}></Icon>
