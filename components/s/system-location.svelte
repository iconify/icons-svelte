<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g4tx7vblx.css';
import '../../css/w/wlghgvvky.css';
import '../../css/k/kx5ekhj3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g4tx7vblx"/><path class="wlghgvvky"/><path class="kx5ekhj3l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:system-location" {...props}></Icon>
