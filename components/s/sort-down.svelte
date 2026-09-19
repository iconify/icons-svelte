<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7-5zibul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="g7-5zibul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:sort-down" {...props}></Icon>
