<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efy6mqwgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="efy6mqwgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:swagger" {...props}></Icon>
