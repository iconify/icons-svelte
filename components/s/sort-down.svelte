<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tua0aq4ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="tua0aq4ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sort-down" {...props}></Icon>
