<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyzo0y4mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="yyzo0y4mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:save-all" {...props}></Icon>
