<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd3nyebrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd3nyebrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:tiktok-alt" {...props}></Icon>
