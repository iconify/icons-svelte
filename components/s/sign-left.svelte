<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt74o3_bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zt74o3_bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:sign-left" {...props}></Icon>
