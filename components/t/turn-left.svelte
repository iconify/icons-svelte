<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l45ra6buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l45ra6buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:turn-left" {...props}></Icon>
