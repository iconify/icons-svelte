<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_h70ea7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="z_h70ea7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:th-large" {...props}></Icon>
