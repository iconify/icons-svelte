<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-n0pf_-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-n0pf_-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:zoom-in-filled" {...props}></Icon>
