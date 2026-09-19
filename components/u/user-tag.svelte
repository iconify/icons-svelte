<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tis9c0sli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="tis9c0sli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:user-tag" {...props}></Icon>
