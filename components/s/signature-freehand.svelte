<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8wft1lvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8wft1lvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:signature-freehand" {...props}></Icon>
