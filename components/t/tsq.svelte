<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci-bfktii.css';
import '../../css/j/j01m1nbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ci-bfktii"/><path class="j01m1nbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tsq" {...props}></Icon>
