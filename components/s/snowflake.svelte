<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8me2xqmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="c8me2xqmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:snowflake" {...props}></Icon>
