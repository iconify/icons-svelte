<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xksh8usvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xksh8usvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:volume-down-filled" {...props}></Icon>
