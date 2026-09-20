<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2c8fsbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t2c8fsbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:ship-solid" {...props}></Icon>
