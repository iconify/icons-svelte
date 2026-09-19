<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m80vfrb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="m80vfrb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sleigh" {...props}></Icon>
