<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3byzibuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3byzibuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:swap-horizontal-circle-outline" {...props}></Icon>
