<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxr63lbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gxr63lbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:tap" {...props}></Icon>
