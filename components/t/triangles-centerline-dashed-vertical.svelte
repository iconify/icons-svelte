<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z98wpl-ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z98wpl-ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:triangles-centerline-dashed-vertical" {...props}></Icon>
