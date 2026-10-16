<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kak06wnga.css';
import '../../css/z/z0454qbpn.css';
import '../../css/d/djxbnjbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kak06wnga"/><path class="z0454qbpn"/><path class="djxbnjbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tidal-lagoon-20-bold" {...props}></Icon>
