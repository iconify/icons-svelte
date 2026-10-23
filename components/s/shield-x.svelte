<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj4x2qbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uj4x2qbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:shield-x" {...props}></Icon>
