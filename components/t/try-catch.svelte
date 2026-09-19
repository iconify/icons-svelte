<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3g_acbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b3g_acbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:try-catch" {...props}></Icon>
