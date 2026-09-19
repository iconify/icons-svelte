<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yws3_pbhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":512};
const content = `<path class="yws3_pbhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:star-of-life" {...props}></Icon>
