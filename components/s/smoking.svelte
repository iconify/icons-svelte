<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zixferb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1664};
const content = `<path class="zixferb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:smoking" {...props}></Icon>
