<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf99i7bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf99i7bbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:twitter-bird-solid" {...props}></Icon>
