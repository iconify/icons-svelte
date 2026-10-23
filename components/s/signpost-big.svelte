<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_z5ifmad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_z5ifmad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:signpost-big" {...props}></Icon>
