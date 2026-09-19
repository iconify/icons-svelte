<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcmmanq0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="lcmmanq0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:sleigh" {...props}></Icon>
