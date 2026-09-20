<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yybedubjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":192,"height":192};
const content = `<path class="yybedubjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sanity-light" {...props}></Icon>
