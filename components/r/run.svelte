<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4d7t7yyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c4d7t7yyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:run" {...props}></Icon>
