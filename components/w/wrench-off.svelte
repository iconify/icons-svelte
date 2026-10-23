<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9x7_fvwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9x7_fvwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:wrench-off" {...props}></Icon>
