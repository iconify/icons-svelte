<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uooe_ab7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="uooe_ab7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:virus-covid-slash" {...props}></Icon>
