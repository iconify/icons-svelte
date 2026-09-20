<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2yti383j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2yti383j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-strength-1-lock" {...props}></Icon>
