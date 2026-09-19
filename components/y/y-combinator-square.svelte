<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axti0sr1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="axti0sr1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:y-combinator-square" {...props}></Icon>
