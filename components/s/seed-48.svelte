<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzgcm9b0v.css';
import '../../css/v/vscquvbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hzgcm9b0v"/><path class="vscquvbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:seed-48" {...props}></Icon>
