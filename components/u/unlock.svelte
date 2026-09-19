<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oms_6fbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="oms_6fbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:unlock" {...props}></Icon>
