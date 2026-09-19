<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqh-8_m-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="zqh-8_m-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:square-o" {...props}></Icon>
