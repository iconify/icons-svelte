<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_k46jbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a_k46jbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-basket" {...props}></Icon>
