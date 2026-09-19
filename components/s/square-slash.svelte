<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi_4ffb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bi_4ffb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:square-slash" {...props}></Icon>
