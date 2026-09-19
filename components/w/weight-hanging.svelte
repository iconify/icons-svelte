<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxpm_ebjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bxpm_ebjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:weight-hanging" {...props}></Icon>
