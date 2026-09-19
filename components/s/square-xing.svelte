<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp5m1r47p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="zp5m1r47p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:square-xing" {...props}></Icon>
