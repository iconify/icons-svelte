<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njg7ipjzz.css';
import '../../css/s/sodj30gif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="njg7ipjzz"/><path class="sodj30gif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tag-edit" {...props}></Icon>
