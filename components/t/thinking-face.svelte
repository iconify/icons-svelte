<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imsv_jbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="imsv_jbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:thinking-face" {...props}></Icon>
