<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbb__jcbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wbb__jcbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:shocked" {...props}></Icon>
