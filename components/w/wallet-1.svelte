<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgi0tgbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="pgi0tgbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:wallet-1" {...props}></Icon>
