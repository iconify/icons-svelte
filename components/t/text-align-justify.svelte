<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufjnn8nee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ufjnn8nee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:text-align-justify" {...props}></Icon>
