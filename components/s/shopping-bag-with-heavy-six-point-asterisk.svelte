<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6bmqdbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g6bmqdbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-heavy-six-point-asterisk" {...props}></Icon>
