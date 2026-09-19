<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktcjmyg5d.css';
import '../../css/i/isi39nobh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktcjmyg5d"/><path class="isi39nobh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:whatsapp-square" {...props}></Icon>
