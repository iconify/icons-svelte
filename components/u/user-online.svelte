<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9ppw9blh.css';
import '../../css/s/sqkxxvbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="s9ppw9blh"/><path class="sqkxxvbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-online" {...props}></Icon>
