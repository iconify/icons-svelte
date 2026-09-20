<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxx8p7oda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxx8p7oda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:voiceprint-line" {...props}></Icon>
