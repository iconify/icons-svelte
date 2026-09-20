<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6uo6sbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6uo6sbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-strength-2-lock" {...props}></Icon>
