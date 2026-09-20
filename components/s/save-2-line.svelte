<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5orysb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5orysb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:save-2-line" {...props}></Icon>
