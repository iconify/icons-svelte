<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs00j1q9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hs00j1q9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stopwatch-add" {...props}></Icon>
