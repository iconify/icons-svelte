<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrt_0fbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrt_0fbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:square-kanban" {...props}></Icon>
