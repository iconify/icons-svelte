<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohll3yb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":384};
const content = `<path class="ohll3yb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:view-agenda" {...props}></Icon>
