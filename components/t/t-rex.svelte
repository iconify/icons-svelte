<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpzfoabrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpzfoabrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:t-rex" {...props}></Icon>
