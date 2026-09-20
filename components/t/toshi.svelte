<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_uqzkbxl.css';
import '../../css/d/dmbs_cc9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_uqzkbxl"/><path class="dmbs_cc9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:toshi" {...props}></Icon>
