<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9eg8jbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r9eg8jbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:tasks" {...props}></Icon>
