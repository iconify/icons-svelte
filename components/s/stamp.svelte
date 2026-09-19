<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6de9d63f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r6de9d63f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:stamp" {...props}></Icon>
