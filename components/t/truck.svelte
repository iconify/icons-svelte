<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc6qagbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="uc6qagbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:truck" {...props}></Icon>
