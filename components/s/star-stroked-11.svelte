<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7p-x_2jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="k7p-x_2jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:star-stroked-11" {...props}></Icon>
