<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znpy9zbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="znpy9zbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:square" {...props}></Icon>
