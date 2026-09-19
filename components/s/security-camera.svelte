<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqinukb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xqinukb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:security-camera" {...props}></Icon>
