<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoojuxfxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yoojuxfxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:web-section-alt" {...props}></Icon>
