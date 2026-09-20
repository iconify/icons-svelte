<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_mfufgeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_mfufgeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:screen-lock-rotation" {...props}></Icon>
