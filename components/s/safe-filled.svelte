<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s07htpbtb.css';
import '../../css/v/vslx-5blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s07htpbtb"/><path class="vslx-5blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:safe-filled" {...props}></Icon>
