<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc-_-yb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oc-_-yb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:spades-symbol-flat" {...props}></Icon>
