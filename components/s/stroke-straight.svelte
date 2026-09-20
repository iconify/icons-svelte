<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx3_vxixm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cx3_vxixm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:stroke-straight" {...props}></Icon>
