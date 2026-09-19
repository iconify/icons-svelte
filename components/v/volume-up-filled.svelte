<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j35eaocdf.css';
import '../../css/x/x0gu7cb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j35eaocdf"/><path class="x0gu7cb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:volume-up-filled" {...props}></Icon>
