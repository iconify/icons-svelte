<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6k8ln9vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6k8ln9vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:timeline-fill" {...props}></Icon>
