<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf4-6acwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="sf4-6acwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:vest" {...props}></Icon>
