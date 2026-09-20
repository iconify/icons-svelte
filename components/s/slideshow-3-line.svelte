<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgh_qzbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgh_qzbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:slideshow-3-line" {...props}></Icon>
