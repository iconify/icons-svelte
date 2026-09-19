<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbl_nlblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="gbl_nlblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:users-rectangle" {...props}></Icon>
