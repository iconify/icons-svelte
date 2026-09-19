<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkspzmbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qkspzmbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-subscript" {...props}></Icon>
