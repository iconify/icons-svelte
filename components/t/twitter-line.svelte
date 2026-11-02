<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5_utsc8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5_utsc8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:twitter-line" {...props}></Icon>
