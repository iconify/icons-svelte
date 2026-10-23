<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc4lmzb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc4lmzb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:squircle-dashed" {...props}></Icon>
