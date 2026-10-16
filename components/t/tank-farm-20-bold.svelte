<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhs5b57iy.css';
import '../../css/y/yfoxxnbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mhs5b57iy"/><path class="yfoxxnbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tank-farm-20-bold" {...props}></Icon>
