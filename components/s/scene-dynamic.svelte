<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cousj-bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cousj-bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:scene-dynamic" {...props}></Icon>
