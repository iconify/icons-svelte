<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkut9chyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="rkut9chyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:school-flag" {...props}></Icon>
