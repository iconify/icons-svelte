<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfmit8bob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pfmit8bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:shopping-help-information" {...props}></Icon>
