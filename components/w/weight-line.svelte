<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akiv3lb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akiv3lb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:weight-line" {...props}></Icon>
