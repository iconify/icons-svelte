<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7965ybwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k7965ybwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-follow" {...props}></Icon>
