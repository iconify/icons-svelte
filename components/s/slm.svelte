<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd4xszy-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hd4xszy-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:slm" {...props}></Icon>
