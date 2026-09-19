<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxlj_x0ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxlj_x0ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:video-slash" {...props}></Icon>
