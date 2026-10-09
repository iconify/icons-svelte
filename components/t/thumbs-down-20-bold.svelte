<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfsfruvhw.css';
import '../../css/e/e9tnf2s0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sfsfruvhw"/><path class="e9tnf2s0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thumbs-down-20-bold" {...props}></Icon>
