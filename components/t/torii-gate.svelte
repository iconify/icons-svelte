<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7-w1bcfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t7-w1bcfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:torii-gate" {...props}></Icon>
