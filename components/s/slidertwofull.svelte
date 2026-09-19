<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1gy8vb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c1gy8vb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:slidertwofull" {...props}></Icon>
