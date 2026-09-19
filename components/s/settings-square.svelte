<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueo529fdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="ueo529fdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:settings-square" {...props}></Icon>
