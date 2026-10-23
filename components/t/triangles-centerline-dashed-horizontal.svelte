<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv78f1c7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv78f1c7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:triangles-centerline-dashed-horizontal" {...props}></Icon>
