<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz9fz5bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="tz9fz5bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:tasks" {...props}></Icon>
