<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmb4kccad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="bmb4kccad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:snowflake" {...props}></Icon>
