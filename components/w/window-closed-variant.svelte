<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z44o-kmxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z44o-kmxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:window-closed-variant" {...props}></Icon>
