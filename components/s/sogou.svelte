<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy8bvsbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yy8bvsbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:sogou" {...props}></Icon>
