<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmd-lzd5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmd-lzd5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-strength-outline" {...props}></Icon>
