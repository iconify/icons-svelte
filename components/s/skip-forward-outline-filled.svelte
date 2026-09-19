<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irq4-3e5k.css';
import '../../css/d/d-zstca3u.css';
import '../../css/k/klkict4oo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="irq4-3e5k"/><path class="d-zstca3u"/><path class="klkict4oo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:skip-forward-outline-filled" {...props}></Icon>
