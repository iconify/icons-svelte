<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_vojfbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p_vojfbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:text-align-top" {...props}></Icon>
