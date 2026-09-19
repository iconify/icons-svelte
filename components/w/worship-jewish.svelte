<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn7trv9jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rn7trv9jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:worship-jewish" {...props}></Icon>
