<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng_83soyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ng_83soyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:wind-arrow-down" {...props}></Icon>
