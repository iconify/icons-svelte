<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckfp8xsti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckfp8xsti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:shield-off-solid" {...props}></Icon>
