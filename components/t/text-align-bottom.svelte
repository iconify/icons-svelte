<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq5xwzb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dq5xwzb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:text-align-bottom" {...props}></Icon>
