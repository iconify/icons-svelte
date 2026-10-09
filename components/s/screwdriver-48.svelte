<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si-3bpbzc.css';
import '../../css/y/yck_bwygh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="si-3bpbzc"/><path class="yck_bwygh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:screwdriver-48" {...props}></Icon>
