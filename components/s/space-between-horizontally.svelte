<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2ayqabna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k2ayqabna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:space-between-horizontally" {...props}></Icon>
