<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlj2t5bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jlj2t5bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:star-half-stroke" {...props}></Icon>
